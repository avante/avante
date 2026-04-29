# Estimativas em Desenvolvimento de Software: uma crítica sob a ótica da capacidade produtiva, engenharia e responsabilidade gerencial

## Introdução

Desde o surgimento dos métodos ágeis, especialmente a partir dos anos 2000, o mercado de desenvolvimento de software passou a buscar alternativas aos modelos tradicionais de gestão de projetos, marcados por planejamento extensivo, cronogramas rígidos e forte centralização do controle. Nesse contexto, frameworks como Scrum, Kanban e Extreme Programming ganharam espaço ao propor ciclos curtos, adaptação contínua e maior proximidade entre negócio e tecnologia.

Entretanto, ao longo da popularização da Agilidade, consolidou-se também uma prática amplamente difundida: a estimativa de esforço realizada pelo próprio time de desenvolvimento. Planning poker, story points, sizing e outras técnicas passaram a ocupar posição central no processo de planejamento. Em muitas organizações, tais estimativas tornaram-se o principal insumo para responder perguntas clássicas de negócio: quando ficará pronto e quanto irá custar.

Este ensaio sustenta uma crítica a esse modelo. Defende-se que estimativas subjetivas realizadas pelo time agregam pouco valor operacional, deslocam responsabilidades gerenciais para equipes técnicas e frequentemente produzem previsões frágeis. Em contraposição, argumenta-se que a previsibilidade deveria emergir da capacidade histórica observada do sistema produtivo, apoiada por excelência em engenharia de software, gestão de fluxo e análise estatística.

---

## A centralidade indevida das estimativas

A estimativa tornou-se, em muitas empresas, uma espécie de ritual obrigatório. Antes de iniciar o trabalho, espera-se que o time atribua valores às demandas e, a partir deles, construa compromissos futuros. O problema central desse modelo reside no fato de que estimativas são, em essência, projeções subjetivas sobre um trabalho ainda não realizado.

Mesmo quando conduzidas com boa intenção, estimativas sofrem influência de diversos fatores:

* desconhecimento técnico inicial;
* requisitos incompletos;
* dependências ocultas;
* variabilidade humana;
* pressão política por datas;
* viés de otimismo;
* mudanças de escopo ao longo da execução.

O resultado é que números produzidos como aproximações passam a ser tratados como promessas. O que deveria servir apenas como hipótese vira meta operacional, mecanismo de cobrança e base para compromissos externos.

Sob essa ótica, a estimativa deixa de ser uma ferramenta útil e passa a representar desperdício: consome tempo do time, gera falsa sensação de precisão e frequentemente deteriora a qualidade da decisão organizacional.

---

## O verdadeiro valor das discussões técnicas

É importante distinguir estimativa daquilo que normalmente ocorre ao seu redor. Muitas vezes, sessões de planning produzem benefícios reais — mas não por causa do número final atribuído.

O que costuma agregar valor são atividades paralelas, tais como:

* esclarecimento do escopo;
* identificação de riscos;
* decomposição de trabalho;
* alinhamento arquitetural;
* discussão de abordagem técnica;
* explicitação de critérios de aceite;
* percepção de dependências.

Esses ganhos pertencem ao campo da engenharia e do entendimento do problema, não ao ato de estimar em si. Em outras palavras, se tais conversas são úteis, elas poderiam existir independentemente da geração de pontos, horas ou qualquer unidade abstrata.

---

## Previsibilidade como propriedade do sistema

Uma alternativa mais robusta consiste em tratar previsibilidade não como opinião humana, mas como propriedade estatística do processo produtivo.

Quando uma equipe trabalha com práticas consistentes, itens menores, fluxo estável e entregas frequentes, torna-se possível medir indicadores concretos como:

* throughput (quantidade entregue por período);
* lead time;
* cycle time;
* variabilidade;
* percentis de entrega;
* tendências históricas.

Com base nesses dados, previsões deixam de depender exclusivamente da intuição do time e passam a ser formuladas probabilisticamente. Em vez de afirmar “essa demanda leva duas semanas”, a organização pode dizer:

> Com base no histórico recente, existe 85% de probabilidade de concluir itens desse porte entre X e Y dias.

Esse tipo de abordagem é intelectualmente mais honesto e gerencialmente mais útil, pois reconhece incerteza sem abdicar da tomada de decisão.

---

## O papel central da engenharia de software

Se previsibilidade depende da capacidade do sistema, então o foco principal do time deveria recair sobre aquilo que aumenta essa capacidade. Nesse ponto, práticas defendidas historicamente pelo Extreme Programming tornam-se especialmente relevantes:

* integração contínua;
* testes automatizados;
* refatoração constante;
* design simples;
* entregas frequentes;
* feedback rápido;
* propriedade coletiva do código;
* pequenas mudanças incrementais.

A essas práticas podem ser somadas abordagens modernas como CI/CD, trunk-based development, observabilidade, automação de qualidade e gestão visual de fluxo.

Quando a equipe investe nesses fundamentos, reduz retrabalho, diminui variabilidade e acelera aprendizado. A previsibilidade surge como consequência natural da excelência operacional, e não como produto de reuniões de estimativa.

---

## Responsabilidade do time e responsabilidade da gestão

Outro ponto crítico refere-se à distribuição correta de responsabilidades organizacionais.

O time técnico deve ser responsável por:

* qualidade do produto;
* sustentabilidade técnica;
* eficiência do fluxo;
* melhoria contínua;
* transparência sobre riscos técnicos;
* colaboração contínua com stakeholders na descoberta e refinamento de valor.

Já a gestão deve ser responsável por:

* compromissos externos;
* priorização econômica;
* decisões de escopo;
* análise de risco;
* alocação de recursos;
* comunicação executiva e alinhamento organizacional.

Isso não implica afastamento entre time e stakeholders. Pelo contrário: equipes maduras devem manter contato direto e frequente com clientes, usuários e áreas interessadas, reduzindo ruído de comunicação, acelerando feedback e ampliando a compreensão do problema.

Quando se exige, porém, que o time responda isoladamente “quando ficará pronto?”, transfere-se para a camada técnica uma responsabilidade que, em essência, é gerencial. Datas e custos não dependem apenas do esforço de desenvolvimento, mas de contexto estratégico, tolerância a risco, urgência de mercado e escolhas de escopo.

Portanto, cabe à gestão transformar capacidade observada em compromissos de negócio. O papel do time é fornecer um sistema produtivo confiável, colaborar diretamente com stakeholders e aprimorar continuamente sua capacidade de entrega.

---

## O caso da inovação e da ausência de histórico

É legítimo argumentar que projetos inéditos ou contextos altamente incertos não dispõem de dados históricos suficientes. Nesses cenários, algum grau de julgamento qualitativo pode ser necessário.

Ainda assim, a resposta mais madura não é ampliar estimativas detalhadas, mas reduzir o tamanho das apostas:

* quebrar iniciativas em lotes menores;
* validar hipóteses cedo;
* entregar incrementos mínimos;
* coletar dados rapidamente;
* recalibrar continuamente.

Trata-se da lógica dos baby steps: em vez de prever grandes jornadas no escuro, aprende-se por ciclos curtos.

---

## Conclusão

A prática tradicional de estimativas feitas pelo time tornou-se dominante no mercado ágil, mas sua centralidade merece revisão crítica. Em muitos contextos, ela consome energia sem elevar a qualidade real da previsibilidade, além de transferir para equipes técnicas responsabilidades típicas da gestão.

Uma abordagem mais consistente consiste em reconhecer que previsibilidade nasce da capacidade do sistema produtivo. Equipes devem concentrar-se em engenharia de software, redução de variabilidade, fluxo contínuo e melhoria operacional. A gestão, por sua vez, deve usar dados históricos e análise estatística para construir compromissos responsáveis com o negócio.

Em síntese: não se trata de rejeitar planejamento, mas de substituir opiniões frágeis por evidências reais. Onde estimativas prometem certeza, sistemas maduros oferecem probabilidade. E, no desenvolvimento de software, probabilidade bem fundamentada costuma valer mais do que precisão ilusória.
