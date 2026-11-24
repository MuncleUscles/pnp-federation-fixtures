# pnp.fun controlled federation fixtures

This repository contains public fixtures for testing pnp.fun's GitHub source
registry and account-to-wallet claim flow. It is controlled by the pilot
operators and is **not independent outside participation**.

The identity-control fixture is a tiny, established Lean theorem added through
a GitHub pull request. Its purpose is to supply a real merged source PR, an
immutable source commit, and a licensed file for testing the claim procedure.
It does not assert mathematical novelty, new research toward P versus NP, or
entitlement to points. Source indexing earns **zero points**.

An operator may register the immutable source and request a native author
claim using a locally held wallet. The actual source PR author must then post
the contract's exact public challenge on that PR. The verifier re-fetches that
comment, checks the numeric GitHub account and exact challenge, and submits its
evidence for native settlement. A successful controlled trial demonstrates
that mechanism for the participating account; it does not verify any outside
author, establish real-world identity or mathematical priority, or demonstrate
Sybil resistance.

Keep private keys outside this repository and GitHub. Only public challenges
and signatures belong in a claim. No outside author's wallet is assigned by
this fixture, and unclaimed outside-author credit must remain unclaimed.

No GitHub Actions workflow or native-contract client runs from this repository.
The reviewed pnp.fun operator tools process its public source as untrusted data.
The source registry's `not-locally-verified` label is documentary; registration
is not acceptance of a formal contribution.

All files are provided under the [MIT License](LICENSE).
