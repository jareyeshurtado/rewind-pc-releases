# Rewind club software: release channel

Update channel for the Rewind software installed at partner clubs. Club PCs read `manifest.json`
from here and install only releases whose signature (`manifest.json.sig`) matches the key built
into their software.

This repository is maintained by `tools/make_release.py`; do not edit its files by hand.

Proprietary software, all rights reserved. See [LICENSE](LICENSE).
