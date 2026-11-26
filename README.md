
# Encaminhamento de Demandas — BPMN TO-BE

## Sobre o projeto

Este repositório reúne os artefatos referentes à modelagem do processo de negócio TO-BE de Encaminhamento de Demandas, desenvolvido no contexto de uma proposta de transformação digital dos processos da Prefeitura.

O objetivo é apresentar a modelagem do processo futuro, seus subprocessos e as alterações realizadas em relação ao processo AS-IS, considerando melhorias na eficiência, agilidade, efetividade e transparência do encaminhamento das demandas.

## 1. Processo de negócio TO-BE

O diagrama apresenta a modelagem consolidada do processo futuro, utilizando a notação BPMN (Business Process Model and Notation).

[Visualizar diagrama completo](./01-processo-principal/encaminhamento-tobe.svg)

![Processo de negócio TO-BE](./01-processo-principal/encaminhamento-tobe.svg)

## 2. TO-BE com destaque das alterações

Esta versão apresenta as alterações realizadas em relação ao processo AS-IS, utilizando cores para facilitar a identificação dos elementos novos, modificados, excluídos e preservados.

[Visualizar diagrama com alterações](./01-processo-principal/encaminhamento-tobe-alteracoes.svg)

![Processo TO-BE com destaque das alterações](./01-processo-principal/encaminhamento-tobe-alteracoes.svg)

### Legenda

| Cor | Classificação |
|---|---|
| 🟩 Verde | Elementos novos |
| 🟦 Azul | Elementos modificados |
| 🟥 Vermelho | Elementos excluídos |
| ⬜ Branco | Elementos preservados |

## 3. Subprocessos

Os subprocessos detalham as atividades representadas de forma recolhida no diagrama principal.

| Subprocesso | Diagrama |
|---|---|
| Consolidar e validar informações da demanda | [Visualizar](./02-subprocessos/01-consolidar-e-validar-informacoes.svg) |
| Definir encaminhamento | [Visualizar](./02-subprocessos/02-definir-encaminhamento.svg) |
| Reanalisar demanda devolvida | [Visualizar](./02-subprocessos/03-reanalisar-demanda-devolvida.svg) |
| Tratar falha de integração | [Visualizar](./02-subprocessos/04-tratar-falha-de-integracao.svg) |
| Validar demanda recebida | [Visualizar](./02-subprocessos/05-validar-demanda-recebida.svg) |

## 4. Principais alterações

As alterações realizadas na transição do AS-IS para o TO-BE concentram-se nos seguintes aspectos:

- Consolidação e validação das informações da demanda.
- Redistribuição das responsabilidades pelo levantamento complementar.
- Apoio especializado à definição do encaminhamento.
- Automatização do registro e roteamento das demandas.
- Automatização da atualização de status e disponibilização de informações ao cidadão.
- Padronização dos motivos de devolução.
- Reestruturação da reanálise das demandas devolvidas.
- Exclusão da raia Equipe de Análise, com redistribuição de suas responsabilidades no processo.

## 5. Documentação complementar

O documento de análise comparativa apresenta individualmente as alterações realizadas entre os processos AS-IS e TO-BE, incluindo a descrição das mudanças e os respectivos elementos BPMN.

[Consultar análise comparativa AS-IS e TO-BE (PDF)](./03-documentacao/analise-comparativa-as-is-to-be.pdf)

## 6. Resultados esperados

- Redução de encaminhamentos inadequados.
- Redução de devoluções e retrabalho.
- Maior padronização das informações.
- Maior integração e automação do processo.
- Aumento da rastreabilidade das demandas.
- Maior transparência para o cidadão.

## 7. Organização do repositório

| Diretório | Conteúdo |
|---|---|
| `01-processo-principal` | Diagramas BPMN TO-BE, com e sem destaque das alterações. |
| `02-subprocessos` | Diagramas de detalhamento dos subprocessos. |
| `03-documentacao` | Documento de análise comparativa entre AS-IS e TO-BE. |

---

Projeto acadêmico de modelagem de processos de negócio e transformação digital.
