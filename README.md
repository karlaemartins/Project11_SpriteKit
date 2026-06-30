# iOS Pachinko - Projeto de Estudo

Jogo desenvolvido em **SpriteKit** que explora conceitos fundamentais do desenvolvimento de jogos 2D, como física, colisões, animações, partículas e gerenciamento de cenas.

Este projeto faz parte do **Project 11** do curso **100 Days of Swift**, sendo desenvolvido com o objetivo de aprender os fundamentos do SpriteKit e compreender sua arquitetura e fluxo de trabalho.

## O que o app faz

- Simula um jogo de Pachinko utilizando física 2D
- Permite lançar bolas na tela
- Detecta colisões entre objetos
- Atualiza a pontuação conforme o resultado das jogadas
- Utiliza efeitos visuais com partículas

## Arquitetura

O projeto foi estruturado utilizando **SpriteKit**, explorando o gerenciamento de cenas, nós, física e animações para construção de jogos 2D.

## Decisões importantes

- Utilização de SpriteKit
- Gerenciamento da cena através de `SKScene`
- Objetos representados por `SKSpriteNode`
- Sistema de física utilizando `SKPhysicsBody`
- Detecção de colisões com `SKPhysicsContactDelegate`
- Efeitos visuais utilizando `SKEmitterNode`

## Melhorias em relação ao projeto original

Além da implementação principal, também foram realizados os desafios propostos pelo curso:

- Bolas criadas com cores aleatórias utilizando os assets do projeto
- Lançamento das bolas sempre próximo ao topo da tela, permitindo ao jogador escolher apenas a posição horizontal
- Implementação de um sistema de limite de bolas:
  - O jogador inicia com 5 bolas
  - Cada lançamento consome uma bola
  - Slots verdes concedem uma bola adicional
  - Slots vermelhos não devolvem bolas
  - Obstáculos são removidos quando atingidos pelas bolas

## Conceitos praticados

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

## Créditos

Projeto baseado no **Project 11**, do curso **100 Days of Swift**, criado por **Paul Hudson (Hacking with Swift)**.
