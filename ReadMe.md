secpwgen.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===========
~~[wheel](https://gitlab.com/KOLANICH/secpwgen.py/-/jobs/artifacts/master/raw/dist/lime-0.CI-py3-none-any.whl?job=build)~~
~~![GitLab Build Status](https://gitlab.com/KOLANICH/secpwgen.py/badges/master/pipeline.svg)~~
![GitLab Coverage](https://gitlab.com/KOLANICH/secpwgen.py/badges/master/coverage.svg)
~~[![GitHub Actions](https://github.com/KOLANICH-tools/secpwgen.py/workflows/CI/badge.svg)](https://github.com/KOLANICH-tools/secpwgen.py/actions/)~~
![N∅ dependencies](https://shields.io/badge/-N∅_deps!-0F0)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-tools/secpwgen.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

A pure python dropin replacement for [secpwgen](https://linux.die.net/man/1/secpwgen).  Some features are added like QR Code generation.

In order to this work on python<3.6 you need to manually install the [secrets library](https://raw.githubusercontent.com/python/cpython/master/Lib/secrets.py) by downloading it and putting into the dir where default python packages reside.
