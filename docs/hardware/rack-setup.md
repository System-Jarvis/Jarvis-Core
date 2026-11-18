
# J.A.R.V.I.S. — Rack Setup

## Overview

This document records the physical installation and ongoing setup of the J.A.R.V.I.S. server rack.

The rack infrastructure supports the self-hosted J.A.R.V.I.S. platform and its future development.

## Rack Cabinet

**Manufacturer:** APC

**Model:** AR1000A NetShelter

**Purpose:** House and organize the J.A.R.V.I.S. server infrastructure.

## Server Installation

### Equipment

Four Supermicro / Thinkmate rackmount servers were acquired for the J.A.R.V.I.S. project.

### Installation Status

- Three working servers were reported installed in the cabinet
- The primary J.A.R.V.I.S. server was successfully powered on

## Installation Challenges

### Rack Rail Orientation

During installation, a set of server rails was mounted upside down.

The rail release mechanism became inaccessible, preventing normal rail removal.

Observed conditions included:

- The rails could slide but would not detach
- The release lever was obstructed
- No accessible secondary release tab was identified
- No usable release access opening was identified

The upside down rails were forcefully removed and replaced with spare rails.

### Front-Panel Clearance

Front-mounted loops or brackets on the servers interfered with closing the rack cabinet door.

One bracket assembly included the server power button.

Reseating the servers and moving the vertical rack rails fixed this issue.

## Remaining Setup Tasks

- [ ] Verify network connectivity.
- [ ] Configure and verify remote management access.
- [ ] Record final rack layout and equipment positions.

## Documentation Maintenance

This document should be updated whenever:

- Equipment is installed or removed
- Mounting hardware is changed
- Physical installation issues are resolved
- Cabling or power distribution changes
- Rack organization is modified

Sensitive infrastructure information should be excluded from publicly accessible documentation.

---

**Project:** J.A.R.V.I.S.

**Documentation Phase:** Phase 0 — Base Documentation

**Infrastructure Phase:** Phase 1 — Server Infrastructure Setup
