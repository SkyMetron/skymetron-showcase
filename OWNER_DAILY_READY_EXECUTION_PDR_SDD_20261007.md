# PDR + SDD — skymetron-showcase

**Authority:** https://github.com/SkyMetron/SkyGerSDDProjects/blob/vnext5-w0-canonical-resync/OWNER_DAILY_READY_PDR_SDD_EXECUTION_MASTER_20261007.md
**Class:** PRESENTATION/HOLD
**Status:** draft specification only, no production feature created.

## PDR
Exibir status público de releases com evidência sem vazar detalhes internos, sem confundir roadmap com feature pronta.

## SDD / architectural role
Documento de product surface deve consumir somente versões/promotions aprovadas; separar Owner Daily Ready de SkyMetron 1.0; jamais publicar topologia privada, credenciais, hashes de path privados ou links para evidência secreta. Source of truth é releases e changelog aprovado.

## Multi-agent
Responsible AGENT-H; AGENT-G independent reviewer; AGENT-A contract alignment. No agent shares mutable worktree. Evidence pass only after actual tests.

## Exit condition
Página/README só anuncia versão com instalador e checksums reais; estado draft não é release; lint links e LGPD/security PASS.

## Test plan
Linkcheck, publication guard fixture, redaction test, a11y preview, non-release negative case.

## Operational rule
Do not merge/release/deploy/archive/scrub without separate Owner approval. This PR may be updated with verified work and audit evidence. Freeze unrelated product sources and preserve historical release/secret artifacts. Report HEAD, build/test/security outcomes, recovery and blockers.
