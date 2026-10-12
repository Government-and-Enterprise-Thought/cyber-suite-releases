# Cyber Suite — single-tenant releases

Download location for the **Cyber Suite single-tenant customer export**.

## What is here

Each release carries one asset, `cyber-suite-single-tenant.zip`, containing a
runnable build:

| File | What it is |
| --- | --- |
| `cyber-suite` | the application, a static `linux/amd64` binary |
| `cyber-suite-single-tenant-v{version}-image.tar` | the same build as a container image |
| `Dockerfile` | reference runtime |
| `setup.env.sample` | the configuration to fill in |
| `LOAD-AND-RUN.md` | how to start it |
| `BUILD-INFO.txt`, `SHA256SUMS` | provenance and checksums |
| `grafana/*.json` | the Policy, Risk, Assurance, GRC and Advisory dashboards |

Verify what you downloaded with `shasum -c SHA256SUMS` before running it.

## What is NOT here

**No source code.** This repository exists only to distribute release
artifacts. Source is held privately and is not published.

## Versions

Releases are tagged `cyber-suite-single-tenant-v{X.Y.Z}`, matching the Cyber
Suite version the build was cut from. Take the newest unless you have been
asked for a specific one.
