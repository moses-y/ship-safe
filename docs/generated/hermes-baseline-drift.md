## Hermes baseline drift

Pinned: **v0.21.0** (`v2026.8.31`, `29112bef0992`)

20 newer release(s):

| release | tag | commit | published |
| --- | --- | --- | --- |
| Hermes Agent canary v0.23.1+canary.20261115T064406Z | `v0.23.1+canary.20261115T064406Z` | `` | 2026-11-15T07:52:37Z |
| Hermes Agent canary v0.23.1+canary.20261114T064334Z | `v0.23.1+canary.20261114T064334Z` | `` | 2026-11-14T07:46:34Z |
| Hermes Agent canary v0.23.1+canary.20261113T064447Z | `v0.23.1+canary.20261113T064447Z` | `` | 2026-11-13T08:06:48Z |
| Hermes Agent v0.23.1 | `v0.23.1` | `` | 2026-11-10T01:42:15Z |
| Hermes Agent v0.23.0 — The Hearth Release | `v0.23.0` | `` | 2026-11-05T21:32:33Z |
| Hermes Agent v0.22.7 | `v0.22.7` | `` | 2026-11-03T21:53:16Z |
| Hermes Agent v0.22.6 | `v0.22.6` | `` | 2026-11-02T17:18:36Z |
| Hermes Agent v0.22.5 | `v0.22.5` | `` | 2026-10-23T05:28:45Z |
| Hermes Agent v0.22.4 | `v0.22.4` | `` | 2026-10-21T18:49:24Z |
| Hermes Agent v0.22.3 | `v0.22.3` | `` | 2026-10-21T12:21:11Z |
| Hermes Agent v0.22.2 | `v0.22.2` | `` | 2026-10-15T08:21:32Z |
| Hermes Agent v0.22.1 | `v0.22.1` | `` | 2026-10-14T23:59:24Z |
| Hermes Agent v0.22.0 — The Threshold Release | `v0.22.0` | `` | 2026-10-14T03:21:46Z |
| Hermes Agent v0.21.7 | `v0.21.7` | `` | 2026-10-12T05:53:41Z |
| Hermes Agent v0.21.6 | `v0.21.6` | `` | 2026-10-08T11:51:57Z |
| Hermes Agent v0.21.5 (v2026.9.24) | `v2026.9.24` | `` | 2026-09-24T10:09:38Z |
| Hermes Agent v0.21.4 (v2026.9.21) | `v2026.9.21` | `` | 2026-09-21T18:10:55Z |
| Hermes Agent v0.21.3 (v2026.9.14) | `v2026.9.14` | `` | 2026-09-14T16:04:14Z |
| Hermes Agent v0.21.2 (v2026.9.11) | `v2026.9.11` | `` | 2026-09-11T19:20:31Z |
| Hermes Agent v0.21.1 (v2026.9.7) | `v2026.9.7` | `` | 2026-09-07T22:17:01Z |

### Surfaces with upstream changes

Each of these needs its detector re-checked against the new snapshot. **No status may move to covered without that.**

- **acp** — 20 file(s) changed
  - `acp_adapter/auth.py`
  - `acp_adapter/catalog.py`
  - `acp_adapter/commands.py`
  - `acp_adapter/content.py`
  - `acp_adapter/edit_approval.py`
  - `acp_adapter/elicitation.py`
  - `acp_adapter/entry.py`
  - `acp_adapter/events.py`
  - `acp_adapter/gateway_commands.py`
  - `acp_adapter/gateway_media.py`
  - ...and 10 more

### What this pull request does not do

Nothing is updated. The baseline JSON, the coverage matrix and every status are untouched. Moving the pin is a reviewed change that follows the procedure in `docs/hermes-coverage-matrix.md`, including re-checking the known-CVE record.
