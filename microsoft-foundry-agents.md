# Microsoft Foundry Agent Integration

Status: **Orchestration agent validated; identity/MCP integrations prototyped**.

## Problem
Connect an external application to an agent platform with explicit identity and authorization boundaries.

## My Role
I built and validated an orchestration agent and debugged integration behavior.

## What I Built
A Microsoft Foundry orchestration agent invoked from an external Python application using Microsoft Entra service-principal authentication and project-level RBAC. Remote MCP and Agent Identity integration were prototyped.

## Technical Decisions
Used SDK/ARM inspection and identity-chain debugging to understand integration boundaries. No private tenant, principal, policy or endpoint information is disclosed.

## Outcome
The orchestration integration was built and validated. Remote MCP and Agent Identity work remains described as prototyping; this is not a claim of production deployment for every integration.

## Constraints and Responsible Deployment
No tenant IDs, credentials, policy documents, private tool schemas or internal traces are included.

## Public Disclosure Note
Personal technical narrative by Chen Jiang; not an official employer repository or institutional endorsement. Facts are bounded by [Chen Jiang’s public LinkedIn profile](https://www.linkedin.com/in/chenjiangprofile), as represented by the owner-supplied Profile.pdf export reviewed on 14 October 2026. The export is a user-provided public factual baseline, not independently verified deployment evidence. No employer source, internal configuration, credentials or confidential material is distributed.
