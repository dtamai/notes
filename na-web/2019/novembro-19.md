# Novembro/19

## [Re-engineering Inclusion](https://www.youtube.com/watch?v=fggQAPEeiaI)

_01/11/2019 - Jill Wetzler, talk 35min, GOTO 2019_

Casos estranhos que acontecem com iniciativas atuais de Diversidade e Inclusão:

* tempo nesse trabalho extracurricular poderia ser gasto produzindo código, apesar do incentivo da empresa pra esse tipo de trabalho
* focar nessa questão interna é visto como falta de dedicação ao time, focar na comunidade externa também é falta de dedicação
* VP questiona a utilidade do grupo já que não viu melhoria de diversidade na empresa
* perde um prazo de entrega de código e a culpa é da iniciativa, que não é prioridade do time, mesmo o projeto final tendo sido entregue no prazo

A solução que Lyft está seguindo foi criar um grupo de trabalho formado por diretores e gerentes, principalmente homens, alguém de HR, tech leads para falar o que precisa ser resolvido. Presença da liderança é obrigatória, não há tarefas que tech leads precisam fazer, as ações são responsabilidade da liderança. Rotatividade desses papéis.

Atividades do grupo de trabalho sobre promoções para gestores: discussão sobre o que fazer quando há um feedback enviesado, aprender a identificar e responder esses casos. Uma ideia foi pedir uma segunda opinião.

Atividade para o grupo não representado em tech: a liderança apresenta como funciona o processo de promoção e a importância de cada um defender o próprio trabalho. Mas não caiu bem, porque o processo tem controle absoluto da gestão, o que alguém pode fazer caso a auto-avaliação não bater com a avaliação recebida?

Solução adotada: papel de um patrocinador para promoção. IC pede um patrocinador, HR escolhe alguém que faça sentido ser um terceiro ponto de vista. O patrocinador então precisa levantar informações e decidir se vai apoiar a promoção ou se vai ajudar a dar feedback negativo. Na reunião de calibração pode estar presente ou não, idealmente vai acompanhar depois do resultado.

Principais tópicos aprendidos:

* colocar autoridades responsáveis por D&I
* focar em uma iniciativa por vez
* ouvir todas as vozes, não tentar explicar cada caso
* explicar processos obscuros, explicar para o time como funciona, ouvir os comentários
* **percepção de viés é tão importante quanto viés real, o que qualquer pessoa sente é válido**
* incentivar gestores ajudarem no crescimento um do outro
* melhorar a situação dos grupos marginalizados melhora a situação pra todo mundo

> The goal of inclusion work is not "More black folk!" Or "More women!" The lack of black folk and women is a symptom of the root cause: opportunity to succeed and thrive is not evenly distributed.
>
> Mekka Okereke - [Twitter](https://twitter.com/mekkaokereke/status/1081630160443469824)

## [De-risking custom technology projects](https://github.com/18F/technology-budgeting/blob/master/handbook.md)

_03/11/2019 - 18F_

18F é um escritório do governo federal dos Estados Unidos que ajuda com necessidades de tecnologia, seja construção ou compra de soluções. Esse documento é um guia pra construção de software customizado com risco baixo e atendendo as exigências burocráticas que o governo deve se submeter.

> government can easily outsource the work of creating new technology systems, it cannot outsource the risk of failure

Essa frase dá o tom do guia: o único interesse do governo é ter a tecnologia funcionando e atendendo as necessidades do povo, direta ou indiretamente.

Técnicas ágeis estão muito presentes nas recomendações:

* como atender histórias ao invés de fazer o que uma especificação diz
* responder a mudanças faz parte do dia-a-dia, o escopo de trabalho é dinâmico
* reduzir o custo de mudanças usando tecnologias abertas, padronizadas
* medir sucesso por resultados interativos, não milestones, se não funciona não conta como sucesso
* limitar gastos e contratos, usando contratos pequenos e não muito longos, budgets não maiores que o necessário, construir o mínimo com o menor custo possível e iterar, contratos de entrega de valor, não de construção técnica
* manutenção é atividade comum, porque as necessidades dos usuários mudam, leis, regulações, políticas, melhores práticas, tecnologia também mudam, e o software precisa acompanhar essas mudanças se ainda precisa entregar valor, manutenção deve ser encarada como o mesmo tipo de atividade que construção

_Demos not memos_

Progresso é medido não através de documentos feitos para reportar progresso, mas sim via software funcionando, seja em produção ou em algum ambiente de staging. Para saber o que falta usar um burndown chart de histórias. Para saber se o software entregue atende as necessidades do governo fazer uma avaliação de qualidade.

O guia foca bastante em usar terceiros para construção de software, mas product owner precisa ser obrigatoriamente do governo. Assim desenvolvimento nesse contexto é um serviço, não parte do time de produto, que pra eleva bastante a qualidade profissional esperada, produto tem que comunicar bem as necessidades dos usuários, desenvolvimento precisa entender e propor soluções rápidas e eficientes, além de produzir software que passa por uma avaliação de qualidade a cada iteração. O processo é otimizado pra qualquer prestador de serviço poder continuar o trabalho.

## [Knowledge Debt](https://amir.rachum.com/blog/2016/09/15/knowledge-debt/)

_03/11/2019 - Amir Rachum_

Saber quando pegar e quando pagar dívidas é algo que se aprende com o tempo.

Amir Rachum fala de dívidas de conhecimento, usar antes de entender como funciona. Não podemos aprender tudo sobre tudo que fazemos, precisamos ser seletivos no que nos aprofundar. Não é fácil, mas é essencial.

## [How to Seduce Someone on a Date](https://www.youtube.com/watch?v=v9OdeEzon_0)

_03/11/2019 - The School of Life, vídeo 5min, YouTube_

O conteúdo da School of Life em geral considera amor como um relacionamento entre duas pessoas sem a visão romântica apaixonada.

Lidar com a própria fraqueza de maneira forte. Mostrar a fraqueza não é a mesma coisa que estar nervoso. Mostrar bom relacionamento com o próprio lado sombrio.

É estranho ser adorado, porque por dentro sabemos que não mercemos tanto. Reconhecer a outra pessoa como imperfeita e aprecia-la por isso, ao invés de adotar a visão errônea que ela é perfeita.

Não queremos adoração, mas que nos conheçam, e ainda assim gostem de nós e nos perdoem as falhas.

Auto-conhecimento e generosidade que fazem relacionamentos toleráveis.

## [My Most Embarrassing Mistakes as a Programmer \(so far\)](https://stackoverflow.blog/2019/10/29/my-most-embarrassing-mistakes-as-a-programmer-so-far/)

_04/11/2019 - Ellen Spertus_

Sobre erros, tem uma história sobre Thomas Watson da IBM, que recebeu a carta de demissão de um representante de vendas que perdeu um contrato milionário com o governo. Depois de explicar o que aconteceu e entregar a carta, o vendedor foi sair da sala quando Thomas Watson devolveu a carta dizendo que não pode aceitá-la porque, afinal, acabou de investir um milhão de dólares na educação do vendedor.

## [Seven Questions to Restart Love](https://www.youtube.com/watch?v=DI9UK9r7CQY)

_04/11/2019 - The School of Life, vídeo 8min, YouTube_

As perguntas são boas, e novamente, não é exclusivamente amor romântico.

1. Eu gostaria de ser apreciado por... - não jogar a culpa no outro, comunicar os próprios sentimentos. No começo é muito fácil ver o que há de bom na outra pessoa, mas com o tempo ficamos mimados
2. Quando estou em pânico eu... - nos momentos de calma podemos ousar assumir nossas estranhezas quando sob pressão, montar nosso próprio manual
3. Eu seria mais normal se ... não tivesse me acontecido na infância - conhecer o passado ajuda a entender melhor o presente, conhecer as dificuldades que ainda está lidando e talvez ainda não saiba como lidar
4. Eu gostaria de ser perdoado por... - reconhecer que trouxemos dificuldades, não somos perfeitos. Vamos tentar fazer melhor
5. Adoraria que você percebesse onde me machuca é... - as feridas se acumulam e não conseguimos nos expressar. O importante é ser ouvido e mostrar onde o outro machucou. Essa conversa não é para reavivar problemas, mas sim ajudar a resolvê-los
6. O que me ajudaria a mudar é se você... - precisamos de ajuda pra mudar. Não é uma promessa, mas sim um esforço de reconhecer nossas falhas e melhorar
7. O que eu sentiria muito sua falta é... - se não pudesse mais ver você, quando olhasse para trás o que mais sentiria falta?

## [The Rust 2018 Module System](https://www.youtube.com/watch?v=AN9FoZgLcFg)

_09/11/2019 - Josh Triplett, vídeo 33min, RustConf 2019_

A parte técnica é sobre o sistema de módulos do Rust 2018, mas a parte mais interessante é o processo pra chegar nesse sistema. Foram alguns anos de discussão, várias propostas, e alguns aprendizados:

* cuidados com soluções que só atendem os requisitos mas não agradam ninguém
* levantar problemas cedo, pra evitar apego aos experimentos iniciais
* refletir sobre quais valores guiam as discussões/decisões, inclusive os próprios valores
* trabalhar para alcançar os valores de cada um
* buscar soluções satisfatórias

## [Making the Grade](https://www.happinesslab.fm/episodes/making-the-grade)

_22/11/2019 - Dr. Laurie Santos, podcast 38 min, Happiness Lab_

Notas são recompensas externas, e esse tipo de motivação é pior que motivação interna. Outro problema é que muitas das escalas são relativas, então duas avaliações suficientes tem notas diferentes por detalhes irrelevantes.

## [The Efficiency-Destroying Magic of Tidying Up](https://florentcrivello.com/index.php/2019/09/04/the-efficiency-destroying-magic-of-tidying-up/)

29/11/2019 - Florent Crivello

Complexidade e caos não são a mesma coisa, querer colocar ordem em sistemas complexos não faz sentido. Massa, molho e queijo em potes separados não vira uma pizza.

> Nunca coloque ordem em um sistema antes de entender a estrutuar por baixo do caos.
>
> Scott's Law \(Florent Crivello\)

## [The 2-Word Trick That Makes Small Talk Interesting](https://forge.medium.com/the-2-word-trick-that-makes-small-talk-interesting-fdd4d5aa693)

_30/11/2019 - Dave Schools, Medium, pago_

Tô curioso. Curiosidade genuina, sem querer provar um ponto, mudar a ideia de alguém, apenas saber.

