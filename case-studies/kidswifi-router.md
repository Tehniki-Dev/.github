# KidsWifi Router

## Project Type

Telegram-controlled edge and infrastructure control system for OpenWrt routers.

## System Scope

Telegram bot commands, n8n orchestration with structured AI parsing, MQTT contracts, a Python router agent, Supabase-backed state and logs, and firewall-level policy enforcement on the router.

## Technical Highlights

- Telegram -> n8n -> MQTT -> router agent -> firewall execution loop
- OpenAI structured output inside n8n for natural-language command parsing
- MQTT contract schemas with acknowledgement, status, stats, and health channels
- OpenWrt router agent with nftables primary path and iptables fallback
- usage limits, schedules, overrides, and exception handling in domain logic
- Supabase logging, router registry, usage history, and operational visibility
- CI gates, local E2E flow, deployment scripts, and router health checks

## Operational Value

This class of system proves we can connect Telegram UX, workflow orchestration, brokered messaging, infra-aware agents, and policy enforcement into one controlled operating product instead of stopping at a demo bot.

## Public Visibility

Public summary only. Detailed repository contents, deployment flow, and infrastructure specifics can be expanded selectively.
