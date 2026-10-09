# Sample Vulnerable Node.js Repository

This is a sample Node.js repository created for testing purposes. It includes dependencies with known security vulnerabilities and some code that may trigger CodeQL alerts.

## Dependencies with Known Vulnerabilities

- **express**: 4.16.0 (has known CVEs)
- **lodash**: 4.17.4 (has CVE-2019-10744)
- **minimist**: 1.2.0 (has CVE-2020-7598)

## Code Vulnerabilities

- Command injection in `/exec` route
- Code injection via `eval` in `/eval` route

## Usage

1. Install dependencies: `npm install`
2. Start the server: `npm start`
3. Visit `http://localhost:3000/exec?cmd=ls` (dangerous!)
4. Visit `http://localhost:3000/eval?code=1+1`

**Warning**: This code is intentionally vulnerable. Do not use in production.


---
## Release Notes — v1.0.0-test-vlun-1-20260923-110056-r1

> Auto-generated on 2026-09-23 11:00:56 UTC (release 1/1 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-110056-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-121157-r1

> Auto-generated on 2026-09-23 12:11:57 UTC (release 1/1 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-121157-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122422-r1

> Auto-generated on 2026-09-23 12:24:22 UTC (release 1/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122422-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122527-r2

> Auto-generated on 2026-09-23 12:25:27 UTC (release 2/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122527-r2`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122632-r3

> Auto-generated on 2026-09-23 12:26:32 UTC (release 3/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122632-r3`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122737-r4

> Auto-generated on 2026-09-23 12:27:37 UTC (release 4/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122737-r4`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122843-r5

> Auto-generated on 2026-09-23 12:28:43 UTC (release 5/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122843-r5`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-122949-r6

> Auto-generated on 2026-09-23 12:29:49 UTC (release 6/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-122949-r6`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-123054-r7

> Auto-generated on 2026-09-23 12:30:54 UTC (release 7/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-123054-r7`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-123159-r8

> Auto-generated on 2026-09-23 12:31:59 UTC (release 8/8 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-123159-r8`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-124124-r1

> Auto-generated on 2026-09-23 12:41:24 UTC (release 1/5 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-124124-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-124229-r2

> Auto-generated on 2026-09-23 12:42:29 UTC (release 2/5 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-124229-r2`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-124334-r3

> Auto-generated on 2026-09-23 12:43:34 UTC (release 3/5 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-124334-r3`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-124439-r4

> Auto-generated on 2026-09-23 12:44:39 UTC (release 4/5 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-124439-r4`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-1-20260923-124545-r5

> Auto-generated on 2026-09-23 12:45:45 UTC (release 5/5 for repo test-vlun-1)

- **Tag**: `v1.0.0-test-vlun-1-20260923-124545-r5`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-050042-r1

> Auto-generated on 2026-09-29 05:00:42 UTC (release 1/1 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-050042-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-050856-r1

> Auto-generated on 2026-09-29 05:08:56 UTC (release 1/1 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-050856-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052211-r1

> Auto-generated on 2026-09-29 05:22:11 UTC (release 1/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052211-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052317-r2

> Auto-generated on 2026-09-29 05:23:17 UTC (release 2/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052317-r2`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052422-r3

> Auto-generated on 2026-09-29 05:24:22 UTC (release 3/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052422-r3`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052527-r4

> Auto-generated on 2026-09-29 05:25:27 UTC (release 4/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052527-r4`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052632-r5

> Auto-generated on 2026-09-29 05:26:32 UTC (release 5/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052632-r5`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052738-r6

> Auto-generated on 2026-09-29 05:27:38 UTC (release 6/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052738-r6`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052844-r7

> Auto-generated on 2026-09-29 05:28:44 UTC (release 7/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052844-r7`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-052949-r8

> Auto-generated on 2026-09-29 05:29:49 UTC (release 8/8 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-052949-r8`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-173423-r1

> Auto-generated on 2026-09-29 17:34:23 UTC (release 1/5 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-173423-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-173529-r2

> Auto-generated on 2026-09-29 17:35:29 UTC (release 2/5 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-173529-r2`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-173634-r3

> Auto-generated on 2026-09-29 17:36:34 UTC (release 3/5 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-173634-r3`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-173739-r4

> Auto-generated on 2026-09-29 17:37:39 UTC (release 4/5 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-173739-r4`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20260929-173845-r5

> Auto-generated on 2026-09-29 17:38:45 UTC (release 5/5 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20260929-173845-r5`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20261009-070238-r1

> Auto-generated on 2026-10-09 07:02:38 UTC (release 1/2 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20261009-070238-r1`
- **Branch**: `main`


---
## Release Notes — v1.0.0-test-vlun-5-20261009-070343-r2

> Auto-generated on 2026-10-09 07:03:43 UTC (release 2/2 for repo test-vlun-5)

- **Tag**: `v1.0.0-test-vlun-5-20261009-070343-r2`
- **Branch**: `main`
