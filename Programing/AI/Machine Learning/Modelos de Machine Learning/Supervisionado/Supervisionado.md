
> [!note] Se você conhecer os dados dá pra você ajudar a máquina no aprendizado supervisionado.

--- 
#### Nele você mostra pra máquina a conexão entre:

*as variáveis*  <-------------->  *os resultados conhecidos.*

--- 

  
No ML isso é chamado de Dados-amostrais-rotulados ou [[dados rotulados]] e saída correta.

São dados rotulados porque já estão etiquetados com informações de identificação.

> [!example] [[ex dados rotulados]]:
"Quanto tempo levará para chegar em casa?"
>
>Crie um conjunto de dados rotulados que incluam:
>- Condições climáticas 
>- Horários
>- Feriados
>
>Essas seriam as entradas
>A saída seria o tempo que levaria para voltar para casa em cada dia.
>
>Variáveis independentes: ***Entradas***
  Variáveis dependentes: ***Saída***


Poderia usar [[Regressão]] estatística e ver como as variáveis independentes afetam variável dependente.

--- 

> [!info] 
> Você sabe instintivamente que se estiver chovendo *(Variável independente de condição climática),* vai demorar mais tempo para voltar para casa, mas as máquinas dependem de dados e estatísticas.
> 
   Elas precisam analisar o tempo do trajeto e compara-lo aos dados rotulados das condições climáticas.

---
### Veremos como criar um modelo supervisionado de ML para este exemplo. 

O primeiro passo é criar um [[Conjunto de Treinamento]].
Com isso ela consegue criar uma relação direta entre a quantidade de chuva e o tempo de chegar em casa.

Logo quanto mais chove, mais demora. 

Também pode haver uma conexão entre o horário de saída do trabalho e a duração do trajeto. Quanto mais perto das 17h mais demora.
A máquina encontra alguns dos relacionamentos com os dados rotulados. 

Ele entende com isso que a chuva afeta a forma que as pessoas dirigem e que mais pessoas circulam em certos horários. Em seguida a máquina aplica esse conjunto de treinamento à um conjunto de teste dos seus dados.

Ela verifica se o conjunto de treinamento se mantem bom durante muito tempo. Quanto mais testes e 'feedback' ela tiver, mais precisa ficará. E você poderá fazer ajustes com base em novos dados. Parecido com o aprendizado humano.

Os dados rotulados são a principal diferença entre o aprendizado supervisionado e outros aprendizados de máquina

---
#machine-learning 