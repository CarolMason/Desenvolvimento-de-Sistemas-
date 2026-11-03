# TG4 — Diagramas de Sequência

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

| # | Diagrama | Caso de uso | Ator principal | Arquivo |
|---|---|---|---|---|
| 1 | Reservar mesa | UC04 | Cliente | [01-reservar-mesa.md](diagramas-de-sequencia/01-reservar-mesa.md) |
| 2 | Gerenciar reservas recebidas | UC09 | Gerente do Restaurante | [02-gerenciar-reservas-recebidas.md](diagramas-de-sequencia/02-gerenciar-reservas-recebidas.md) |
| 3 | Aprovar cadastro de restaurante | UC10 | Administrador da Plataforma | [03-aprovar-cadastro-restaurante.md](diagramas-de-sequencia/03-aprovar-cadastro-restaurante.md) |

Os três fluxos foram escolhidos por cobrirem os três perfis de usuário do sistema e por se conectarem: o cliente cria a reserva (UC04), o gerente decide sobre ela (UC09) e o administrador libera o restaurante que passa a recebê-las (UC10).

## Base utilizada

Os diagramas partem dos entregáveis anteriores:

- **TG1** — contexto e diagrama de casos de uso
- **TG2** — especificação dos casos de uso (fluxos principais e alternativos)
- **TG3** — diagrama de classes de domínio (nomes de classes, atributos, enumerações de status)

Cada linha de vida representa um objeto anônimo da classe indicada. Os objetos de domínio usam as classes do TG3 (`Restaurante`, `Mesa`, `Reserva`, `PropostaReagendamento`). Além delas, cada diagrama usa três elementos que não são classes de domínio: `Interface` (tela), `Sistema` (controlador) e `ServicoNotificacao`.

## Legenda da notação (UML)

| Elemento | Significado |
|---|---|
| Boneco | Ator |
| Retângulo no topo (nome da classe) | Linha de vida de um objeto |
| Seta contínua com ponta cheia | Mensagem síncrona |
| Seta tracejada | Retorno |
| Seta contínua com ponta aberta | Mensagem assíncrona |
| Barra sobre a linha de vida | Ativação (objeto em execução) |
| `alt` / `else` | Alternativas excludentes |
| `opt` | Trecho opcional |
| `loop` | Repetição |
| `«create»` | Criação de objeto |
| `ref` (nota) | Referência a outro caso de uso |

