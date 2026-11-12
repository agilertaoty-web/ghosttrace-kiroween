# GhostTrace

GhostTrace is an interactive replay of a fictional network outage. It connects a chronological incident log to a topology diagram, so an operator can see when a primary uplink fails, when the standby path takes traffic, and when service is verified.

## Try the replay

Open [GhostTrace on GitHub Pages](https://agilertaoty-web.github.io/ghosttrace-kiroween/) or open `index.html` in a modern browser. No setup or credentials are required.

1. Select **Play** or scrub the replay slider to see the network change.
2. Select a timeline event to jump to it. Compare the primary and standby paths during failover.
3. Filter the event list by severity or node. Download the incident log for an offline debrief.

All events and node identifiers are fictional. The application runs locally in the browser and does not need telemetry, an API key, or an external service.

## Kiroween 2026

Category: **Costume Contest**. The dark observatory design uses color and text to make degradation, outage, failover, and recovery easy to tell apart.

Kiro Web first developed the pure timeline operations. A follow-up prompt had Kiro Web incorporate that logic into the complete standalone browser app, including the simulated outage, interactive topology, controls, filters, and log download. Kiro Web then supplied a patch to keep keyboard focus during replay and reset the filters. Codex coordinated the work, applied that patch, verified the app in a browser, and prepared the repository and submission. The requirements and design are documented under [`.kiro`](.kiro/).

## License

[MIT](LICENSE)
