# TG6 — Diagramas de Atividades

**Disciplina:** Desenvolvimento de Sistemas I — Prof. Luiz Lozano

**Equipe:** Super

**Projeto:** Sistema de Reservas de Restaurantes (plataforma web)

## Integrantes

| Nome | RA |
|---|---|
| Carolina Mason | 10771365 |
| Dhara Dantas | 10780188 |
| Giovanna Cseri | 10771364 |
| Natalia Ramos | 10771391 |

## Diagramas entregues

| # | Caso de uso | Ator principal | Arquivo |
|---|---|---|---|
| 1 | UC04 — Reservar mesa | Cliente | [01-atividade-reservar-mesa.md](01-atividade-reservar-mesa.md) |
| 2 | UC09 — Gerenciar reservas recebidas | Gerente do Restaurante | [02-atividade-gerenciar-reservas-recebidas.md](02-atividade-gerenciar-reservas-recebidas.md) |
| 3 | UC10 — Aprovar cadastro de restaurante | Administrador da Plataforma | [03-atividade-aprovar-cadastro-restaurante.md](03-atividade-aprovar-cadastro-restaurante.md) |

Cada arquivo traz o contexto, as partições (raias), o diagrama em UML, a explicação e as decisões de modelagem e pontos em aberto.

## Base utilizada

- **TG2** — especificação dos casos de uso (fluxos principais e alternativos)
- **TG3** — diagrama de classes de domínio (status de `Reserva`, `Restaurante` e `PropostaReagendamento`)
- **TG4** — diagramas de sequência (mesmos casos de uso, em outra visão)
- **TG5** — diagrama de transição de estado da `Reserva`

## Notação

Os diagramas usam elementos da UML (nó inicial e final, ação, decisão, bifurcação/junção, partições e *call behavior*) desenhados em Mermaid, que o GitLab renderiza direto no `.md`. O Mermaid não tem raias nativas, então as partições aparecem como agrupamentos nomeados.
