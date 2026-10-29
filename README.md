# Flashloop website preview

Orange: https://odhasu.github.io/flashloop-clone/

Cyan (`#78c2d6`): https://odhasu.github.io/flashloop-clone/cyan/

This repository contains two static frontend exports of the Flashloop reference clone with shared local images, fonts, and optimized MP4 videos. The original source repository and its history remain private.

Primary navigation includes all observed tabs except Super Agent, including Faceless Studio. Authentication, payments, generation and email delivery require the original service; this preview recreates the frontend.

Built from source commit `847202cf0d04a27734d842e7bb210627661dc9bc` on 29 October 2026. ESLint, TypeScript, both production exports, thirteen tests, 110 pages, and 531 referenced resources passed before publication. All 204 optimized media outputs passed a one-second FFmpeg decode check.

Video optimization reduces 407,523,707 bytes to 259,730,057 bytes (36.3%). Videos load near the viewport and pause offscreen or when the document is hidden. Reduced-motion preferences are respected. The existing desktop scroll sequence is preserved. Cyan clouds retain their shading and transparency.
