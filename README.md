# Drone Telemetry & Flight Log Platform

Proof-of-concept project for collecting, storing and analyzing UAV flight usage and telemetry-related data.

The goal of this repository is to evaluate integration patterns for edge/IoT devices, including drone flight sessions, telemetry events, battery usage, media metadata and future cloud processing.

## Technical context

This project is related to software development activities in the area of:

- edge device integrations
- IoT telemetry ingestion
- REST API design
- event-driven architecture
- flight session logging
- media metadata processing
- future image/video analysis workflows

The reference hardware used for validation is a DJI Mini 5 Pro drone.

## Scope

Current MVP scope:

- manual flight session logging
- telemetry event schema design
- API contract definition
- mock event collector
- future-ready architecture for cloud ingestion

Out of scope for MVP:

- autonomous drone control
- real-time SDK integration
- BVLOS operations
- production flight automation

## Architecture
<img width="2409" height="356" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/15bc6e69-d291-4af6-a97b-879c3da6810e" />
