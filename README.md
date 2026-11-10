# TG5 — Diagrama de Transição de Estado

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

## Diagrama entregue

| Visão escolhida | Classe (TG3) | Casos de uso | Arquivo |
|---|---|---|---|
| Ciclo de vida da Reserva | `Reserva` (atributo `status`) | UC04, UC05, UC06, UC09 | [diagrama-de-estado.md](diagrama-de-estado.md) |

O arquivo traz o diagrama, a lista de estados, a tabela de transições (evento, guarda e ação), a explicação e os pontos em aberto.

## Base utilizada

- **TG2** — especificação dos casos de uso (fluxos principais e alternativos)
- **TG3** — diagrama de classes de domínio (enum `StatusReserva`)
- **TG4** — diagramas de sequência (ciclo de vida da `PropostaReagendamento`)

## Como visualizar

O diagrama está em [Mermaid](https://mermaid.js.org/) dentro de um bloco de código, que o GitLab renderiza ao abrir o `.md`. Há também uma imagem pronta (`diagrama-de-estado.png`).
