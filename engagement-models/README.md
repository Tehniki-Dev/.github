# Engagement Models

Different systems need different entry paths.

We choose the engagement model based on product maturity, delivery risk, and how clear the current system actually is.

## Developer-First

Best when the backlog is already clear and the system can be extended safely.

Typical situations:

- the team already understands the current architecture
- the next implementation scope is well-defined
- the product needs strong execution without a separate diagnosis phase

What the client gets:

- direct execution
- focused implementation
- faster movement on clearly defined scope
- engineering support without unnecessary discovery overhead

## Architect-First

Best when the product direction is clear, but the system shape and next technical decisions are not.

Typical situations:

- the product is growing, but the architecture is starting to lag behind
- new features depend on decisions that should be made once, not improvised repeatedly
- the team needs technical direction before scaling delivery

What the client gets:

- architecture framing
- system boundaries
- clearer priorities
- a safer next-phase implementation path

## Audit-First

Best when the system is already fragile and direct implementation would create too much risk.

Typical situations:

- the backend became hard to change safely
- the product outgrew the first version
- instability, hidden dependencies, or unclear infrastructure make honest delivery impossible without diagnosis

What the client gets:

- technical assessment
- risk visibility
- problem framing
- a realistic first recovery or stabilization phase

## Long-Term Technical Partner

Best when the product is growing continuously and needs stable engineering involvement over time.

Typical situations:

- the system is already live and growing
- the team needs stable backend and architecture ownership over time
- the product cannot be handled well through disconnected one-off tasks

What the client gets:

- continuity
- stronger system ownership
- structured evolution instead of reactive patching

## Curated Delivery

This is not a separate project type.
It is a delivery leadership layer that can sit on top of implementation, phased delivery, or longer-term work when the client wants less management overhead and clearer control over scope, progress, and acceptance.

Typical situations:

- the client does not want to translate every request directly into engineering language
- scope can drift if clarifications are handled only in chat
- acceptance risk is high unless execution stays tied to agreed requirements

What the client gets:

- clearer request shaping before development starts
- visible progress through Kanban-style board tracking
- tighter execution control against agreed scope
- fewer disputes at delivery and handover

## How To Choose

- if scope is already clear -> `Developer-First`
- if technical direction is missing -> `Architect-First`
- if risk is high and the system state is unclear -> `Audit-First`
- if the product will evolve across multiple phases -> `Long-Term Technical Partner`
- if the client wants less coordination burden and clearer acceptance -> `Curated Delivery`

## Related Pages

- [Why TEHNIKI](../why-tehniki/README.md)
- [What We Do Not Do](../what-we-do-not-do/README.md)
- [How We Work](../how-we-work/README.md)
- [Who We Are For](../who-we-are-for/README.md)
- [Tenders and Enterprise Readiness](../tenders/README.md)
