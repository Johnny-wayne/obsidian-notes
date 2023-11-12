
O Semi-supervisionado combina os dois outros aprendizados:

[[Supervisionado]] e [[Não supervisionado]]

Imagine que você que cria um programa que traduz mensagens de voz em texto
O não supervisionado não ajudaria muito.

Agruparia palavras, mas não saberia seu significado.
Talvez ela consiga agrupar a palavra 'foto' dita por alguem o problema é que como está agrupada e não classificado o programa não sabe que o som de foto é o mesmo que a palavra foto.

Por outro lado, o supervisionado não funcinaria, seria MUITO trabalhoso rotular todas os sons e palavras correspondentes ou criar um conjunto de treinamento para traduzir todas as palavras e frases.


É aí que entra o semi-supervisionado.

Tu cria um conjunto de treinamento menor com as palavras e frases mais comuns e frequentes e a máquina pode usa-lo para criar classificações básicas. Seria como um supervisionado, mas aqui ela usa o conjunto de treinamento e depois analisa o restante dos dados, assim ela expande o vocabulário com base no que havia classificado.

Como:

dado rotulado: som foto = palavra foto
Aí com os dados rotulados ela usa o raciocinio indutivo para expandir o vocabulário.
fotografia
fotógrafo
Fotocópia
Toperdo de fótons

e cria novas traduções apartir disso
ela terá os dados para foto e o som de foto

Se tiver certo ela agrupa essas palavras à foto ou algo do tipo.
O feedback normalmente vem de observadores humanos. Por isso quando se faz uma tradução, normalmente se vem um link perguntando:

"Como está essa tradução?"

Mas o aprendizado indutivo não é a unica forma dessa categoria, também existe o racíonicio translutivo/trandutivo algo assim.

Ele permite restringir os dados rotulados com base no que vc já sabe da coleção. Portanto se vc usar o raciocio trandutivo para trancrever mensagens de voz. Deve pensar em um contexto maior. 
Por exemplo as pessoas quando estão em mensagens de voz, usam mais substantivos:

- Pessoas
-Lugares
- Coisas
- Horários
- Datas

O raciocinio transdutivo aprimora o modelo fazendo melhores suposições sobre o que há nos dados não rotulados. 

O aprendizado semi-supervisionado não é tão usado mas funciona bem em alguns casos especificos.
Como:

- Quando não é dificil pra máquina criar grupos úteis
-  quando há muitos dados

Classificar páginas da web ou agrupar insetos.

Só funciona quando nenhum dos outros dois funciona.

O raciocínio indutivo e o transdutivo podem levar a maiores erros (sim é assim que escreve).
Solução para problemas especificos

---
#machine-learning 