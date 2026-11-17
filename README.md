# glowcap site media

Rendered media that [glowcap.org](https://glowcap.org) serves, kept out of the
[glowcap](https://github.com/glowcap-org/glowcap) repository so its clone stays
small.

Each release here holds one approved render as its assets. The glowcap
repository pins the exact files the site uses, with their sizes and SHA-256
hashes, in `site/video/published.json`, and the site build downloads and
verifies them. A release that no pin names can be deleted.

The media is made from the glowcap repository's sources and shares its
[Apache-2.0 license](https://github.com/glowcap-org/glowcap/blob/main/LICENSE-APACHE).
