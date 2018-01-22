# Ontologia da Gestão Cultural

## Introdução
## Participantes e processo de construção
## Núcleo do modelo (diagrama)
## Referências Externas do Modelo
## Modelo Completo (diagrama)
## Modelo Conceitual
#### Escopo
## Referências



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

A realização de mediação de grupos focais teve como objetivo extrair e organizar as informações dos especialistas de domínio, de maneira a permitir a modelagem e o desenvolvimento da ontologia de maneira totalmente colaborativa. Nesse tipo de método de controle de conteúdo gerado por grupos focais, são apresentada boas práticas para que seja possível fazer intervenções sem gerar conflitos ou prejudicar o processo de criação da inteligência coletiva. Dentre essas práticas heurísticas foram adotadas:

- Controlar o número de participantes;
- Gerar estratégias de envolvimentos dos componentes;
- Definir moderadores de grupo;
- Fazer a análise do conteúdo e gerar relatórios;
- Fazer registros dos pontos principais do grupo.

Esse tipo de metodologia é direcionado, em especial, para questões comportamentais e engenharia social, objetivando o maior aproveitamento das reuniões em grupo, tanto na questão do espaço físico, sobre como conduzir a reunião em si, quanto na parte de gestão das informações no momento das discussões.

<!-- ## Ferramenta para Edição Colaborativa de Ontologias: Tainacan Ontology -->


## Documentação da Ontologia


<!-- As super classes definidas pelo GT Glossário da Cultura foram: -->

### Agente

> **Definição**:

> É o indivíduo, grupo ou instituição, que atua no planejamento, execução, gestão, avaliação, criação, produção, difusão, pesquisa, e ensino no campo da cultura.

São identificadas como subclasses de Agente (e suas definições):

> Agente Coletivo: agente que representa um grupo, instituição ou similar, que atue como um ente coletivo.

> Agente individual: agente que representa apenas um indivíduo, grupo, instituição ou similar, que atua como um ente único.

A estrutura final de subclasses da classe Agente proposta pelo GT foi a seguinte:

- **Agente**
  - **Agente Coletivo**
    - Grupo de Cultura
    - Instituição
      - Administração Pública
        - Órgão Gestor de Cultura
      - Entidade Empresarial
        - Cooperativa
        - Empresa Privada
      - Terceiro Setor
        - Associação
    - Órgão Colegiado
      - Comissão Intergestores
      - Conselho de Política Cultural
    - Povo e Comunidade Tradicional
      - Comunidade Tradicional
      - Povo Indígena
  - **Agente Individual**

Os relacionamentos propostos, em grande parte extraídos da tipologia atual do SNIIC e, também em sua maioria, são diferentes apenas entre as subclasses "Agente Coletivo" e "Agente Individual", que possuem características específicas.

O resultado da modelagem de relacionamentos baseados na classe Agente foi o seguinte:

- **Agente**
  - Relacionamentos Comuns
    - criaEspaço - Espaço
    - elaboraInstrumento - Instrumento
    - financiaAção - Múltiplo
    - financiaEspaço - Espaço
    - fiscalizaAção - Ação
    - gereEspaço - Espaço
    - mantémEspaço - Espaço
    - planejaAção - Ação
    - produzInstrumento - Instrumento
    - realizaAção - Ação
    - regulamentaInstrumento - Instrumento
    - trabalhaEmEspaço - Espaço
    - utilizaInstrumento - Instrumento
    - utilizaEspaço - Espaço
  - Relacionamentos de Agente Coletivo
    - compostoPor - Agente
    
O resultado da criação de atributos para a classe Agente (e os seus respectivos tipos) é apresentado a seguir:

- **Agente**
  - Atributos Comuns
    - Nome - Texto
    - Área de atuação - Taxonomia
    - Descrição curta - Texto
    - Website - Texto
    - Email - Texto
    - Telefone - Texto
    - Localização geográfica - Texto
    - CEP	- Texto
    - Logradouro - Texto
    - Número - Texto
    - Complemento	- Texto
    - Bairro - Texto
    - Município	- Texto
    - UF - Taxonomia
    - Descrição - Texto
  - Atributos de Agente Individual
    - CPF	- Texto
    - Data de nascimento	- Data
    - Gênero	- Taxonomia
    - Orientação sexual	- Taxonomia
    - Raça/cor	- Taxonomia
    - Ocupação	- Taxonomia
  - Atributos de Agente Coletivo
    - CNPJ	- Texto
    - Tipologia	- Taxonomia
    - Esfera	- Taxonomia
    - Tipo de esfera	- Taxonomia
    - Títulos e certificados	- Taxonomia

### Espaço

Lugares, fixos ou móveis/itinerantes, virtuais ou físicos, onde ocorrem ações culturais.

São identificadas como subclasses de Espaços:

> Equipamento Cultural: constituem o estoque fixo ligado à cultura existente no momento de pesquisa no município, aberto ao público, podendo ou não ser mantido pelo poder público de qualquer esfera, seja ele federal, estadual ou municipal.

> Espaço Potencialmente Cultural: locais aptos a receberem ações culturais, porém não caracterizados como equipamentos culturais.

A estrutura final de subclasses da classe Espaço proposta pelo GT foi a seguinte:

- **Espaço**
  - Equipamento Cultural
    - Arquivo
    - Biblioteca
    - Centro Cultural
    - Circo 
    - Espaço Reliogioso
    - Museu
    - Teatro
  - Espaço Potencialmente Cultural
  
O resultado da modelagem de relacionamentos baseados na classe Espaço foi o seguinte:

- **Espaço**
  - Relacionamentos
    - atraiPúblico - Público
    - recebePúblico - Público
  
O resultado da criação de atributos para a classe Espaço (e os seus respectivos tipos) é apresentado a seguir:
  
- **Espaço**
  - Atributos
    - Nome - texto
    - Área de atuação -	Taxonomia
    - Descrição curta -	Texto
    - Acessibilidade - Lógico
    - Acessibilidade Física - Taxonomia
    - Horário de funcionamento - Texto
    - Website	- Texto
    - Email	- Texto
    - Telefone - Texto
    - Localização geográfica - Texto
    - CEP	- Texto
    - Logradouro - Texto
    - Número - Texto
    - Complemento - Texto
    - Bairro - Texto
    - Município - Texto
    - UF - Texto
    - Descrição - Texto
    - Critério de uso do espaço - Texto
    - Tipo - Taxonomia
    - Gestor(a)(s) - Texto
    - Esfera - Taxonomia
    - Tipo de esfera - Taxonomia
    - EstaCedidoPara - Agente
    - éVirtual - Lógico
    - SituaçãoDeFuncionamento -	Taxonomia
    - AcessoAoPúblico	- Taxonomia
    - Tipo - Taxonomia

### Ação

> **Definição**:

> Conjunto de atividades e procedimentos, envolvendo recursos humanos e materiais, que visam pôr em prática os objetivos de um agente ou de uma determinada política cultural.

São identificadas como subclasses de Ação (e suas definições):

> Criação: ações relacionadas ao uso de potencialidades criativas para elaboração de ideias, conteúdos e produtos culturais originais.

> Difusão: ações que criam oportunidades de disseminação da cultura, fruição e troca de experiências, por meio da ampliação de circuitos de distribuição e da descentralização da oferta cultural, propiciando a circulação de diversas expressões culturais e linguagens, contribuindo para a formação ampla do cidadão.

> Formação: ações educativas, formais ou não formais, que buscam ampliar o repertório cultural dos participantes e/ou facilitar o estabelecimento de relacionamentos inspiradores com a arte e a cultura nas dimensões de apropriação, fruição, expressão, experimentação ou especialização.

> Governança: ações que contribuem para a melhoria da qualidade de uma organização, para o melhor desempenho de suas atividades e fortalecimento institucional. Abrange atividades de apoio técnico a municípios e instituições culturais, a articulação e a construção de parcerias para realização de ações conjuntas, a captação de recursos, o incremento da comunicação institucional, a melhoria da infraestrutura, a qualificação técnica de funcionários, a realização de pesquisas de perfil e satisfação do público e demais rotinas. Em geral, esse tipo de função não está associada diretamente a um público externo.

> Preservação: ações voltadas para a valorização do patrimônio cultural, em todas as suas vertentes, por meio de reconhecimento, pesquisa, conservação, proteção, restauração e/ou manutenção de bens materiais e imateriais considerados significativos por determinado grupo social.

> Produção: ações relacionadas ao uso de potencialidades criativas para elaboração de ideias, conteúdos e produtos culturais originais.

A estrutura final de subclasses da classe Ação proposta pelo GT foi a seguinte:

- **Ação**
  - **Criação**
  - **Difusão**
  - **Formação**
  - **Governança**
  - **Preservação**
  - **Produção**
  
 O resultado da modelagem de relacionamentos baseados na classe Ação foi o seguinte: 
 
- **Ação**
  - Relacionamentos
    - aconteceEm - Espaço
    - atingePúblico - Público
    - éExecutadaPor - Agente
    - éOrientadaPor - Instrumento
    - temPublico - Público
    
O resultado da criação de atributos para a classe Ação (e os seus respectivos tipos) é apresentado a seguir:    

- **Ação**
  - Atributos
    - Tradução para Libras - Lógico
    - Áudio descrição - Lógico
    - Classificação etária - Taxonomia
    - Preço - Texto
    - Nome - Texto
    - Descrição Curta - Texto
    - RecebeuRecursos	- Valor Inteiro
    - RecebeuVerbaPública -	Lógico
    - ImpactaTerritórios -	Lista
    - TeveMeiaEntrada -	Lógico
    - QualidadeMeiaEntrada -	Lista
    - QuantidadeMeiaEntradaPorTipo -	Valor Inteiro
    - TemConteúdoAcessível -	Lógico

### Instrumento

> **Definição**:

> São meios, mecanismos ou ferramentas de gestão cultural que orientam a relação dos agentes, espaços, públicos e ou ações.

São identificadas como subclasses de Instrumento:

> Ato Jurídico: é uma manifestação da vontade humana que produz efeitos jurídicos, causando a aquisição, modificação ou extinção de relações jurídicas e de seus direitos. Assim, são fatos jurídicos que consistem em manifestações da vontade humana.
  
> Documento Referencial: documento que fornece detalhes pertinentes para a consulta sobre um assunto no campo da cultura. Os documentos de referência podem ser publicações (impressas ou eletrônicas), bases de dados (internas, externas) e páginas da Web, entre outros.

> Norma Jurídica: é uma regra de conduta imposta, admitida ou reconhecida pelo ordenamento jurídico. Norma e lei são usadas comumente como expressões equivalentes, mas norma abrange na verdade também o costume e os princípios gerais do direito. Como exemplos, existem os tratados internacionais, normas constitucionais, legais e infralegais.

> Sistema Operativo: podem ser vistos de dois pontos de vista, sendo gerenciadores de recursos e/ou máquinas estendidas.

A estrutura final de subclasses da classe Instrumento proposta pelo GT foi a seguinte:

- **Instrumento**
   - Ato Jurídico
    - Ato Administrativo
    - Contrato
  - Documento Referencial
  - Norma Jurídica
  - Sistema Operativo


O resultado da modelagem de relacionamentos baseados na classe Instrumento  foi o seguinte:

- **Instrumento**
  - Relacionamentos
    - medeiaAção - Ação
    - normatizaAção - Ação
    - orientaAgente - Agente
    - publicisaAção - Ação
    - regulaEspaço - Espaço
    - regulamentaAção - Ação
    - regulamentaEspaço - Espaço
    - viabilizaAção - Ação
    
O resultado da criação de atributos para a classe Instrumento (e os seus respectivos tipos) é apresentado a seguir:

- **Instrumento**
  - Atributos Comuns
    - Título - texto
    - Descrição -	texto
    - Vigência -	boolean
    - Data de vigência - date
    - Data de publicação	- date
    - Esfera	- texto
    - Tipo - texto
  - Atributos de Contrato
    - Partes envolvidas - texto
  - Atributos de Sistema Operativo
    - Função - texto
  

### Público

> **Definição**:

> São indivíduos ou coletivos que usufruem direta ou indiretamente das ações e/ou dos espaços culturais.

A estrutura final de subclasses de Público proposta pelo GT, com suas respectivas definições, foi:

> Potencial: são “indivíduos” (agentes) que ainda não participam/participaram de ação cultural e que podem vir a se tornar público presencial ou virtual.

> Presencial: público presencial das ações culturais e/ou dos espaços físicos.

> Virtual: público que acessa, participa, cria e vivencia as ações culturais virtuais e os espaços virtuais na internet.

A estrutura final de subclasses da classe Público proposta pelo GT foi a seguinte:

- **Público**
  - Potencial
  - Presencial
  - Virtual
  
O resultado da modelagem de relacionamentos baseados na classe Público  foi o seguinte:

- **Público**
  - Relacionamentos
    - frequentaEspaço - Espaço
    - interageCom - Agente
    - paga - Ação
    - participaDeAção - Ação
    - utilizaEspaço - Espaço
    - utilizaInstrumento - Instrumento
    
O resultado da criação de atributos para a classe Público (e os seus respectivos tipos) é apresentado a seguir:

- **Público**
  - Atributos
    - FaixaEtária	- Lista
    - Tipo de engajamento - Texto	
    - Segmento de público	- Texto

<!-- 
## Discussões sobre os Resultados
### Versão Beta da Ontologia
### Desenvolvimento de Metolologia para Construção Colaborativa de Ontologias
### Desenvolvimento de Ferramenta Colaborativa para Construção de Ontologias
-->






