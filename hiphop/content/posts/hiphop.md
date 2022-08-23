---
title: "Hip-Hop e Rap: Uma análise sobre a evolução das letras"
date: 2022-07-15T17:12:33-03:00

---

# Introdução
Durante toda a história da humanidade, os seres humanos sempre buscaram diversas maneiras de se comunicar e aos poucos, através das emergentes necessidades, tentavam indicar, sonorizar e expressar o que era possível ver, sentir e até mesmo pensar. No decorrer do tempo, foi se desenvolvendo um sistema de comunicação mediante a criação das primeiras palavras, unindo-as para gerar as primeiras frases e consequentemente, consolidar um sistema mais complexo que hoje é conhecido por linguagem. Através de diferentes tipos de linguagens, a arte pode ser definida como um conjunto de técnicas e habilidades que produzem algum tipo de representação humana, destinada a comunicar e expressar tudo o que permeia seu ambiente.

Em cada época da história, a arte foi influenciada pelos contextos sociais, culturais e econômicos na qual estava inserida, se tornando um importante instrumento de construção da sociedade. Uma das formas de comunicação mais importantes criadas como arte é a música, sendo esta, uma técnica de expressão caracterizada pela sucessão estruturada de sons e ritmos e no contexto da humanidade possui uma grande função social. Através dela nós conseguimos refletir os sentimentos, a cultura e as diversas visões sobre o mundo. Sua evolução permitiu que diferentes combinações de melodias fossem criadas e aos poucos os gêneros musicais foram surgindo. Entre eles, no final do século XX, surgiu o *rap*. 

Rap é um acrônimo para *rhythm and poetry* (ritmo e poesia) que define bem o estilo das músicas do gênero. Acompanhadas por batidas rápidas e alguns efeitos sonoros, as letras das músicas são estruturadas em forma de discurso, tendo como característica uma presença muito forte de rimas e figuras de linguagem, tais como, metáforas, comparações, duplo sentido, jogo de palavras, entre outros. Esse ritmo nasceu na Jamaica nos anos 1960 e foi difundido dentro das comunidades afrodescendentes dos Estados Unidos no início da década de 1970. De lá para cá, esse gênero musical começou a ganhar maiores proporções em todo o mundo, influenciando grande parte da população mundial em diversos âmbitos, como na moda, cinema e estilo de vida.

Considerando a influência da cultura hip-hop e do próprio rap na sociedade atual, surgiu a ideia de realizar uma análise evolutiva sobre as composições artísticas do gênero, buscando compreender melhor quais são as temáticas mais abordadas, como é possível caracterizar as gerações de artistas, quais são os sentimentos predominantes entre as letras das músicas, entre outros aspectos menos óbvios.

Diante disso, esse trabalho utilizou técnicas de coleta de dados para gerar uma base com as letras das músicas de rap de alguns dos artistas mais renomados de cada época, começando do início da sua popularização e indo até os dias atuais, e mediante isso, aplicou conceitos e técnicas de análises textuais para extrair as principais informações encontradas no conteúdo das músicas, tentando entender melhor como elas evoluíram.

# Análise

## Coleta dos Dados

Os dados utilizados neste estudo foram coletados em um dos sites mais conhecidos e com um dos maiores acervos do gênero musical hip-hop/rap, o Genius. O próprio Genius disponibiliza uma [*API*](https://docs.genius.com/) que nos permite encontrar as músicas com maior facilidade. Entretanto, através desta API, não é possível obter propriamente as letras das músicas, apenas suas URLs. Diante disso, para extrair o conteúdo das obras por meio dos links coletados, foi utilizada uma técnica conhecida como *Web Scraping*, através da biblioteca [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/), disponibilizada na linguagem de programação Python, que atua como um parser de arquivos HTML, permitindo a extração das composições encontradas.

Para essa análise, decidi utilizar apenas alguns dos artistas que mais se destacaram no gênero levando em consideração apenas os norte-americanos, visto que a região tem sido o ambiente em que o gênero mais cresceu, se destacou e atingiu marcas expressivas desde o seu surgimento. Tais artistas foram identificados através de pesquisas em [fóruns](https://beats-rhymes-lists.com/lists/50-greatest-rappers-of-all-time/), [listas ordenadas por votação popular](https://www.ranker.com/crowdranked-list/the-best-80s-rappers), números de vendas de discos, entre outros. Ao todo, 118 artistas fizeram parte da lista final e foram selecionados os 50 top hits de cada um deles, ou seja, as músicas mais visualizadas no site.

Ao final do processo de coleta, uma base de dados foi estabelecida e contém as informações sobre o nomes dos artistas, nomes das músicas, data de lançamento e a letra das composições. A base de dados completa possui o total de 5900 registros, variando de músicas da década de 1980 até os dias atuais.

## Distribuição dos Dados

Na primeira parte da análise, procuramos visualizar como estão distribuídos os nossos dados.

{{< data_distribution >}}

No gráfico acima, podemos observar que a maior quantidade de músicas coletadas está concentrada na década de 2010, mais precisamente 51.79% da amostra, o que era esperado, visto que o gênero musical começou a ganhar mais força nos últimos 15 anos, consequentemente novos artistas foram aparecendo e entrando em evidência, além de desenvolverem mais composições em quantidade, sendo beneficiados pelo avanço da tecnologia que afetou positivamente a indústria musical.


A segunda maior concentração dos dados está nas composições datadas da década de 1990, representando 23% da amostra. Por fim temos as duas menores concentrações dos dados, sendo essas as décadas de 2000 e de 1980, apresentando 18.5% e 3.9% da amostra, respectivamente.

Uma informação importante é que não foi possível identificar a data de lançamento de cerca de 154 composições coletadas, sendo dessa forma, desconsideradas neste tópico.

## Frequência das Palavras

Dando continuidade à análise, nesse segundo momento busco entender melhor quais são as palavras que mais predominam as letras das músicas do gênero, considerando que através delas será possível compreender o que é discutido nas composições.

Foram selecionadas as top 20 palavras considerando todas as 5900 composições sem as separar por década e o resultado obtido é demonstrado no gráfico abaixo. Vale ressaltar que para esse contexto, foram retiradas as palavras obscenas e aquelas que não nos passam tantas informações.

{{< top_words >}}

É possível identificar, de imediato, a presença de palavras como “love”, “time”, “money”, “life”, demonstrando que é comum no gênero falar sobre o amor e a vida em si, além de abordar temas relacionados ao dinheiro, como um estilo de vida de ostentação, semelhante ao funk brasileiro, o que faz bastante sentido, visto que tanto rap quanto o funk surgem em contextos geográficos e socioeconômicos bem semelhantes.

Mais adiante, aparecem palavras como “black” e “god”, que provavelmente fazem referências à vida da comunidade negra nas grandes cidades, as dificuldades encontradas no seu cotidiano e também a demonstração da fé e da crença numa divindade. 

## Tamanho das Músicas

Na terceira parte da análise, foram extraídas informações sobre como as letras se comportam em relação ao seu tamanho. Como mostra o gráfico abaixo, entre todas as épocas, as canções tendem a não apresentar uma grande variabilidade em seus tamanhos, visto que as diferenças entre os terceiro quartil (75% percentil) e o primeiro quartil (25% percentil) são bem semelhantes em todos os boxplots.

{{< lyrics_length >}}

É possível notar que as músicas da década de 1980 possuem a menor média entre todas as épocas, contendo cerca de 2078 palavras, porém com uma certa similaridade à média das músicas mais atuais, da década de 2010, que possuem cerca de 2790 palavras. Um dos motivos que podem explicar esse fenômeno é o fato de que as músicas mais antigas tinham uma característica de se destacarem mais pela questão instrumental, sendo utilizadas como ambientadoras de boates e discotecas. O foco das músicas atuais não é necessariamente o mesmo, porém atinge resultados semelhantes, visto que muitos artistas atualmente têm se preocupado mais em desenvolver músicas “chicletes” que tendem a ser menores, mas que possuem uma melodia bem trabalhada que irão gerar mais repetições e, consequentemente, mais dinheiro.

Em contrapartida, as músicas da época de 1990 demonstram ser maiores, possuindo uma média de 3093 palavras, sendo seguidas pelas músicas da época de 2000, que possuem uma média de 3016 palavras. Provavelmente, as músicas dessas épocas são mais conhecidas pelo conteúdo lírico presente nelas. Muitos artistas que se destacam nessa época, tais como, 2Pac e The Notorious B.I.G, são famosos pelo fato de possuírem letras impactantes e bem trabalhadas, que abordam temas extremamente importantes de uma forma bem inteligente.

## Análise de Sentimento

Com o objetivo de deixar o trabalho mais interessante, foi realizada uma análise de sentimento, aplicada a toda a base de dados coletada, para gerar informações sobre quais são as emoções mais predominantes nas músicas de acordo com cada década.

{{< emotions >}}

A primeira coisa que é perceptível ao analisar o gráfico é quais são as emoções que mais se destacam em ordem. A emoção mais predominante entre as músicas do gênero é a raiva. Isso é algo bastante interessante, pois o rap costuma ser classificado como um gênero musical de protesto, mostrando a desigualdade social, a violência e a dificuldade da vida das pessoas que vivem nos bairros mais pobres da cidade. Em sequência, temos a presença dos sentimentos de tristeza e medo, trazendo uma ideia de que as músicas retratam um certo nível de angústia associados ao desespero, podendo ser por não conseguir encontrar soluções para os problemas enfrentados no dia a dia da comunidade negra, a falta de renda que podem levar alguns à vida do crime, ao tráfico de drogas, à vivenciar o sistema penitenciário, o racismo naturalizado nas ações da sociedade ou pela falta de esperança numa mudança para que cenários como os citados deixem de ser cada vez mais comuns. Por fim, temos os sentimentos de surpresa e alegria, sendo estes menos comuns, mas que mostram que algumas canções ainda conseguem retratar um lado mais leve da realidade, dos relacionamentos amorosos, da família, das conquistas pessoais, entre outros.

Ao olharmos as emoções por década, vemos que o sentimento de raiva e medo é maior nas décadas de 1990 se comparado com a década de 2000. De maneira contrária, o sentimento de tristeza se sobressai nas músicas da década de 2000 em relação à década de 1990.

## Análise de Tópicos

Por último, foi realizada uma análise de tópicos com os dados coletados, que buscou separar em alguns grupos os temas mais comuns discutidos nas músicas. No processo apenas as décadas de 1990 e 2000 geraram tópicos interessantes e válidos para discussão, portanto, apenas esses foram considerados na análise.

### Tópicos em 1990

Os principais tópicos identificados pelo modelo contém os principais temas encontrados como foco de discussão no gênero musical. No primeiro exemplo, o tópico 0 retrata assuntos relacionados ao próprio gênero musical, algo que é bastante comum, visto que muitos rappers e mc's costumam fazer batalhas de rimas, mostrando suas habilidades com as palavras, tentando fazer esquemas de rimas mais complexas e vencer o oponente. Dessa forma, vemos algumas palavras mais recorrentes, como “mic”, “rap”, "rhymes" e “mcs”. Outro tema muito comum nas músicas do gênero na época, fazem menção à figura da mulher de maneiras diferentes, podendo ser um provável contexto de relacionamentos amorosos ou até chegando a realizar comentários misóginos, machistas e de objetificação feminina. Isso é perceptível nos tópicos 1, 12 e 13 que têm como palavras mais frequentes “girl”, “hoes”, “sex”, “feeling”, “love” e “baby”.

![example](/topics_90s.png)

Os tópicos 4 e 5 mostram uma face mais intensa da realidade retratada nas músicas de rap, temas mais agressivos que tratam da violência e do crime enfrentados no cotidiano dos jovens das periferias das grandes cidades, principalmente na década de 1990, onde a cena do gangsta rap ficou mais evidente. Além disso, foi o momento em que houve a ascensão dos conflitos entre Bloods e Crips e da briga entre a Costa Oeste e Costa Leste, sendo representadas pelos rappers 2Pac e The Notorious B.I.G, respectivamente. Palavras como “murder”, “die”, “thugs”, “gun” e “war” estão presentes.

O tópico 7 contém um tema mais religioso, trazendo a presença de palavras como “god” e “lord”. Os tópicos 8 e 10 retratam alguns temas como o trabalho e o dinheiro, provavelmente falando sobre usar a música como uma forma de conseguir melhorar a condição financeira. Por fim, o tópico 9 retrata um tema bastante encontrado nas músicas do gênero, que fazem apologia ao consumo de drogas, principalmente a maconha, onde temos a presença das palavras “smoke”, “weed” e “blunt”. 

### Tópicos em 2000

Em relação aos tópicos encontrados nas canções da década de 2000, pouca coisa mudou no que diz respeito à temática abordada nas letras das músicas. Assim como os primeiros tópicos dos dados da década de 1990, o tópico 0 retrata um pouco dos temas que falam sobre o próprio gênero musical e também sobre a questão do gangsta rap, onde palavras como “gangsta”, “rap”, “hiphop”, “life”, e “game” estão presentes.  O tópico 1 já traz um tema mais triste, girando em torno de palavras que retratam a realidade da vida de quem compõe as músicas, onde palavras como “cry”, “pain”, “life” e “hell” aparecem. Os tópicos 5 e 8 se assemelham aos tópicos 1, 12 e 13 da década anterior, que retratam temas de prováveis relacionamentos amorosos e à sexualidade, onde palavras como “girl”, “shawty”, “baby”, “love” e “sexin” aparecem.

![example](/topics_00s.png)

Outro tema abordado é mostrado no tópico 6, trazendo a representação do ambiente em que a realidade retratada nas canções é vivida, tanto para falar sobre o orgulho de sua origem, quanto também para exibir os problemas que permeiam a região. Neste tópico encontramos palavras como “ghetto”, “home”, “hood”, “block” e “people”. Por fim, o tópico 9, possui um conteúdo de crítica ao sistema e ao governo, sendo inclusive um dos temas mais abordados pelo rapper *Immortal Technique*, conhecido pela sua técnica apurada e por tratar de assuntos como  a pobreza, o racismo, além dos temas previamente citados. As próprias palavras “immortal” e “technique” fazem parte das palavras mais encontradas neste tópico. Outra palavras encontradas são “world”, “truth”, “government” e “freedom”.

# Conclusão

Após toda a análise, percebo como a evolução das técnicas de Processamento de Linguagem Natural e da Inteligência Artificial desempenham um papel importante no entendimento de algumas temáticas da nossa sociedade de uma forma cada vez mais acessível e assertiva. Foi possível identificar características que não são tão óbvias à “olho nu”, apenas ouvindo as músicas, mas que vão de acordo com o que é imaginado por nós quando falamos sobre hip hop e rap. Ao longo do tempo, o gênero deixou de ser visto apenas como um ritmo popular pela influência nas festas e danças e se tornou um importante meio de informação e cultura para a juventude, sobretudo aqueles com uma maior vulnerabilidade socioeconômica.

Isso é mais evidente quando vemos as etapas de análise de sentimento e da análise de tópicos, onde temos como sentimentos mais predominantes a raiva, a tristeza e o medo, que casam perfeitamente com todos os tópicos descobertos, que falam sobre a violência, a dura realidade da vida na condição da pobreza, as maneiras de lidar com a dor que envolvem, principalmente, o consumo e o tráfico de drogas, a associação a grupos criminosos, como as gangues, entre outros aspectos.

Dessa forma, acredito que o hip hop e o rap tem sido, desde o início da sua existência, uma das grandes ferramentas usadas para falar sobre alguns dos problemas mais importantes da sociedade que ocorrem, principalmente, nas regiões mais pobres das grandes cidades, como as periferias e subúrbios, onde predomina a presença da comunidade negra, sendo esses o maiores afetados pela desigualdade social, o racismo estrutural inserido na cultura, a falta de acesso à direitos básicos e que acarreta na construção de um ambiente completamente insalubre e caótico que leva os jovens a tomarem atitudes desesperadoras, já que a falta de oportunidades e recursos é a realidade de muitos deles. 

Porém, as músicas não só falam sobre os problemas, mas também executam o papel de um instrumento cultural que ensina seu público a entender todo o contexto social, econômico e cultural no qual estão inseridos, passando mensagens de empoderamento, inspirando a tomada de novas atitudes com o objetivo de realizar uma significativa mudança social. 