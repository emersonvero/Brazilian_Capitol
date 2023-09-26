# Brazilian_Capitol
This is a Network Science project analysing the twitter network of criminals that invaded Brazilian`s National Government Palace, on Jan 8th 2023.

The Brazilian_Capitol_A_Network_of_Criminals.pdf file contains a paper that discusses the proposal and the development of the project.
There is also a file with a slides presentation for the project.

The followers_data folder contains the dataset collected for the project, each excel file contains the list of followers of one of the users that were present in the breakthrough of Brazilian pallace.


Introduction


housands of far right organized rioters broke into Brazilian Government building on January 8, in
a similar fashion to the Capitol episode in the United States two years ago. These people claim that
the elections won by Lula (current president) against Jair Bolsonaro (former president) were somehow
a fraud. They explicitly ask the army to implement a military dictatorship, invoking the darkest
period of Brazilian recent story, that begun in 1964’s coup d’etat and lasted 24 years, marked by
the imprisonment, torture and death of thousands of activists, repression to any kind of worker’s or
student’s political organization or even to any kind of art manifestation that could slightly sound as a
challenge to ”good manners” and the ”christian Brazilian traditional family.” [1]
Since 1989, Brazilian government regime is a regular presidential parliamentarism that theoretically
guarantees the right to protest but also formally criminalizes open attacks to democracy and to the
regime itself [2]. It is also a crime to attack State public property.[2] This is enough to state that
the people who participated in the attack in Brasilia are indeed criminals that deserve some kind of
punishment, even though the State is quite lenient towards far-right criminal attacks in general.
So little was the fear of punishment, that during the episode, the invaders made tweets providing
the proofs of their own participation. Not only that, over the whole country in the biggest cities, during
two months, people set camp in front of Brazilian Army facilities in preparation for the tentative of
coup d‘etat about to come. This people ultimately form together a social network that is the study
object of this work.
One is able to query tweets based on the geographic coordinates of the building and the exact time
that the invasion happened, and also query based on the coordinates of the camps, and with a span
of time corresponding to their duration.
The idea is to analyse the network of people who actively participated on the event, the nodes
being a twitter user, and the links being their followers. This way, centrality measures can be applied
to reach a conclusion on who are the most influential users, who are the ones responsible for spreading
information the most, etc.



/////


Milhares de manifestantes de extrema-direita organizados invadiram o palacio do Planalto em 8 de janeiro, de maneira semelhante ao episódio do Capitólio dos Estados Unidos dois anos atrás. Essas pessoas alegam que as eleições vencidas por Lula (atual presidente) contra Jair Bolsonaro (ex-presidente) de alguma forma foram fraudadas Elas pediam explicitamente ao exército que implementasse uma ditadura militar, evocando o período mais sombrio da história recente do Brasil, que começou com o golpe de estado de 1964 e durou 24 anos, marcado pela prisão, tortura e morte de milhares de ativistas, repressão a qualquer tipo de organização política de trabalhadores ou estudantes, ou mesmo a qualquer manifestação artística que pudesse parecer um desafio à "boa conduta" e à "tradicional família brasileira cristã". [1]

Desde 1989, o regime de governo brasileiro é um parlamentarismo presidencial regular que teoricamente garante o direito de protesto, mas também criminaliza formalmente ataques abertos à democracia e ao próprio regime [2]. Também é crime atacar propriedade pública do Estado.[2] Isso é o suficiente para afirmar que as pessoas que participaram do ataque em Brasília são, de fato, criminosas que merecem algum tipo de punição, mesmo que o Estado seja bastante leniente com ataques criminosos de extrema-direita em geral.

Tão pequeno era o temor de punição que, durante o episódio, os invasores fizeram tweets fornecendo provas de sua própria participação. Além disso, em todo o país, nas maiores cidades, durante dois meses, as pessoas acamparam em frente às instalações do Exército Brasileiro em preparação para a tentativa de golpe iminente. Essas pessoas acabaram formando uma rede social que é objeto de estudo deste trabalho.

É possível consultar tweets com base nas coordenadas geográficas do prédio e no momento exato da invasão, bem como consultar com base nas coordenadas dos acampamentos e com um intervalo de tempo correspondente à sua duração.

A ideia é analisar a rede de pessoas que participaram ativamente do evento, sendo os nós um usuário do Twitter e os links sendo seus seguidores. Dessa forma, medidas de centralidade podem ser aplicadas para chegar a uma conclusão sobre quem são os usuários mais influentes, quem são os responsáveis por disseminar informações com mais intensidade, etc.

