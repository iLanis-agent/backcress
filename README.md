# Backcress 1.0 TEST
Native Android Double Back room-visit puzzle. Android 8+ (min26), target35. Package com.gg007.backcress. Twelve original unique boards on a compact 5x4 grid.

## Rules
Double Back on a 5x4 grid. Draw one closed loop through the center of every cell exactly once, using horizontal and vertical links. No crossings, branches or separate loops. Every outlined connected room must be entered exactly twice and exited exactly twice: four selected links cross its border. Visits may contain one or more cells. This edition has no blocked cells. Tap gaps between neighboring centers to toggle links. Undo/reset, levels and next; saved palette and optional room letters. No timer or score. Double Back rules by Palmer Mebane.

## Download and status
https://mega.co.nz/#!oIVVQAQL!h1Mkdhw5TmjLw95fS6hae_mfk7N0WVpjidg6at8cVsA
APK SHA256 010d04d27d184fde8cee7e6a0c06174709ed44ab84ee96af17bd7cfbcab96b07; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
The portable seed-671109 generator exhaustively enumerates all fourteen Hamiltonian cycles on the 5x4 grid by vertex-path search. Twelve selected connected-room layouts each admit exactly one of these cycles, and all twelve solutions differ. An independent degree-pruned edge-subset enumeration recovers the same fourteen cycles. All 168 cycle-board comparisons and 240,000 seeded arbitrary edge subsets agree between production degree/border/bit-flood checks and an independent coordinate traversal that counts room entries. Full coverage, single loop, exactly two visits per room, bounds, undo/reset, solved lock and malformed states pass. Actual drawing-adapter taps solve all twelve and check undo/replay, next, levels, menu, privacy and saved palette/room letters. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 198 prior live studio descriptions and byte-current 803 web registry entries using functional terms. No Double Back or twice-per-room Hamiltonian loop match in this partial corpus. Cloverroad makes one visit per room with optional off-road cells; Springloop has two disjoint loops balancing room visits. Backcress instead uses one loop through every cell and requires two separate visits to each room. Known Double Back adaptation, rules credited to Palmer Mebane; original generated room layouts, code and visuals. No copied layouts/code/art or global invention claim. Six fetched rule pages across six sites agree on core rules. No history claim.
Rules https://mellowmelon.wordpress.com/double-back/ ; independent rules https://www.gmpuzzles.com/blog/2013/07/from-the-foxgers-den-34-double-back/ .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/backcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.backcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Backcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 199-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/m50079xlci89-backcress-source-archive . Repository https://github.com/iLanis-agent/backcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
