# GrabCove-build

This public repository contains only GitHub Actions workflows for GrabCove.

Release workflows check out the tagged source from the private
khiempham-dev-nextsky/GrabCove repository into an ephemeral runner workspace,
build on standard public GitHub-hosted runners, and publish signed artifacts to
khiempham-dev-nextsky/GrabCove-releases. Application source, secrets, and build
artifacts are never committed here.

