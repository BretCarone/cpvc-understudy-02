# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page music discovery site where a visitor enters an artist they like and receives animated bubble suggestions for other artists to explore.
- **Audience:** Someone who wants to find more music to listen to, starting from an artist they already enjoy.
- **Requirements:** One working primary interaction: enter an artist and show understandable suggestion bubbles; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A visually rich, centered artist input with animated suggestion bubbles appearing around it; feel playful, immersive, and easy to scan.
- **Test:** I can enter an artist, receive suggestions, confirm that the bubbles remain understandable at a boundary such as an empty input, and see the curated-discovery label in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
