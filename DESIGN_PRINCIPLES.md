# Simple to start, explicit about guarantees

A new user should reach a useful result without learning every internal subsystem.

- One clear primary action and one canonical getting-started path per use case.
- Show prerequisites, exact version, expected result and recovery steps together.
- Offer documented, versioned defaults; keep the selected primitives and assumptions inspectable.
- Never silently weaken a protection or hide a consequential side effect to make a demo succeed.
- Use actionable errors. Claim that no effect occurred only when the system can establish that fact.
- Separate ordinary use from advanced settings and research detail.
- Do not create repositories, services or configuration options without a maintenance reason.

A first local result in under ten minutes on a supported environment is a usability target to measure, not a validated performance claim. Test with people outside the development team and record where they need help.
