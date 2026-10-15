![Djehuty AI Sesh Kemet](𓏞𓀀%20Sesh%20Kemet%20𓆎𓅓𓏏𓊖%20.jpg)
# Djehuty AI (Prototype)

*Reducing prompt friction by aligning intent before anything is generated.*

> **Status: UI mockup. All responses are simulated.** There is no AI backend yet.

## The problem
AI building tools need precise prompts. When a request is vague, users lose time and credits on misunderstandings, rework and bugs.

## The idea
Djehuty AI is a concept for a three-step flow:

1. **Interpreter**: restates the user's plain-language request as a few simple choices to confirm.
2. **Builder**: creates the result based on the confirmed intent.
3. **Auditor**: checks the result against the confirmed intent before it is delivered.

The name comes from Djehuty, the Egyptian name of Thoth, associated with writing and wisdom.

## What exists today
- A clickable front-end mockup of the flow (describe → confirm → build & verify), made by a solo, non-technical builder using AI-assisted tools (v0).
- All choices, progress steps and verification results are hardcoded sample data.

## What is planned (not built yet)
- A real intent-analysis step using Meta's Muse models
- Code generation and test-based verification
- A small benchmark comparing retries and tokens used with and without the confirm-first flow

## Run locally
1. Install Node.js
2. `npm install`
3. `npm run dev`

## Design
Deep umber (#16110D), dark teal-charcoal (#1F2A2E), turquoise (#1FA8A3) and antique gold (#C9A24B).

## Notes
Independent project, not affiliated with or endorsed by Meta. Prepared as part of an application to the Meta Global AI Developer Hackathon.

## License
MIT
