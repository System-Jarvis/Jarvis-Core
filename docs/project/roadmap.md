# J.A.R.V.I.S. — Development Roadmap

## Project Definition

**A self-hosted artificial intelligence platform.**

## Roadmap Purpose

This document tracks the phases, objectives, milestones, and progress of the J.A.R.V.I.S. project.

---

## Phase 0 — Base Documentation

**Status:** Complete

**Completed:** November 19, 2026

### Objectives

Establish a consistent documentation foundation for the J.A.R.V.I.S. project.

### Milestones

- [x] Establish the System-Jarvis GitHub organization
- [x] Create the Jarvis-Core repository
- [x] Create the Jarvis-Terminal repository
- [x] Establish the six original planned agents and their responsibilities
- [x] Create the initial Jarvis-Core README
- [x] Create the Project Overview
- [x] Establish the Development Roadmap
- [x] Create the Agent Network documentation
- [x] Document the existing hardware and infrastructure
- [x] Establish development documentation standards
- [x] Complete the foundational documentation audit
- [x] Merge the final Phase 0 documentation
- [x] Align the GitHub organization roadmap with the approved development phases

---

## Phase 1 — Server Infrastructure Setup

**Status:** Complete

### Objectives

Prepare the physical and software infrastructure required to host J.A.R.V.I.S.

### Milestones

- [x] Acquire four Supermicro / Thinkmate servers
- [x] Acquire the APC NetShelter AR1000A cabinet
- [x] Install three working servers in the rack
- [x] Power on the primary server
- [x] Resolve rack mounting and door-clearance issues
- [x] Install a 1 TB 2.5-inch SATA HDD in the primary server
- [x] Install Debian GNU/Linux 13 (Trixie)
- [x] Complete initial server configuration
- [x] Verify network connectivity
- [x] Configure and verify SSH public-key authentication
- [x] Install and configure Tailscale
- [x] Verify successful reboot and remote reconnection
- [x] Verify CPU, memory, and storage functionality
- [x] Verify essential system services
- [x] Confirm network time synchronization
- [x] Document the primary server's confirmed hardware and software configuration
- [x] Validate the hosting environment for initial development workloads

### Final Validation

The primary J.A.R.V.I.S. server successfully completed initial hardware, software, networking, and system-health verification.

SSH and Tailscale were confirmed operational following a server reboot.

### Documentation Closure

- [x] Complete primary server operational validation
- [x] Prepare updated hardware inventory
- [x] Prepare updated development progress log
- [x] Prepare updated development roadmap
- [ ] Review and commit final Phase 1 documentation
- [ ] Merge the Phase 1 finalization pull request
- [ ] Formally record Phase 1 as complete

---

## Phase 1.5 — Future Feature Planning and Documentation

**Status:** Planned

### Objectives

Research, document, evaluate, and organize possible future J.A.R.V.I.S. capabilities without interrupting active development.

---

## Phase 2 — Core AI Development

**Status:** Complete

**Primary Workstream:** JarvisV1 Development and Environment Configuration

### Objectives

Develop the first functional J.A.R.V.I.S. artificial intelligence prototype using a self-hosted language model, conversational WebUI, and foundational system integration capabilities.

Establish a functional AI environment that can be expanded during future development phases.

### Completed Milestones

- [x] Install and configure Ollama on the primary J.A.R.V.I.S. server.
- [x] Test initial local language models.
- [x] Evaluate preliminary inference performance.
- [x] Select `llama3.1:8b` as the JarvisV1 model.
- [x] Establish the initial J.A.R.V.I.S. identity.
- [x] Create and merge the official V1 system prompt.
- [x] Integrate the V1 system prompt into the running application.
- [x] Perform initial identity and behavior testing.
- [x] Install and configure Chainlit.
- [x] Establish a functional conversational WebUI.
- [x] Connect Chainlit to Ollama.
- [x] Enable remote WebUI access through Tailscale.
- [x] Implement initial interface customization and branding.
- [x] Document WebUI activation and access procedures.
- [x] Integrate live system information into JarvisV1.
- [x] Implement read-only hardware diagnostic reporting.
- [x] Verify access to CPU and memory utilization.
- [x] Verify storage and uptime reporting.
- [x] Verify CPU temperature reporting.
- [x] Implement structured system health reports.
- [x] Verify that Ollama runs as an active system service.
- [x] Verify that Chainlit operates successfully.
- [x] Confirm that the running Chainlit process survives an SSH disconnection.
- [x] Verify the initial JarvisV1 system prompt behavior.
- [x] Conduct preliminary technical assistance testing.

### Documentation

- [x] Create and merge the JarvisV1 system prompt documentation.
- [x] Create and merge the Chainlit WebUI activation guide.
- [x] Record initial model testing and development progress.
- [ ] Finalize Phase 2 documentation and merge the finalization pull request.

### Phase 2 Outcome

JarvisV1 successfully operates as a self-hosted artificial intelligence prototype using Ollama, Llama 3.1 8B, and the Chainlit conversational interface.

The prototype demonstrates its configured J.A.R.V.I.S. identity, responds to operator requests, and provides access to live server diagnostics.

## Future Development Phases

Implement specialized members of the J.A.R.V.I.S. Agent
Network, establish agent responsibilities, and develop
communication and coordination between agents.

Phase 3 will also introduce Rust development, including
the foundational architecture and implementation work
required for the next generation of J.A.R.V.I.S.

### Phase 4 — Interface Development

**Status:** Planned

Develop terminal and desktop interfaces for interacting with J.A.R.V.I.S., including the planned Linux-first, cross-platform interface architecture.

### Phase 5 — Integration and Expansion

**Status:** Planned

Explore advanced integrations, automation, monitoring, device control, and additional J.A.R.V.I.S. capabilities.

Features documented during Phase 1.5 may be assigned to these phases based on requirements, dependencies, and implementation readiness.

---

## Roadmap Maintenance

This roadmap should be updated when:

- A development phase is completed.
- A major milestone is achieved.
- New project requirements are approved.
- Technical dependencies change.
- A future feature is approved for implementation.
- The development team revises priorities.

Detailed implementation activities should be recorded in the Development Progress Log and relevant technical documentation.

---

**Project:** J.A.R.V.I.S.

**Last Updated:** November 22, 2026

**Current Development Phase:** Phase 2 — Core AI Development