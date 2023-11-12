### Tipos
- [[Q-learning]]

--- 
> [!tip] Ele é diferente dos aprendizados [[Supervisionado]], [[Não supervisionado]] e [[Semi-supervisionado]]

No aprendizado por reforço a máquina itera para melhorar continuamente o resultado. Com o tempo, a máquina deve se concentrar como um míssil teleguiado na busca de saídas de alta qualidade. O aprendizado por reforço é muito aberto.

--- 

Ele reforça o comportamento desejado para a máquina. ==Em vez de deixar tudo aberto para estudo e observação, você define um objetivo claro para a máquina. ==

Exemplo
Veja desta forma: quando eu era jovem, havia um jogo de videogame simples chamado Pong. O jogo tinha duas barras em lados opostos da tela, que deslizavam para cima e para baixo para tentarmos acertar a bola de cada lado. Em 2013, o projeto Deep Mind do Google fez um experimento com o Pong para ensinar um computador a jogá-lo.

Criaram várias recompensas para o computador. Toda vez que ele acertava a bola com a raquete, recebia uma recompensa. Toda vez que o adversário errava a bola, recebia outra recompensa. Depois, jogou contra si mesmo e tentou obter o máximo de recompensas. Em pouco tempo o computador dominou o jogo e começou a derrotar jogadores humanos. 

A equipe Deep Mind usou algo chamado [[Q-learning]]. O Q-learning ajudou em alguns dos jogos mais complicados que precisavam de recompensas mais sofisticadas. 

 O aprendizado por reforço é uma das áreas mais promissoras do aprendizado de máquina. A máquina passa por inúmeras simulações de ações e estados até encontrar a melhor estratégia. Em 2015, o projeto Deep Mind foi notícia quando seu programa AlphaGo venceu um jogador especialista no jogo chamado Go. O AlphaGo usou aprendizado não supervisionado. Aprendeu observando profissionais jogando Go. O novo programa AlphaGo Zero se baseia em Q-learning. Não precisa assistir aos especialistas jogando. O AlphaGo Zero analisou o jogo e tentou várias ações para mudar o estado e vencer. Em poucas horas, essa máquina de Q-learning jogou Go em um nível que os humanos não conseguem entender. Após apenas 70 horas de treinamento, o AlphaGo Zero venceu a versão anterior do AlphaGo nas primeiras 100 tentativas. O aprendizado por reforço e especificamente o Q-learning permitem que as máquinas avancem rapidamente além do nosso entendimento. Isso pode ajudar a pular as etapas requeridas pelo aprendizado não supervisionado. Não são necessárias horas observando e estudando grandes quantidades de dados.
 
---
#machine-learning 