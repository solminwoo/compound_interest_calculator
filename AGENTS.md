# compound_interest_calculator engineering guidance

<!-- ecc-engineering-defaults:start -->
## Engineering defaults
For coding work, read [.engineering/defaults.md](.engineering/defaults.md).
These are shared fallback conventions; the existing project owner, nested instructions,
skills, model choices, domain contracts and stronger verification/release gates remain authoritative.
No hooks, permissions, MCP services or background automation are installed by this guidance.

### Project adaptation
Create React App with root package-lock.json. Candidate checks: `npm test -- --watchAll=false` and `npm run build`. Add behavioral assertions for interest calculations, rounding and invalid input when changing behavior; preserve the current framework until an upgrade is requested.
<!-- ecc-engineering-defaults:end -->
