# profile 1.0.2

- New `dm_from_profile()` (#10).


# profile 1.0.1

- `?read_pprof` uses example conditional on availability of RProtoBuf.

# profile 1.0

Initial release. Exported functions:

- `read_rprof(path, ..., version = "1.0")` and `write_rprof(x, path)` for reading files generated by `Rprof()` and writing compatible files.

- `read_pprof(path, ..., version = "1.0")` and `write_pprof(x, path)` for reading and writing files understood by `pprof`.

- `validate_profile(x)` for validating profile data, called by the readers and writers.
