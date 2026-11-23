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

**Status:** In Progress

**Initial Workstream:** JarvisV1 Development and Environment Configuration

### Objectives

Develop an initial functional JarvisV1 prototype and establish the basis for future AI architecture.

### Completed Milestones

- [x] Install Ollama on the primary server
- [x] Run an initial local language model
- [x] Complete preliminary inference testing with `llama3.2`
- [x] Select `llama3:8b` for continued evaluation
- [x] Begin establishing the JarvisV1 identity

### In Progress

- WebUI development and experimentation
- Local model evaluation
- Research into GPU and SSD upgrades
- Initial environment configuration for JarvisV1

### Remaining Milestones

- [ ] Develop a usable WebUI for interacting with Jarvis
- [ ] Create and document the first official JarvisV1 prototype
- [ ] Evaluate model quality, performance, and resource requirements
- [ ] Document model configuration and identity
- [ ] Define the foundational Core AI architecture

---

## Future Development Phases

### Phase 3 — Agent Network Development

**Status:** Planned

Implement specialized members of the J.A.R.V.I.S. Agent Network, establish agent responsibilities, and explore communication and coordination between agents.

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