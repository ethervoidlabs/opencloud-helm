# Security policy

Report suspected vulnerabilities privately to the repository owner before
opening a public issue. Do not include credentials, tokens, user data, or
private cluster details in a report.

All chart changes require review before merging to `main`. Enabled images must
use a reviewed immutable `tag@sha256:digest` reference, and enabled component
credentials must come from a secret manager or an explicitly supplied Secret.
