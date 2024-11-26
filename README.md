# Estudo Comportamental da Vida Artificial

Este projeto apresenta uma simulação baseada no modelo de Lotka-Volterra para analisar o comportamento de presas e predadores em um ambiente virtual. Utilizando Python, o sistema simula interações entre plantas, coelhos e raposas, explorando diferentes estratégias de movimentação e dinâmica populacional.

## Introdução

A pesquisa visa identificar padrões comportamentais em indivíduos artificiais, com foco na dinâmica populacional e na estabilidade do sistema. O modelo matemático de Lotka-Volterra foi adaptado para simular um ecossistema simplificado, no qual:

- **Plantas** são geradas aleatoriamente ao longo do tempo.
- **Coelhos** consomem plantas para se reproduzir.
- **Raposas** predam coelhos para sobreviver e gerar filhotes.

A movimentação das espécies é implementada de duas maneiras:
1. **Aleatória**: Sem direcionamento específico.
2. **Orientada por percepção**: Estratégica, com base no ambiente ao redor.

## Objetivos

- Simular interações entre três espécies em diferentes cenários.
- Avaliar o impacto das estratégias de movimentação na dinâmica populacional.
- Explorar variações nos parâmetros do modelo para analisar estabilidade e equilíbrio.

## Como Rodar o Projeto

### Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina. As bibliotecas necessárias podem ser instaladas com o seguinte comando:

```bash
pip install pygame

