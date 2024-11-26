# Estudo Comportamental da Vida Artificial

  Este projeto apresenta uma simulação baseada no modelo de Lotka-Volterra para analisar o comportamento de presas e predadores em um ambiente virtual. Desenvolvido em Python, o sistema simula as interações entre três espécies principais: plantas, coelhos e raposas, permitindo a exploração de diferentes estratégias de movimentação e dinâmicas populacionais.

Site para a simulaçao: https://estebanmap.github.io/SiteCIC/

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

### Como Rodar o Projeto em seu Repositório
# Pré-requisitos
Certifique-se de ter o Python e Git instalados em sua máquina.
Python: https://www.python.org/
Git: https://git-scm.com/

Insira os seguintes codigos, dessa sessão e posterior, no terminal de sua maquina:
Insira os seguintes codigos, dessa sessão e posterior, no terminal de sua maquina:
```bash
pip install notebook
````
```bash
pip install pygame
````

## Passo a Passo para Rodar a Simulação
1. Clone o repositório do projeto:
```bash
git clone https://github.com/EstebanMAP/Estudo-comportamental-da-vida-artificial
```
2. Navegue até o diretório do projeto:
Para simulaçao com movimento aleatorio:
```bash
cd Estudo-comportamental-da-vida-artificial/Random/
```
Para simulaçao com movimento orientada por percepção:
```bash
cd Estudo-comportamental-da-vida-artificial/Perception
```

3. Abra o Jupyter Notebook
Para simulaçao com movimento aleatorio:
```bash
jupyter notebook PrayPredatorRandom.ipynb
```
Para simulaçao com movimento orientado por percepção:
```bash
jupyter notebook PrayPredatorBasedInRules.ipynb
```

4. Execute a célula do notebook para iniciar a simulação.

