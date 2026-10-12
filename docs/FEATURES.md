# Feature overview

This document explains TradeGuardian's product areas at a high level. It is not a release checklist or a claim that every capability is available in every version.

| Product area | Purpose |
| --- | --- |
| Rulebook and presets | Organize limits for evaluation, funded, and personal trading workflows. |
| Guardian | Bring the trader's chosen rules into decision checkpoints. |
| Risk Guardian | Support position-size, trade-frequency, and risk-boundary workflows. |
| Trading windows and instrument rules | Define when and what a trader intends to trade. |
| Rule locking | Support a commitment period for selected rules, subject to the deployed implementation. |
| Decision checkpoints | Encourage a pause and written reasoning before an action. |
| Journal and playbook | Organize trade notes, setups, and post-session reflection. |
| Analytics and performance review | Help examine trading outcomes alongside execution behavior. |
| AI coach and journal assistance | Support reflection and organization; suggestions require user judgment. |
| Alerts and violations | Highlight detected departures from configured rules when observable. |
| Achievements and progress | Recognize adherence based on the evidence the product can actually observe. |

## Example workflow

1. Define a trading plan and its boundaries.
2. Review the rules before a session.
3. Use supported checkpoints and alerts during decisions.
4. Record the trade and its context.
5. Review outcomes and rule adherence separately.

## Observation and enforcement

A browser workflow can only evaluate the information it can access. Broker-side execution, activity outside a supported surface, disconnected sessions, and missing data can limit coverage. Reliable enforcement claims require confirmation for the specific integration and deployed version.

A period without a detected violation does not by itself prove that every trade complied with the rules.

## Scope of this repository

No trading engine, broker connector, browser extension, backend service, database definition, or deployment instructions for the proprietary application are included. The live product is accessed through the TradeGuardian website.
