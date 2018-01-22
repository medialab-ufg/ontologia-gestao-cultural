# Ontologia da Gestão Cultural

## Introdução
A importância da organização de dados na era da informação têm sido amplamente discutida em diferentes áreas de pesquisa. De acordo com as pesquisas nessa área, existem muitas formas de realizar esse tipo de trabalho, seja por uso de glossários, vocabulários, dicionários ou até mesmo de taxonomias que permitem que os dados sejam organizados de forma estruturada, facilitando os processos de busca e recuperação de informações. 

Entretanto, devido ao volume e diversidade de dados que circula hoje pela Internet, uma classificação de termos de forma sintática tem se mostrado insuficiente para manter o significado dos dados de forma individualizada e confiável. Nesse sentido, pesquisas e tecnologias para web semântica vem sendo desenvolvidas e as ontologias ganham notoriedade devido ao seu grande potencial em organizar e representar os dados com maior confiabilidade, permitir categorização e classificação com menor propensão a erros, e permitir que a informação codificada seja interpretada por seres humanos e máquinas.

O presente relatório apresenta o projeto e criação de uma ontologia para a Gestão Cultural, trabalho de interesse do Ministério da Cultura (MinC), em parceria com o Laboratório de Políticas Públicas Participativas (L3P) da Universidade Federal de Goiás (UFG). São descritos aqui: a metodologia de construção colaborativa de ontologias, a versão beta da ontologia, e as principais contribuições da pesquisa e estudos realizados.

## Participantes e processo de construção
Em geral, quando se trabalha com a criação de ontologias, devido ao grau de complexidade dessas estruturas de dados, o método padrão se baseia na parceria entre os especialistas de domínio e os técnicos ou engenheiros de ontologia, que são responsáveis por modelar o conhecimento de dominio repassado pelos especialistas e desenvolver a ontologia através de linguagem computacional apropriada. Entretanto, para a realidade do projeto, visando aproximar ainda mais o especialista de domínio do processo de modelagem de conhecimento da Gestão Cultural, foi adotada uma forma de trabalho colaborativa entre a parte especialista e a parte técnica, objetivando trazer os especialistas de domínio para o processo de desenvolvimento participativo, tanto para coletar uma grande massa de dados, quanto para validar todas as informações de domínio

Nesse contexto, foi criado o GT Glossário da Cultura, grupo de trabalho que contou com mais de 50 especialistas de domínio, fixos e também colaboradores sazonais, que, através de reuniões de trabalho presenciais e online, juntamente com o grupo de pesquisa L3P, realizaram o trabalho de modelagem e desenvolvimento da Ontologia da Gestão Cultural. Para chegar a este resultado foram analisadas metodologias de trabalho específicas para a criação colaborativa de ontologias, a partir da qual foi também criada uma metodologia própria, além do desenvolvimento de uma ferramenta web para edição colaborativa de ontologias, fomentando ainda mais a integração de todos os participantes nesse processo.

### Metodologias para criação de ontologias: uma revisão metodológica
A metodologia para criação da Ontologia da GEstão Cultural foi baseada na revisão sistemática de metodologias de criação de ontologias, visando trazer consistência nos trabalhos de desenvolvimento e a criação, que se mostrou necessária, de um novo modelo colaborativo de criação de ontologias.  A lista de [referências] (https://github.com/medialab-ufg/ontologia-gestao-cultural/blob/master/Documenta%C3%A7%C3%A3o.md#refer%C3%AAncias) apresentada abaixo mostra as pesquisas utilizadas como base para a realização deste projeto.

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

### Processo de trabalho selecionado e a Metodologia 101
O detalhamento de referência da Metodologia 101 pode ser encontrado em: https://protege.stanford.edu/publications/ontology_development/ontology101.pdf

No entanto, para simplificar, as 07 etapas propostas foram adaptadas para este projeto da maneira descrita a seguir:

1.	Definir escopo e domínio
A etapa da definição do escopo e domínio da ontologia tem por objetivo entender qual o foco temático e processual que a ontologia deve atender, sabendo que esse trabalho de definição delimita as informações e conhecimentos sistematizados que a ontologia deve cobrir. É nesse momento que vamos definir os objetivos da ontologia, que perguntas concretas a ontologia deve responder e qual deve ser o modelo de governança responsável pela gestão da própria ontologia. 

2.	Avaliar taxonomias existentes para possível reutilização
Nesta etapa, temos por objetivo mapear iniciativas de vocabulários, glossários, dicionários, tesauros, ontologias e taxonomias de forma geral que já foram produzidas para o mesmo escopo ou que dialoguem de alguma maneira com o foco da ontologia que estamos desenvolvendo. O objetivo desse mapeamento é avaliar a possibilidade de reutilização de trabalhos anteriores e também a possibilidade de reutilização de padrões que podem facilitar e ampliar a interoperabilidade entre soluções já existentes, ampliando assim o potencial de conectividade no espaço informacional da ontologia.

3.	Identificar, escolher e definir os termos
A partir do mapeamento de diferentes fontes de informação e da possibilidade de reutilização de trabalhos anteriores, nesta etapa partimos para a priorização e escolha efetiva dentre todos os termos candidatos de quais serão efetivamente levados em consideração pela ontologia e que serão os elementos estruturantes da representação da informação e conhecimento a que a ontologia se propõe. Termos acabam sendo descartados, termos podem ser priorizados e termos novos podem surgir, sendo aqui uma etapa de intenso trabalho colaborativo, diálogo e participação. É também nessa etapa que os termos escolhidos precisam ser definidos, constituindo uma descrição mínima do seu significado. 

4.	Definir as classes e seus relacionamentos
Uma vez que temos os termos que farão parte da ontologia definidos, chega o momento nessa etapa de definir quais são as classes, as subclasses e a forma como elas devem se relacionar entre si. Esse trabalho visa ampliar a estrutura de organização da informação da ontologia, procurando organizar os termos em redes que definam a visão de relacionamento entre eles que o grupo de pessoas que desenvolve a ontologia possui. Aqui definimos que tipo de relacionamentos a ontologia deve atender, como eles devem ser expressos e quais relacionamentos que conectam determinadas classes por todo o espaço informacional da ontologia. 

5.	Definir as propriedades das classes
Nessa etapa definimos quais são as propriedades ou atributos de cada classe, entendendo que essas propriedades são parâmetros descritivos que ajudam a caracterizar o que é uma classe, do que ela é composta e quais são as informações básicas que devem ser preenchidas para definir uma classe existente no mundo das relações sociais que queremos representar. 

6.	Definir as facetas das propriedades
Para cada propriedade de classe que definimos na etapa anterior, devemos agora dizer como elas devem ser preenchidas, se devem utilizar algum tipo de vocabulário controlado (um conjunto de opções pré-determinadas), que restrições de preenchimento devem ser consideradas, padrões, formas e qualquer regulamentação ou indicação de boas práticas que devem ser levadas em consideração para definição das classes.  
7.	Criar instâncias
Por fim, nessa última etapa passamos a utilizar a ontologia criada para definir objetos do mundo social que queremos representar. É nesse momento, por exemplo, que vamos descrever um equipamento cultural específico, preenchendo todos as propriedades que definem esse equipamento cultural, visualizando as relações que ele mantém com outras classes e entendendo o uso prático da ontologia com os objetos da cultura que conhecemos em nossas vidas cotidianas. 


## Núcleo do modelo (diagrama)
## Referências Externas do Modelo
## Modelo Completo (diagrama)

## Modelo Conceitual
### Escopo
Trata-se de uma ontologia para gestão da cultura, com o objetivo de apoiar na resolução de outras questões que têm preocupado a área da cultura, como criação da conta satélite da cultura e qualificação da gestão cultural. O GT fez uma reflexão mais ampla em relação ao escopo, e chegou-se a um consenso de se tratar de uma ontologia para a política pública da cultura, entendendo que uma das missões do SNC, do SNIIC, e do próprio MinC, é orientar e qualificar a gestão cultural no Brasil.

Os objetivos da ontologia propostos pelos participantes visam a integração e interoperabilidade de sistemas de informação atualmente em uso, facilitar acompanhar e monitorar o Sistema Nacional de Cultura em suas diferentes facetas, determinar a estrutura informacional daquilo que deve ser reconhecido como elementos de valor para organização do MinC e facilitar a integração entre diferentes instâncias federativas. 

### Não-escopo


### Perguntas-requisito
•	Auxiliar a busca de informações pelos parceiros do MINC?
•	Auxiliar processes de definição de arquitetura da informação?
•	Visualizar o SNC
•	Estruturação
•	Dinâmicas
•	Recursos
•	Reforços 
•	Auxiliar nos processos de conexão da gestão cultural (Priv./Pub. – Pub./Pub. Etc...)
•	Auxiliar na apropriação da gestão cultural pela sociedade?
•	Auxiliar o monitoramento/avaliação da gestão cultural?
•	Auxiliar na consolidação do SNIIC?
•	Auxiliar definições semânticas mais precisas no âmbito da GC?
•	Ser um manual (de apresentação) da cultura brasileira?
•	Auxiliar processos de formação de gestores culturais?
•	Identificar agentes/ações culturais em diferentes níveis?
•	Classificar dados/indicadores do PNC?
•	Ampliar conexões setoriais e intersetoriais?
•	Avaliar impactos econômicos/sociais da gestão cultural?
•	Viabilizar a transparência e o controle social?
•	Difundir/mobilizar no sentido de universalizar direitos culturais?
•	Caracterizar elementos da gestão cultural (agentes, instituições, instrumentos, equipamentos, fontes de informação, públicos, serviços, manifestações).
•	Promover a inteligibilidade?
•	Promover ações sistêmicas?  (Diálogos entre subjetividade do campo cultural e objetividade da GC?)
•	Ajuda a preservar a memória cultural?
•	Pode mapear as atividades do MINC para aux. Na elaboração de um plano de classificação de documentos?
•	Relacionar/comparar editais culturais?

### Conceitos
#### Ação
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


#### Agente
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

#### Espaço cultural
> Lugares, fixos ou móveis/itinerantes, virtuais ou físicos, onde ocorrem ações culturais.

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


#### Instrumento
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
  

#### Público
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


## Referências
As referências são relativas a pesquisa realizada em janeiro de 2016 na base de dados Scopus com o termo de busca "collaborative ontology development". A pesquisa visava identificar, para o início do trabalho de modelagem da ontologia, experiências e propostas metodológicas que já tinham passado pelo processo de desenvolvimento de uma ontologia de forma colaborativa. Esses textos foram estudados pela equipe de mediação do projeto e serviram de base para o trabalho desenvolvido e apresentado acima.

1.	D. Bagni, M. Cappella, M. Pazienza, and A. Stellato. “Congas: A collaborative ontology development framework based on named graphs”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5883 LNAI, pp. 42-51, 2009.

2.	F. Bai and J. Ziegler. “Exchanging knowledge in concise bounded descriptions an approach to support collaborative ontology development in a distributed environment”. pp. 491-500, 2009. 

3.	J. Bao, Z. Hu, D. Caragea, J. Reecy, and V. Honavar. “A tool for collaborative construction of large biological ontologie”. pp. 191-195, 2006.

4.	Y. Chen, X. Peng, and W. Zhao. “An approach to detect collaborative conflicts for ontology development”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5446, pp. 442-454, 2009. 

5.	J. Dall'Agnol, C. Tacla, A. Freddo, A. Molinari, and E. Paraiso. “The use of well-founded argumentation on the conceptual modeling of collaborative ontology development”. pp. 200”207, 2011. 

6.	X. Du, M. Li, H. Hu, W. Ma, G. Qin, and W. Wu. “Construction of economics knowledge grid”. Huazhong Keji Daxue Xuebao (Ziran Kexue Ban)/Journal of Huazhong University of Science and Technology (Na- tural Science Edition). vol. 34, no. SUPPL., pp. 17”20, 2006.  

7.	S. Falconer, T. Tudorache, and N. Noy. “An analysis of collaborative patterns in large-scale ontology development projects”. pp. 25-31, 2011.

8.	J. Frankowski, P. Rubach, and E. Szczekocka. “Collaborative ontology development in real telecom environment”. pp. 40-53, 2007. 

9.	D. Gruen, J. Rasmussen, J. Liu, S. Hupfer, and S. Ross. “Collaborative reasoning and collaborative ontology development in craft”. Vol. SS-08- 07, pp. 51-58, 2008. 

10.	J. Hauagge Dall Agnol and C. Tacla. “A method for collaborative argumentation in merging individual ontologies”. Journal of Universal Computer Science. vol. 19, no. 12, pp. 1808-1833, 2013. 

11.	J. Henke. “Towards a usable group editor for ontologies”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 4273 LNCS, pp. 978”979, 2006. 

12.	T. Inniss, J. Lee, M. Light, M. Grassi, G. Thomas, and A. Williams. “Towards applying text mining and natural language processing for biomedical ontology acquisition”. pp. 7-14, 2006.
13.	R. Kalbasi, A. Alesheikh, and S. Amanzadeh. “Delving into knowledge modeling software supporting collaborative ontology development”. International Review on Computers and Software. vol. 7, no. 5, pp. 2045-2053, 2012. 

14.	R. Kalbasi, K. Janowicz, F. Reitsma, L. Boerboom, and A. Alesheikh. “Collaborative ontology development for the geosciences”. Transactions in GIS. vol. 18, no. 6, pp. 834-851, 2014. . 

15.	M. Li, D. Wang, X. Du, and S. Wang. “Ontology construction for semantic web: A role-based collaborative development method”. vol. 3399, pp. 609”619, 2005.

16.	M. Loskyll, D. Heckmann, and I. Kobayashi. “Ubiseditor 3.0: Collaborative ontology development on the web”. vol. 467, 2009. 

17.	J. Mace, S. Parkin, and A. Van Moorsel. “A collaborative ontology development tool for information security managers”. 2010. 

18.	G. Mangione, E. Mazzoni, F. Orciuoli, and A. Pierri. “A pedagogical approach for collaborative ontologies building”. Studies in Computational Intelligence. vol. 350, pp. 135-166, 2011. 

19.	“The semantic web, iswc 2002 - first international semantic web conference, proceedings”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 2342. LNCS, 2002. 

20.	“1st international semantic web conference, iswc 2002”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 2342, pp. 1”474, 2002. 

21.	“1st international working conference on business process and services computing, bpsc 2007”. 2007.  

22.	”Symbiotic relationships between semantic web and knowledge engineering - papers from the aaai spring symposium, technical report”. Vol. SS-08-07, 2008. 

23.	“The semanticweb - 3rd asian semanticweb conference, aswc 2008, proceedings”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5367 LNCS, 2008.

24.	“The sementic web - iswc 2008 - 7th international semantic web conference, iswc 2008, proceedings”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5318 LNCS, 2008.  

25.	“Sw2 2009 - proceedings of the workshop on web 3.0: Merging semantic web and social web”. vol. 467, 2009.  

26.	“Proceedings of the international symposium on matching and meaning automated development, evolution and interpretation of ontologies – a symposium at the aisb 2010 convention”. 2010.  

27.	“Symposium on computer human interaction for management of information technology, chimit 2010,” 2010.  

28.	“Acm international conference proceeding series”. vol. 02-04-September- 2015, 2015.  

29.	A. Norta, R. Yangarber, and L. Carlson. “Utility evaluation of tools for collaborative development and maintenance of ontologies”. pp. 207”214, 2010. .

30.	N. Noy and T. Tudorache. “Collaborative ontology development on the (semantic) web”. Vol. SS-08-07, pp. 63”68, 2008. . 

31.	M. Oprea. “On the design of a collaborative ontology development methodology for educational systems”. vol. 02-04-September-2015, 2015. 

32.	R. Palma, P. Haase, O. Corcho, A. Gómez-Pérez, and Q. Ji. “An editorial workflow approach for collaborative ontology development”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5367 LNCS, pp. 227-241, 2008. .

33.	R. Palma, O. Corcho, A. Gómez-Pérez, and P. Haase. “A holistic approach to collaborative ontology development based on change management”. Journal of Web Semantics. vol. 9, no. 3, pp. 299-314, 2011.
 
34.	T. Redmond, M. Smith, N. Drummond, and T. Tudorache. “Managing change: An ontology version control system”. vol. 432, 2009. 

35.	M. Rospocher, T. Tudorache, and M. Musen. “Investigating collaboration dynamics in different ontology development environments”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 8793, pp. 302-313, 2014. 

36.	J. Sachs and T. Finin. “Social and semantic computing in support of citizen science”. vol. 774, pp. 46-51, 2011.  

37.	G. Santipantakis and G. Vouros. “Semantics based reconciliaton for collaborative ontology evolution”. pp. 153-158, 2009.  

38.	A. Sebastian, N. Noy, T. Tudorache, and M. Musen. “A generic ontology for collaborative ontology-development workflows”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5268 LNAI, pp. 318”328, 2008.

39.	D. Settas, G. Meditskos, N. Bassiliades, and I. Stamelos. “Detecting antipatterns using a web-based collaborative antipattern ontology knowledge base”. Lecture Notes in Business Information Processing. vol. 83 LNBIP, pp. 478”488, 2011.  

40.	X. Shixiong, D. Zhiwen, Z. Lei, and Y. Guan. “Research on collaborative ontology development method based on lock granularity”. vol. 1, pp. 374”378, 2008.  

41.	C. Sousa, A. Soares, C. Pereira, and S. Moniz. “Establishing conceptual commitments in the development of ontologies through competency questions and conceptual graphs”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 8842, pp. 626-635, 2014.  

42.	Y. Sure, M. Erdmann, J. Angele, S. Staab, R. Studer, and D. Wenke. “Ontoedit: Collaborative ontology development for the semantic web”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 2342 LNCS, pp. 221-235, 2002.
 
43.	E. Tonkin, H. Pfeiffer, and A. Hewson. “An evidence-based approach to collaborative ontology development”. pp. 39-41, 2010.  

44.	E. Toppano. “A communication-based model of ontology design and (re)use”. 2010.  

45.	T. Tudorache, N. Noy, S. Tu, and M. Musen. “Supporting collaborative ontology development in protégé”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 5318 LNCS, pp. 17-32, 2008.

46.	T. Tudorache, N. Noy, S. Falconer, and M. Musen. “A knowledge base driven user interface for collaborative ontology development,” pp. 411”414, 2011. . 

47.	A. Valo, E. Hyvönen, and V. Komulainen. “A tool for collaborative ontology development for the semantic web”. pp. 209-212, 2005. 

48.	A. Walter and G. Nagypál. “Imagenotion: Methodology, tool support and evaluation”. Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). vol. 4803 LNCS, no. PART 1, pp. 1007-1024, 2007. 

49.	J. Wang, L. Xu, Z. Deng, and L. Zhang, “A collaborative ontology developing method based on ripple-effect”. pp. 131-134, 2010. 

50.	G.-J. Xian and R.-X. Zhao, “A review and prospects on collaborative ontology editing tools”. Journal of Integrative Agriculture. vol. 11, no. 5, pp. 731-740, 2012.

51.	T. Yang, Y.Wu, X. Peng, and W. Zhao “Fine-grained configuration management for collaborative ontology development”. pp. 230-238, 2011. 

52.	M. Yoder, I. Mikó, K. Seltmann, M. Bertone, and A. Deans. “A gross anatomy ontology for hymenoptera”. PLoS ONE. vol. 5, no. 12, 2010.

53.	N. Zaini and H. Omar. “An online system to support collaborative knowledge acquisition for ontology development”. pp. 543-548, 2011. 


