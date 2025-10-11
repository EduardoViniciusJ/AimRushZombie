# AimRushZombie

**AimRushZombie** é um jogo 2D desenvolvido em **Python** utilizando a biblioteca **Pygame**.  
Este projeto foi criado como **trabalho acadêmico da disciplina de Linguagem de Programação Aplicada**.  
O jogo é uma demo com menu, personagens, inimigos e sistema de pontuação, seguindo boas práticas de programação orientada a objetos e **Design Patterns Factory e Mediator**.

---

## Tecnologias Utilizadas

- **Python**
- **Pygame**
- **Bibliotecas de som e imagens externas**

---

## Como Jogar

### Menu Principal
- Opção **Jogar** → Inicia o jogo.
- Opção **Sair** → Encerra o jogo.
- Som de fundo e imagem de fundo presentes.

### Jogo
- **HUD**
  - Contador de FPS
  - Contador de kills
  - Tempo
  - Música de fundo do jogo

#### Personagens

**Soldado (Jogador)**
- Movimentos:
  - `D` → andar para frente
  - `A` → andar para trás
  - `W` → pular
- `L` → atirar (máximo de 15 tiros; quando acabar, é necessário recarregar **1 segundo** antes de poder atirar novamente)
- Som de tiro
- Morre ao ser atingido por inimigos
- Exibe pontuação de kills na tela

**Inimigos (Zombies)**
- Movem-se sempre na direção do jogador
- Morrem quando atingidos por um tiro

---

## Funcionalidades

- Menu principal com som e imagem de fundo
- Jogabilidade com movimento e pulo
- Sistema de tiro com **limite de 15 balas e recarga de 1 segundo**
- HUD com informações
- Inimigos com comportamento básico (seguir jogador e morrer ao ser atingido)
- Contador de kills atualizado dinamicamente
- Uso de **Design Patterns**:
  - **Factory** → Criação de entidades (player, inimigos, backgrounds)
  - **Mediator** → Gerenciamento de colisões e contagem de kills
