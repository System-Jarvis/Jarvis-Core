# J.A.R.V.I.S. — Hardware Inventory

## Overview

The inventory supports equipment tracking, infrastructure documentation, maintenance planning, system validation, and future hardware upgrades.

## Server Inventory

### Supermicro / Thinkmate Servers

**Quantity Acquired:** 4

**Reported Model:** Supermicro 218-18 / Thinkmate

**Reported Processor Configuration:** Dual Intel Xeon E5-2630 processors

**Chassis Form Factor:** Rackmount

**Intended Purpose:** Hosting the J.A.R.V.I.S. platform and supporting AI development infrastructure.

### Current Hardware Status

- Four Supermicro / Thinkmate servers have been acquired.
- Three working servers have been installed in the APC NetShelter rack.
- One server has been selected as the primary J.A.R.V.I.S. development host.
- The primary server has been successfully configured with Debian GNU/Linux 13.
- CPU, memory, and storage functionality have been checked.
- The primary server has passed its initial infrastructure validation.

## Primary J.A.R.V.I.S. Server

### System Identification

**Hostname:** Jarvis

**Operating System:** Debian GNU/Linux 13 (Trixie)

**Primary Function:** Hosting J.A.R.V.I.S. development services and local AI workloads.

**Operational Status:** Active

### Processor

**Reported Configuration:** Dual Intel Xeon E5-2630

**Status:** Operational

The processor configuration was checked during Phase 1, and no CPU-related issues were reported.

### Memory

**Reported Installed RAM:** 64 GB

**Memory Reported by Debian:** 62 GiB

**Available Memory During Health Check:** Approximately 61 GiB

**Configured Swap:** 48 GiB

**Status:** Operational

Memory functionality was verified during Phase 1. The initial system health check showed approximately 1.2 GiB of memory in use.

### Storage

**Primary Installed Drive:** 1 TB 2.5-inch SATA HDD

**Operating System Installation:** Debian GNU/Linux 13

**Root Filesystem:** `/dev/sda2`

**Root Filesystem Size:** 868 GB

**Used Space During Health Check:** Approximately 16 GB

**Available Space During Health Check:** Approximately 809 GB

**Root Filesystem Utilization:** 2%

**Status:** Operational

The primary server successfully boots directly from its internal storage without requiring the Debian installation USB.

The reported filesystem capacity reflects the configured root filesystem rather than the full advertised capacity of the physical drive.

### Networking and Remote Access

**Remote Access Methods:**
- Secure Shell (SSH)
- Tailscale private networking

**SSH Authentication:** Dedicated Ed25519 public-key authentication verified.

**Verified Services:**
- `ssh.service` — Active
- `tailscaled.service` — Active
- `systemd-timesyncd.service` — Active

The primary server successfully established internet connectivity and completed Tailscale authentication.

A dedicated SSH key was configured and successfully used for remote access.

Following a controlled server reboot, Tailscale and SSH connectivity were successfully restored and verified.

## Rack Infrastructure

### APC NetShelter Cabinet

**Manufacturer:** APC

**Model:** AR1000A NetShelter

**Purpose:** Housing the rack-mounted J.A.R.V.I.S. server infrastructure.

### Current Status

- The APC NetShelter cabinet has been acquired.
- Three working servers have been installed.
- Incorrectly installed rack rails were removed and replaced.
- Rack door-clearance issues were resolved by repositioning the mounting rails and reseating the servers.
- The primary server is operational.

Additional mounting information and rack configuration details will be maintained in `rack-setup.md`.

## Phase 1 — Infrastructure Validation

The primary J.A.R.V.I.S. server completed the following checks during Phase 1.

- [x] Install Debian GNU/Linux 13
- [x] Verify successful operating system installation
- [x] Confirm successful boot from internal storage
- [x] Verify CPU functionality
- [x] Verify memory functionality
- [x] Verify storage functionality
- [x] Confirm basic network connectivity
- [x] Install and configure Tailscale
- [x] Establish SSH connectivity
- [x] Verify public-key SSH authentication
- [x] Successfully reboot the server
- [x] Verify Tailscale connectivity after reboot
- [x] Verify SSH connectivity after reboot

### System Health

The system health check performed during Phase 1 reported:

| Component | Result |
|---|---|
| System uptime | 1 day, 1 hour, 1 minute |
| CPU load average | 0.00, 0.00, 0.00 |
| Total reported memory | 62 GiB |
| Available memory | 61 GiB |
| Root filesystem utilization | 2% |
| SSH service | Active |
| Tailscale service | Active |
| System time synchronization service | Active |
| NTP synchronization | Confirmed |
| Other failed services | None detected |
| NVIDIA Persistence Daemon | Failed — deferred |

## Planned Hardware Evaluation

Future hardware assessments may include:

- SSD upgrades and storage performance
- Backup storage and recovery hardware
- Power supply efficiency
- Cooling and airflow improvements
- Memory expansion
- GPU suitability for AI workloads
- Network infrastructure
- Replacement components and serviceability
- Long-term system reliability

## Inventory Maintenance

This document should be updated whenever:

- New equipment is acquired.
- Hardware specifications are verified.
- Components are replaced or upgraded.
- A server's operational status changes.
- Equipment is removed from service.
- Infrastructure configurations change substantially.

Sensitive information, including management credentials, private network addresses, and authentication keys, must not be published in this document.

---

**Project:** J.A.R.V.I.S.

**Documentation Phase:** Phase 1 — Server Infrastructure Setup

**Infrastructure Status:** Operational validation complete; documentation closure pending

**Last Updated:** November 21, 2026