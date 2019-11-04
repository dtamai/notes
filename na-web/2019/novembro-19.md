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



