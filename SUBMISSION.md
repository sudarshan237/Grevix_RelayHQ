# Grevix AfterCode — submission draft

## Project name
RelayHQ — Work stays in sync

## Description
RelayHQ is a lightweight task and deadline dashboard for small remote teams. It brings task ownership, a visual workflow board, deadline visibility, and a readable activity feed into one focused workspace. The goal is to reduce the everyday coordination overhead that comes from keeping work scattered across multiple apps.

## Problem
Small teams often lose time switching between chat, task lists, and status updates. Ownership becomes unclear, deadline risks surface too late, and important changes are difficult to follow.

## Solution
RelayHQ provides a single workspace with a three-stage task board, priority and owner labels, deadline radar for overdue and upcoming work, and an activity feed. Users can create tasks, search and filter the board, move tasks between statuses, complete work, and retain changes in the current browser. The interface is deliberately minimal and has no onboarding flow for this prototype.

## Demo
[Insert the verified live demo URL after deployment.]

## Public source code
[Insert the verified public GitHub repository URL after creating/publishing the repository.]

## Technologies and AI tools
HTML, CSS, vanilla JavaScript, browser localStorage, and AI-assisted development.

## Current scope and limitations
This is a functional frontend MVP, not a production multi-user service. Data is saved in the current browser only. Authentication, shared server-side storage, real-time syncing, and email/push notifications have not been implemented. Deadline visibility is in-app.

## Challenge Card #1 — The Shift
**Actual challenge card:** [Paste the exact requirement here.]  
**What changed:** [Describe what was changed, removed, or rebuilt.]  
**Evidence:** [Link to the feature/commit or name the screen where it works.]

## Challenge Card #2 — Pressure Test
**Actual challenge card:** [Paste the exact requirement here.]  
**What changed:** [Describe the second adaptation.]  
**Evidence:** [Link to the feature/commit or name the screen where it works.]

## Key product decisions
- Kept the application dependency-free so the prototype remains quick to open and easy to inspect.
- Chose in-browser persistence to make the core interactions usable without server credentials or setup.
- Prioritised the board, deadline visibility, and activity feed over peripheral features.
- Explicitly documented that cross-user sync and external notifications are not yet available instead of presenting mock functionality as production behaviour.
