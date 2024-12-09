# AITrabalho

Para este trabalho de AI decidi usar 3 tecnicas diferentes, a primeira é uma arvore de decisão que vai afetar o que o inimigo faz no seu turno,
implementado no trabalho que fiz para a cadeira de projeto, o jogo chama-se dungeon dwellers um card game inspirado em slay the spire, o jogo
tem varios tipos de inimigo e 3 dificuldades de inimigo, dependendo da dificuldade o inimigo tem acesso a diferentes ataques/habilidades que
são usadas dependendo do estado do jogo, tendo apenas uma ação por turno os inimgos podem escolher entre atacar, defender ou usar um debuff.

A outra implementação é uma state machine para animar as sprites dos inimigos nos devidos estados, apesar de ainda não estar 100% implementada
muitos inimigos tem estados diferentes dependendo do tipo.

Para ultima implementação decidi fazer uma AI simples de pathfinding, este fiz noutro projeto porque não era necessario no Dungeon Dwellers, 
para mostrar o pathfinding criei um player e um enimigo que o persegue evitando obstaculos, o player move-se com o butão direito do rato
e tambem tem aplicado o simples pathfinding para evitar ir contra objectos.
