# Replay design

The Kiro Web conversation started with the timeline operations. The state is derived from the ordered event stream and current elapsed time, allowing playback and backward seeking to share the same state calculation. Filtering operates on the event list independently of replay state.

In the follow-up, Kiro Web was asked to integrate those operations into a complete, standalone HTML app. The requested interface pairs a clickable topology with an incident timeline, uses a dark olive and amber visual palette, and keeps node status available as text.
