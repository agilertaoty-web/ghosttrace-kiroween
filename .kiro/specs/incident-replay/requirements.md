# Incident replay requirements

This file records the requirements given to Kiro Web for the Kiroween 2026 entry.

- When the page opens, show the baseline state of a fictional network with an edge, a primary uplink, a standby uplink, and a core router.
- When an operator plays, seeks, or jumps between events, reconstruct the network state at the selected time. Visibly distinguish an outage from a failover and show when service is restored.
- When an operator filters by node or severity, show the matching events and keep the current incident time.
- When an operator selects an event, seek to it and show its details. Provide a way to reset playback and filters.
- When an operator downloads the log, provide a local plain-text record of the simulated events.
- Keep controls keyboard-accessible, give status changes text labels, and support narrow screens. The app should run as one HTML file without dependencies or external data.
