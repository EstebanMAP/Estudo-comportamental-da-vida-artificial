# Estudo Comportamental da Vida Artificial

Este projeto apresenta uma simulação baseada no modelo de Lotka-Volterra para analisar o comportamento de presas e predadores em um ambiente virtual. Desenvolvido em Python, o sistema simula as interações entre três espécies principais: plantas, coelhos e raposas, permitindo a exploração de diferentes estratégias de movimentação e dinâmicas populacionais.

No ecossistema virtual, as espécies desempenham os seguintes papéis:
- **Plantas**: Geradas aleatoriamente ao longo do tempo.
- **Coelhos**: Consomem plantas para se reproduzir.
- **Raposas**: Predam coelhos para sobreviver e gerar novos indivíduos

A movimentação das espécies é implementada de duas maneiras:
1. **Aleatória**: Movimentação sem direcionamento específico, permitindo observar a dinâmica sem influências externas.
2. **Orientada por percepção**: Estratégia onde cada espécie toma decisões com base no ambiente ao redor, priorizando recursos ou evitando ameaças.

## Objetivos

- Simular interações entre três espécies em diferentes cenários.
- Avaliar o impacto das estratégias de movimentação na dinâmica populacional.
- Explorar variações nos parâmetros do modelo para analisar estabilidade e equilíbrio.

## Como Rodar o Projeto

### Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina. As bibliotecas necessárias podem ser instaladas com o seguinte comando:

```bash
pip install pygame

