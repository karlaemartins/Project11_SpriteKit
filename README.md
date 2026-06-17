# Project 11 – Pachinko (SpriteKit)

Projeto desenvolvido como parte do curso **100 Days of Swift**, de Paul Hudson (Hacking with Swift).

Este projeto marca a introdução ao **SpriteKit**, framework da Apple voltado para desenvolvimento de jogos 2D. Diferente dos projetos anteriores, que foram construídos utilizando UIKit, este projeto explora conceitos específicos de desenvolvimento de jogos, como física, colisões, animações, partículas e gerenciamento de cenas.

Este projeto foi desenvolvido como reprodução do conteúdo proposto no **Project 11** do curso, com o objetivo de aprender os fundamentos do SpriteKit e compreender sua arquitetura e fluxo de trabalho.

## Objetivos de Aprendizado

Durante o desenvolvimento deste projeto foram explorados os seguintes conceitos:

- SpriteKit
- SKScene
- SKNode
- SKSpriteNode
- SKLabelNode
- SKPhysicsBody
- SKPhysicsContactDelegate
- SKAction
- SKEmitterNode
- Sistema de colisões
- Física e gravidade
- Manipulação de toques
- Animações
- Sistema de pontuação
- Efeitos visuais com partículas

## Desafios Implementados

Além do conteúdo principal do projeto, também foram implementados os desafios propostos pelo curso:

### 1. Bolas Aleatórias

Cada bola é criada com uma cor aleatória entre os assets disponibilizados pelo projeto.

### 2. Lançamento pelo Topo

As bolas passam a ser criadas sempre próximas ao topo da tela, permitindo ao jogador escolher apenas a posição horizontal.

### 3. Limite de Bolas

Foi implementado um sistema de quantidade limitada de bolas:

- O jogador inicia com 5 bolas.
- Cada lançamento consome uma bola.
- Slots verdes concedem uma bola adicional.
- Slots vermelhos não devolvem bolas.
- Obstáculos são removidos quando atingidos pelas bolas.

## Tecnologias Utilizadas

- Swift
- SpriteKit
- Xcode

## Créditos

Projeto baseado no **Project 11 – Pachinko**, do curso **100 Days of Swift**, criado por Paul Hudson.
