# Flashloop website preview

Orange: https://odhasu.github.io/flashloop-clone/

Mint (`#9ce6da`): https://odhasu.github.io/flashloop-clone/cyan/

Blue (`#3344d6`): https://odhasu.github.io/flashloop-clone/blue/

This repository contains three static frontend exports of the Flashloop reference clone with shared local images, fonts, and optimized MP4 videos. The original source repository and its history remain private.

Primary navigation includes all observed tabs except Super Agent, including Faceless Studio. Authentication, payments, generation and email delivery require the original service; this preview recreates the frontend.

Built from source commit `6c4af174512915971d9a4f90c33d785a79e9dbba` on 29 October 2026. ESLint, TypeScript, all three production exports, fifteen tests, 165 pages, 593 referenced assets, and 108 local destinations passed before publication. The static icon comparison matched 395 controls across nine reference pages. A subsequent browser comparison corrected the image/video composer and voice icons. All 204 optimized media outputs previously passed a one-second FFmpeg decode check.

Each additional palette updates 89 theme tokens and ten branded assets. Solid mint controls use dark text (13.18:1 contrast). Solid blue controls use white text (7.15:1); blue accent text on charcoal uses a lighter tint. The blue footer uses white labels, provider icons, and an animated white wordmark. Pricing card interiors keep white text on charcoal. The blue hero reuses the mint grid and lighting assets exactly, with softer blue clouds (#707ce2). Its main accent remains #3344d6. Cloud shading and transparency are preserved.

Video optimization reduces 407,523,707 bytes to 259,730,057 bytes (36.3%). Videos load near the viewport and pause offscreen or when the document is hidden. Reduced-motion preferences are respected. The existing desktop scroll sequence is preserved. Clouds retain their shading and transparency and fade upward after image decoding, including refreshes. The production frontend was reviewed in the ChatGPT in-app browser at desktop, tablet, and phone widths.

Individual trend-template links and other unimplemented destinations open the original Flashloop site. This is a frontend reference preview; authentication, generation, payments, and email delivery require a connected service.
