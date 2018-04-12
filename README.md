# Xapi Travis Scripts

Scripts used for various Travis operations in `xapi-project` packages.

Currently provides

- `coverage.sh`, providing support for `bisect` and `ocveralls` coverage reports.
The following envariament variables can be defined to override the default settings:

    - `TEST_DEPS`: additional opam test packages to install before running the tests
    - `TEST_CMD`: command to run the tests

- `aspcud`: a folder with centos7 rpms for aspcud, the solver for opam in our travis images
