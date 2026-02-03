---
layout: post
title: "Introducing PowerFox for PowerPC-based Macs"
date: 2026-01-28
description: "I'm excited to announce the release of PowerFox Browser for PowerPC-based Macs running Mac OS X 10.5 Leopard and Mac OS X 10.6 Snow Leopard."
---

<a href="/assets/img/2026-01-28-powerfox-ppc.jpg"><img src="/assets/img/2026-01-28-powerfox-ppc.jpg" alt="PowerFox for PowerPC Screenshot" style="max-width: 100%;"></a>

Hello everyone,

Hello all, I'm very happy to announce the beta release of PowerFox Browser for the PowerPC architecture.

PowerFox for PPC is not a derivative of TenFourFox. Rather, it is a brand-new browser for PowerPC, built from the same codebase as the 10.6 Intel variant. To refresh your memory, this brings a modern web engine (UXP) with excellent support for the modern internet, with features such as OpenGL acceleration, coloured emoji, modern HTML/CSS/JavaScript support, container tabs, language packs, video codecs (no need for an "enabler"), and much more.

Right now, PowerFox is offered in a beta state for PowerPC - expect bugs and other issues, and please report any of them that you encounter to this thread or on the GitHub bugtracker.

### System Requirements
- Mac OS X 10.5 Leopard
- PowerPC G4 or PowerPC G5 processor
- 1 GHz processor for proper video playback

### Known Issues/Limitations
- JavaScript JIT (Just-In-Time) compilation is currently unimplemented. This means that JavaScript performance will be slower than that of TenFourFox and its derivatives, please consider installing an Ad Blocker and keeping expectations within reason.
- Certain SVG images will not render correctly - under investigation.


PowerFox for PowerPC wouldn't have been possible without code written by Dr. Cameron Kaiser for TenFourFox, the developers behind the UXP web engine - namely dbsoft, and the Basilisk project. Thank you!

You can download a build from the <a href="{{ site.baseurl }}/download.html">download page</a>.

Thank you all for your continued support of PowerFox!