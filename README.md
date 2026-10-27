# POLVOLAND

Jogo de pesca e coleção de polvos para Roblox, criado e desenvolvido por **Arthur Novi** ([@tulhy](https://github.com/tulhy)).

### [Jogar POLVOLAND no Roblox](https://www.roblox.com/games/104189465030693/POLVOLAND)

## Sobre o jogo

Em POLVOLAND você lança a vara, acerta o minijogo de pesca no momento certo e vai completando uma coleção com mais de 90 espécies de polvos espalhadas por várias ilhas. Conforme avança, compra varas melhores, monta um aquário na sua própria ilha e viaja para regiões mais difíceis, até chegar ao Coração do Eclipse, no espaço, aonde só se chega de foguete.

- Mais de 15 varas, cada uma com visual e sorte próprios
- Ilhas com polvos exclusivos: Ilha dos Polvos, Ilha dos Cristais, Caverna das Profundezas, Templo das Águas Sagradas, Ilha do Eclipse, Ilha de Brinquedo, Ilha dos Doces e Coração do Eclipse
- Ciclo de dia e noite, com polvos raros que só aparecem à noite
- Aquário na ilha do jogador, que rende moedas com os polvos expostos
- Viagens de barco e de jet ski entre as ilhas
- Arena de combate com polvos, contra desafiantes do jogo ou contra outros jogadores
- Trocas de polvos e itens entre jogadores
- Tutorial em missões para quem está começando
- Recompensa diária, eventos como a Maré da Sorte e segredos escondidos pelo mapa

## Como foi feito

- **Linguagem:** Luau, com cerca de 50 scripts separados entre servidor, cliente e módulos compartilhados
- **Arquitetura:** o servidor é a autoridade sobre moedas, pescas, trocas e combate; o cliente cuida da interface e dos efeitos visuais
- **Dados:** progresso salvo com DataStore, com trava de sessão para evitar duplicação de itens nas trocas
- **Mapa:** as ilhas são geradas por código, o que permite uma versão leve do arquivo que monta o mapa ao iniciar
- **Testes:** simulações da lógica do servidor fora do Roblox, com APIs simuladas e relógio virtual
- **Publicação:** atualizações enviadas pela Open Cloud API do Roblox

O código-fonte fica em um repositório privado, porque o jogo está publicado e parte da lógica do servidor (como as proteções contra trapaça) não deve ser exposta.

## Autor

Arthur Novi, estudante de Engenharia da Computação na FIAP.
GitHub: [@tulhy](https://github.com/tulhy) · Roblox: @tulhy16
