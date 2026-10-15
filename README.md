# aap-example-go

A minimal **Go (standard library)** app, kept as a deploy example for [AI Admin Panel](https://aiadminpanel.com).

AI Admin Panel deploys it from this repository with **Git Deploy** (and **AI Deploy**) and checks
the result regularly: the page at `/` must contain the marker `aap-example:go`. Use it to see how
your own Go (standard library) project is built, or as a starting point.

No dependencies beyond the standard library: `go build` and run the binary.

- The app listens on `$PORT` (default 8080).
- No secrets in this repository.
- License: MIT.
