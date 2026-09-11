# TARGET: today's build

- **Thing:** RoadRunner, a one-page weekend road-trip planner where a visitor answers a short preference quiz and receives matching sample drive ideas.
- **Audience:** College students who want to plan an affordable, memorable weekend road trip without sorting through a dense set of filters.
- **Requirements:** One working primary interaction: enter a starting city, dates, trip duration, budget, and activity preferences, then view understandable matching route results; selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A cinematic, calm, nostalgic road-trip feel: golden-hour travel imagery; ocean blue, sand, redwood green, and orange; a short card-based quiz leading to a map-and-results split view, large tactile pills and sliders, postcard-style saves, and a “Shuffle my weekend” control.
- **Test:** I can complete the quiz, understand selected preferences and the suggested sample routes, test that an over-budget or too-long route is not shown, and point to my standing rule’s effect in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
