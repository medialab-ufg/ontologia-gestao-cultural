# Ontologia da Gestão Cultural

A importância da organização de dados na era da informação têm sido amplamente discutida em diferentes áreas de pesquisa. De acordo com as pesquisas nessa área, existem muitas formas de realizar esse tipo de trabalho, seja por uso de glossários, vocabulários, dicionários ou até mesmo de taxonomias que permitem que os dados sejam organizados de forma estruturada, facilitando os processos de busca e recuperação de informações. 

Entretanto, devido ao volume e diversidade de dados que circula hoje pela Internet, uma classificação de termos de forma sintática tem se mostrado insuficiente para manter o significado dos dados de forma individualizada e confiável. Nesse sentido, pesquisas e tecnologias para web semântica vem sendo desenvolvidas e as ontologias ganham notoriedade devido ao seu grande potencial em organizar e representar os dados com maior confiabilidade, permitir categorização e classificação com menor propensão a erros, e permitir que a informação codificada seja interpretada por seres humanos e máquinas.

O presente relatório apresenta o projeto e criação de uma ontologia para a Gestão Cultural, trabalho de interesse do Ministério da Cultura (MinC), em parceria com o Laboratório de Políticas Públicas Participativas (L3P) da Universidade Federal de Goiás (UFG). São descritos aqui: a metodologia de construção colaborativa de ontologias, a versão beta da ontologia, e as principais contribuições da pesquisa e estudos realizados.

## GT Glossário da Cultura

Em geral, quando se trabalha com a criação de ontologias, devido ao grau de complexidade dessas estruturas de dados, o método padrão se baseia na parceria entre os especialistas de domínio e os técnicos ou engenheiros de ontologia, que são responsáveis por modelar o conhecimento de dominio repassado pelos especialistas e desenvolver a ontologia através de linguagem computacional apropriada. Entretanto, para a realidade do projeto, visando aproximar ainda mais o especialista de domínio do processo de modelagem de conhecimento da Gestão Cultural, foi adotada uma forma de trabalho colaborativa entre a parte especialista e a parte técnica, objetivando trazer os especialistas de domínio para o processo de desenvolvimento participativo, tanto para coletar uma grande massa de dados, quanto para validar todas as informações de domínio

Nesse contexto, foi riado o GT Glossário da Cultura, grupo de trabalho que contou com mais de 50 especialistas de domínio, fixos e também colaboradores sazonais, que, através de reuniões de trabalho presenciais e online, juntamente com o grupo de pesquisa L3P, realizaram o trabalho de modelagem e desenvolvimento da Ontologia da Gestão Cultural. Para chegar a este resultado foram analisadas metodologias de trabalho específicas para a criação colaborativa de ontologias, a partir da qual foi também criada uma metodologia própria, além do desenvolvimento de uma ferramenta web para edição colaborativa de ontologias, fomentando ainda mais a integração de todos os participantes nesse processo.

## Metodologia para Desenvolvimento Colaborativo de Ontologias

A metodologia para criação da Ontologia da GEstão Cultural foi baseada na revisão sistemática de metodologias de criação de ontologias, visando ytazer consistência nos trabalhos de desenvolvimento e a criação, que se mostrou necessária, de um novo modelo colaborativo de criação de ontologias. 

> Segundo Siqueira et al (2008), entende-se **metodologia para criação de ontologias** como um conjunto de processos que têm como objetivo planejar, organizar, liderar, coordenar e controlar todo o ciclo de vida de uma ontologia, garantindo sua aplicação e utilização, assim como definindo métodos para conduzir as pessoas responsáveis por sua manipulação através da realização de suas atividades.

Nesse contexto, os seguintes modelos de gestão de ontologias que estudados para possibilitar a criação da metodologia colaborativa adotada para a Ontologia da gestão cultural:

- Metodologia Uschold e King: construção de ontologia para processos de modelagem de empresas.

- Metodologia Grüninger & Fox: desenvolvimento de uma ontologia dentro do domínio de processos de negócios e modelagem de atividades.

- Metodologia 101: guia simples baseado em processos iterativos que ajudam os desenvolvedores, mesmo que não sejam especialistas em Engenharia de Ontologias, a criarem uma ontologia usando ferramentas, como por exemplo o Protégé.

- Método KACTUS: este método para desenvolver ontologias está condicionado ao desenvolvimento de aplicações e tem como base uma aplicação da base de conhecimento, por meio de um processo de abstração (isto é, seguindo uma estratégia bottom-up).

- Método SENSUS: esta metodologia é baseada na ontologia SENSUS, que foi criada para fornecer uma estrutura conceitual ampla para desenvolver tradutores automatizados.

- Metodologia On-To-Knowledge: a metodologia On-To-Knowledge (OTK) tem como principal interesse a construção de grandes sistemas de gestão do conhecimento.

- METHONTOLOGY: possibilita a construção de ontologias e inclui a identificação do seu processo de desenvolvimento, um ciclo de vida baseado na evolução de protótipos e técnicas particulares para cumprir cada atividade.

- Processo KUP (Knowledge Unified Process): é um processo unificado proposto para desenvolvimento de ontologias e bases de conhecimento, que deverão ser utilizadas em aplicações para a Web Semântica.

- Metodologia DILIGENT: tem por objetivo criar um conjunto de ontologias para que o usuário possa compartilhá-las e, ao mesmo tempo, possa expandir seu uso local, seja por seu desejo ou necessidade individual.

- Metodologia  CO4 (Cooperative Construction of Consensual knowledge bases): é um protocolo para chegar a um consenso entre várias bases de conhecimento (BCs), que são organizadas em estrutura de árvore. Permite que usuários discutam sobre o conhecimento introduzido em bases de conhecimento, as quais são compartilhadas; essas bases são ontologias, pois deve haver consenso sobre o conhecimento ali representado. Quando uma mudança é proposta, os usuários são notificados e podem aceitá-la ou não.

- Metodologia Cyc: codifica o conhecimento das fontes e, quando já existe conhecimento suficiente na ontologia, um novo consenso é obtido por ferramentas de linguagem natural.

Após a análise detalhada de todas as metodologias citadas, foram avaliados levantados os critérios que atenderiam a demanda do projeto da Ontologia da Gestão Cultural, sendo o indicador com maior peso para escolha da metodologia a **organização dos processos de construção de ontologias**, validado por especialistas na área. A partir dessa premissa foi adotada como base principal o processo de construção descrito pela Metodologia 101, que é um dos estudos pioneiros na área de construção de ontologias e um dos mais referenciados em publicações científicas dessa área, o que reforça sua aplicação e validação na literatura.

Noy e McGuinness (2001), autores da Metodologia 101, descrevem práticas heurísticas sobre a área de criação de ontologias. A partir dessas práticas, utilizadas também para definição da estrutura de trabalho para o GT Glossário da cultura, foram definidos os pontos principais da metodologia de trabalho, que serão apresentados a seguir.

## Desenvolvimento colaborativo da Ontologia de Gestão Cultural

A metodologia do grupo de trabalho teve como premissas as seguintes etapas:

- Diagnóstico de ontologias (pre)existentes sobre o tema Gestão Cultural
- Avaliação de referências para desenvolvimento da ontologia
- Criação das Classes da ontologia
- Criação dos Atributos e Relacionamentos da ontologia
- Validação da ontologia


### Projeção e Condução de Entrevistas em Grupos Focais

Realização de mediação de grupos focais, com o objetivo de extrair e organizar as informações dos especialistas de domínio, no sentido de deixar todos os participantes do grupo de trabalho confortáveis e expor suas ideias. Usamos como base, Krueger (2002) que explica mais sobre como tornar esse processo mais simples e objetivo, independente de qual seja o tema trabalhado. Nesse tipo de método de controle de conteúdo gerado por grupos focais, é apresentada boas práticas para que seja possível fazer as intervenções sem gerar conflitos ou prejudicar o processo de criação da inteligência coletiva. Dentre essas práticas heurísticas, são:

- Controlar o número de participantes;
- Gerar estratégias de envolvimentos dos componentes;
- Definir Moderadores de Grupo;
- Fazer a Análise do Conteúdo e gerar Relatórios;
- Fazer Registros dos pontos principais do Grupo.

Esse tipo de metodologia é direcionado, em especial, para questões comportamentais e engenharia social de como agir para ter o maior aproveitamento das reuniões em grupo, tanto na questão do espaço físico, sobre como conduzir a reunião em si, quanto na parte de gestão das informações no momento das discussões.

<!-- ## Ferramenta para Edição Colaborativa de Ontologias: Tainacan Ontology -->


## Documentação da Ontologia


As super classes definidas pelo GT Glossário da Cultura foram:

### Agente

É o indivíduo, grupo ou instituição, que atua no planejamento, execução, gestão, avaliação, criação, produção, difusão, pesquisa, e ensino no campo da cultura.

### Espaço

Lugares, fixos ou móveis/itinerantes, virtuais ou físicos, onde ocorrem ações culturais.

### Ação

Conjunto de atividades e procedimentos, envolvendo recursos humanos e materiais, que visam pôr em prática os objetivos de um agente ou de uma determinada política cultural.

### Instrumento

São meios, mecanismos ou ferramentas de gestão cultural que orientam a relação dos agentes, espaços, públicos e ou ações.

### Público

São indivíduos ou coletivos que usufruem direta ou indiretamente das ações e/ou dos espaços culturais

### Atributos e Relacionamentos

## Resultados Alcançados

### Versão Beta da Ontologia

### Desenvolvimento de Metolologia para Construção Colaborativa de Ontologias

### Desenvolvimento de Ferramenta Colaborativa para Construção de Ontologias






