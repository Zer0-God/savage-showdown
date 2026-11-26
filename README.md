# Savage Showdown — Combat Lab 0.1

Open index.html in a modern browser, or upload index.html to a static web host (GitHub Pages, for example). No dependencies or server required. On iPhone, use a hosted HTTPS URL in Safari; the Files preview may not run JavaScript. Rotate to landscape for more space.

Select player, opponent, variation, arena and mode, then Start/reset. Move toward the opponent using Forward. Directional sequences are buffered for 380 ms between presses. F+/B+/D+ primes a simultaneous directional attack. Training mode gives a Try button for catalog entries and resets the dummy on previews. Block is held, breaker costs two bars, SAVAGE costs three. The CPU is a simple opponent, not a sophisticated AI.

The roster JSON contains 24 fighters and 1,392 catalog entries. The first three fighters' original inputs and names were transcribed from the conversation, with provisional simplified damage and effect metadata; the other 21 come from the supplied JSON. The HTML embeds the data so it runs offline. If editing roster.json, replace the JSON inside the HTML data script as well.

This is a browser combat sandbox, not Unreal Engine or a native game. Moves use shared procedural poses and single damage events, not authored multi-hit animations; advanced inputs, hit levels, cancel rules, frame data, environment geometry, controller support, networking, story, and cinematic endings require further implementation. Arena selection changes labels only. Some input collisions and advanced paths remain unvalidated. The prototype is not a console-ready build. The long-term plan is to port validated data and mechanics to a production engine with platform-specific builds and licensed character assets.
