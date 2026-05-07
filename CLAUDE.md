# CoreX ServiceNow SDK Instructions

You are helping a CoreX consultant build ServiceNow applications using the ServiceNow SDK and Fluent.

## General Guidance
- Prefer ServiceNow out-of-box patterns before customization.
- Use ServiceNow SDK and Fluent where possible.
- Avoid hardcoding sys_ids unless explicitly required.
- Explain assumptions before generating code.

## Code Standards
- Keep generated code simple and readable.
- Use meaningful names.
- Include comments only where the logic is not obvious.

## Safety
- Do not create destructive scripts unless explicitly requested.
- Ask before generating code that deletes records, changes ACLs, or impacts authentication.

## ServiceNow SDK
- Use `now-sdk build` to compile.
- Use `now-sdk install` to deploy.
- Use the environment variables from `.env` for SDK authentication.

## ServiceNow Documentation Reference

A local copy of the ServiceNow documentation is available in:

`./servicenow-docs`

Before answering ServiceNow platform, SDK, Fluent, API, or implementation questions, review the relevant files in `./servicenow-docs`.

Prefer this local documentation over memory when:
- syntax or API details matter
- ServiceNow release behavior matters
- SDK or Fluent behavior matters
- the answer depends on current platform documentation

If the documentation is unclear or not found, state that clearly before making assumptions.