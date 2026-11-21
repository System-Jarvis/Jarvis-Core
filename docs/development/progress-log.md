
# J.A.R.V.I.S. — Development Progress Log

## Overview

This document records significant development activities, completed milestones, ongoing work, and known issues throughout the J.A.R.V.I.S. project.

## Current Project Status

**Phase 0:** Base Documentation — Complete

**Phase 1:** Server Infrastructure Setup — In Progress

## Phase 0 — Base Documentation

**Status:** Complete

### Phase 0 Completion — November 19, 2026

The foundational J.A.R.V.I.S. Core documentation has been created, reviewed, and merged.

### Completed Work

- [x] Established the System-Jarvis GitHub organization
- [x] Created the Jarvis-Core and Jarvis-Terminal repositories
- [x] Established the official J.A.R.V.I.S. project definition
- [x] Defined the six original J.A.R.V.I.S. Agent Network members
- [x] Updated the Jarvis-Core README
- [x] Created the Project Overview
- [x] Established the Development Roadmap
- [x] Created the Agent Network Overview
- [x] Created and reviewed all six original agent profiles
- [x] Created the Hardware Inventory
- [x] Created the Rack Setup documentation
- [x] Established the Development Standards
- [x] Created the Development Progress Log
- [x] Established the Technical Decision records
- [x] Completed the foundational documentation audit
- [x] Verified the required files and pull request merges
- [x] Updated the Development Roadmap to reflect Phase 0 completion


### Follow-Up Documentation

- [ ] Reconcile the System-Jarvis organization roadmap with the approved Jarvis-Core phase definitions.

## Phase 1 — Server Infrastructure Setup

### Completed Work

- [x] Acquired four Supermicro / Thinkmate servers
- [x] Acquired the APC NetShelter AR1000A cabinet
- [x] Installed three working servers in the rack
- [x] Successfully powered on the primary J.A.R.V.I.S. server
- [x] Replaced incorrectly installed rack rails
- [x] Resolved rack door clearance issues by repositioning the rack rails and reseating the servers
- [x] Complete initial server configuration
- [x] Verify network connectivity
- [x] Configure and verify remote management access
- [x] Record final server hardware specifications
- [x] Validate the hosting environment

## Phase 2 - Development of JarvisV1 and Environment Configuration 

### Completed Work
- [x] Download Ollama to run models on server
- [x] Test multiple models to find optimal one
- [x] Choose final model
- [x] Add Jarvis identity

### Current Activities

- Creating WebUI environment
- Becoming familiar with WebUI
- Research GPU and SSD upgrades

### Remaining Milestones
- [ ] Create WebUI for connecting to and speaking to Jarvis
- [ ] Create Official JarvisV1 model
- [ ] Reformat this documentation
- [ ] Begin learning Rust code

## Known Issues and Blockers

### Initial Server Access

Remote access to the primary J.A.R.V.I.S. server has not yet been verified.

Related GitHub Issue: [#1 — Accessing the JARVIS Server for Initial Connection](https://github.com/System-Jarvis/Jarvis-Core/issues/1)

**Status:** Open — Phase 2

---

**Project:** J.A.R.V.I.S.

**Documentation Phase:** Phase 0 — Base Documentation

**Infrastructure Phase:** Phase 1 — Server Infrastructure Setup

**First Established AI:** Phase 2 -



# Notes Which need to be reformatted 11/21//2026

### Installed Ollama to run first generation of AI models
sudo curl -fsSL https://ollama.com/install.sh | sh 
ollama --version #Version 0.40.16

### Test first models
ollama run llama3.2
ollama run llama3.2 "Who is JARVIS from the MCU?"

### Notes 
Jarvis ran a 3B model by default and generated tokens incredibly quickly. Once the model loads in, within like 3-5 seconds, it generates text at a rapid pace. Because the model was small, it wasn't always perfect, however it was a competent and real response very rapidly. This gives a good sign for the future.

It was opted to use a larger model going forward, so the model from here on out will be `llama3:8b`
