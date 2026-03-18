Paleta de cores:
--sandy-brown: #fa9f42ff;
--muted-teal: #94a89aff;
--pine-teal: #294936ff;
--prussian-blue: #0d2149ff;
--dark-wine: #721817ff;

## Regras de negócio do jogo
- Página inicial ( ou modal) pedindo nomes dos dois players, a quantidade de cartas e se os dinos serão aleatórios ou os mais famosos;
- A tela do jogo tem o espaço para uma carta de cada player, o nome de cada um e o número de cartas que cada um tem no momento;
- O jogo indica de quem é a vez de jogar e mostra a carta desse player, a outra carta fica como se estivesse virada para baixo, sem mostrar dino ou atributos.
- O player da vez escolhe um atributo e clica nesse atributo para desafiar o outro player, nesse momento a carta do outro é revelada e o game diz quem ganhou a mão;
- Quem ganha a mão fica com essas duas cartas e elas vão para o final do baralho do player;
- em caso de empate, as cartas ficam na mesa e o jogador da vez escolhe um atributo da próxima carta;
- Quando um jogador perder todas as suas cartas, o outro ganhou o jogo.

Crie um frontend vanilla para rodar esse jogo de trunfo, pegando as cartas com get em:
- http://localhost:3000/dinos/top/fama/:n para jogar com os dinos mais famosos ou
- http://localhost:3000/dinos/random/:n se escolher jogar com os aleatórios