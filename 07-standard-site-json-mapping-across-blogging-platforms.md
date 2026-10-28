<figure prefix="spdx: http://spdx.org/rdf/terms#" property="copyrightNotice" typeof="ImageObject" vocab="http://schema.org/"><img src="https://cdn.jsdelivr.net/gh/YourOnly-One/content.gamut/rsc/img/documentcompare-elconomeno-cc0.svg" alt="document compare"><figcaption>〈<a href="https://openclipart.org/detail/341964/document-compare" class="p-name" property="name" title="document compare">document compare</a>〉 by <span property="author" typeof="Person" style="text-transform: capitalize;"><a href="https://openclipart.org/artist/elconomeno@email.com" class="h-card p-author p-name u-url" property="name url" rel="author noopener noreferrer" title="elconomeno">elconomeno</a></span> is marked <span class="u-license" property="license" typeof="spdx:License"><a href="https://creativecommons.org/publicdomain/zero/1.0/" property="spdx:name" rel="license spdx:CC0-1.0" title="CC0 1.0 Universal (SPDX-License-Identifier: CC0-1.0)">CC0 1.0 Universal</a></span>.</figcaption></figure>

# Standard.site JSON Mapping Across Blogging Platforms

<!-- Compare standard.site JSON theme fields with platform-specific keys. A quick reference for anyone working with AT Protocol records. -->

Different blogging platforms use different JSON names (also known as keys, property names, or fields) for their theme configuration settings. When inspecting records directly via [pds.ls](https://pds.ls) it can get confusing fast.

This reference maps **standard.site** JSON fields to their platform-specific equivalents so anyone can quickly translate between different naming schemes.

| standard.site | accent | background | foreground | accentForeground | Extras |
|:--|:--:|:--:|:--:|:--:|:--:|
| GreenGale | `accent` | `background` | `text` | `background` | `codeBackground` |
| Leaflet | `accentBackground` | `backgroundColor` | `primary` | `accentText` | `pageBackground` |
| MySky | (standard) | (standard) | (standard) | (standard) | — |
| Offprint | — | — | — | — | — |
| pckt | `accent` | `background` | `text` | `surfaceHover` | `link` |

Notes:

- **(standard)** means the platform is only using standard.site properties.
- This document will be updated as new platforms adopt the standard.site lexicon, or invent their own variations.

If you are debugging theme rendering issues, migrating styles between platforms, or building tooling around AT Protocol records, this mapping should hopefully save you precious time.

Enjoy!

---

Cover image: 〈[document compare](https://openclipart.org/detail/341964/document-compare)〉 by [elconomeno](https://openclipart.org/artist/elconomeno@email.com) is marked [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

This article was first published on [GreenGale](https://greengale.app/sera.is.youronly.one/3mfbgm2ggci2a) platform on 2026-02-20 [@250.00](https://beattime.live) (14:00:39 UTC+8).

---

〈Standard.site JSON Mapping Across Blogging Platforms〉 © 2026 [Yohan Yukiya Sese Cuneta](https://iam.youronly.one) ([ISNI](https://isni.org/isni/0000000530977207) | [ORCID iD](https://orcid.org/0000-0003-4755-4548)).\
License: [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) ([CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)), except where [noted](https://im.youronly.one/p/legal-notice/).
