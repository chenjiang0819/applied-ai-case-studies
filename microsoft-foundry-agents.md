# Microsoft Foundry, Entra and Agent Integration

Orchestration validated; MCP and Agent Identity prototyped.

## Problem

An external application needed to invoke an orchestration agent through explicit identity and project-level authorization.

## My Role

I built and validated the orchestration integration and prototyped further identity and tool-integration paths.

## What I Built

A Microsoft Foundry orchestration agent invoked from an external Python application using Microsoft Entra service-principal authentication and project-level RBAC. I also prototyped Remote MCP and Agent Identity integration.

## Engineering Decisions

Used SDK/ARM inspection and identity-chain debugging to resolve authentication and authorization behavior across application and agent-platform integration.

## Outcome

The external Python-to-Foundry orchestration path was validated. Remote MCP and Agent Identity paths were explored through prototypes.
