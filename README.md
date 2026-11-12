# Original iPhone UI captures, BigMoeOnEdge v0.42.0

Recorded on a 12 GB-class iPhone, iOS 26.6.2, from the clean v0.42.0 source tag
bb205782f622af47c704d4b5b6e8d48ad3aa9fd0, signed Release arm64 with Xcode 27.1 / Swift 6.4.

The four original 1206x2622 PNG screenshots show Chat, Plan, Models and Settings.
The original MP4 is a single 23.905-second native XCTest screen recording, with no cuts,
re-encoding or speed changes. It navigates a saved, generated synthetic red/blue conversation
after an ordinary app relaunch and model reload. Sharing is Off. The existing Qwen3.6-35B-A3B
Q4_K_M and matching Q8_0 projector were reused.

These captures were requested for the README in
https://github.com/Helldez/BigMoeOnEdge/pull/495#issuecomment-6725729425 .
They are available for use in the project README and documentation.

The iOS client tests passed 74/74. Native model loading, Markdown rendering and composer Stop
after visible output, followed by the ordinary recovery answer 4, passed. The earlier image
follow-up run saved Red then Blue but ended in a confirmed process-limit kill; that interrupted
end-to-end UI run is not reported as passed. The separate report and matched system evidence are
https://github.com/Helldez/BigMoeOnEdge/issues/573 .

Only these reviewed originals are included. Failed selector attempts, device-wide system
reports, private library screenshots, credentials and signing data are excluded.
