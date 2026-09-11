# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page music discovery site where a visitor enters an artist and receives up to eight source-backed similar-artist results displayed as bubbles around the search bar.
- **Audience:** Someone who wants reliable starting points for finding more music from an artist they already enjoy.
- **Requirements:** Search an artist through the approved music-data source; show up to eight returned artists, clear loading and error states, and the source for every result; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Browser code plus a server-side proxy for Last.fm. Keep the API key out of the repository and browser. No required visitor accounts, runtime AI, private data, or analytics. Preserve the example and current GitHub Pages publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Keep the visually rich centered search bar and animated result bubbles surrounding it; make loading, errors, and source attribution easy to understand.
- **Test:** I can search a known artist and see up to eight provider-returned results, verify the visible Last.fm attribution, test an unknown artist or offline error, and confirm no fallback results are invented.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
