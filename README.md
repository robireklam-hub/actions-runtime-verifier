# Actions Runtime Verifier

Minimal public verifier for GitHub Actions runtime compatibility.

It currently verifies the exact pinned versions used by the private Bybit EU Trading Radar workflows:

- `actions/github-script@v9.0.0`
- `actions/upload-artifact@v7.0.1`

The workflow proves Node 24+ runtime compatibility, successful Octokit access to this repository, and a real artifact upload.

This repository contains no Bybit Radar source code, production secrets, API keys, Railway credentials, trading logic, persistence, capture, order, or execution capability.

The verifier runs only when its workflow file changes, or when manually dispatched.
