# HypoHeat
Tema do projeto: Especificar e construir uma aplicação web que permita aos usuários acessar a área queimada, 
risco de fogo e focos de calor do Programa Queimadas do INPE 

## Descrição 📝

**Objetivo do projeto é especificar e desenvolver uma aplicação web interativa que permita aos usuários consultar e visualizar de forma intuitiva os dados de área queimada, risco de fogo e focos de calor, obtidos diretamente da base de dados BDQueimadas do Programa Queimadas do INPE.**

## Link para o Trello 📒

Clique [aqui](https://trello.com/invite/b/67b50de51e4b4f5c15bd32dd/ATTI9b7a19e1d1e239837b54b56c8c758ef20CB9B9E4/hypoheat) para acessar o quadro do Trello do projeto

## Link para o Figma 🖼️

Clique [aqui](https://www.figma.com/design/GD5tvYECJTti4SODi0g0xC/HypoHeat?node-id=0-1&t=8QAw5FUGv43DtDRS-1) para acessar o protótipo do projeto

## SPRINTS 📊

| SPRINT | LINK          | INÍCIO     | ENTREGA    | STATUS        |
| ------ | ------------- | ---------- | ---------- | ------------- |
| 01     | [Sprint 01]() | 24/03/2025 | 17/04/2025 | Concluída |
| 02     | [Sprint 02]() | 22/04/2025 | 15/05/2025 | Concluída     |
| 03     | [Sprint 03]() | 16/05/2025 | 10/06/2025 |  Pendente     |

## USER STORIES 🧾

<br>

| ID REFERÊNCIA | Remetente | Instrução                                                                                           | Finalidade                                                                                                                          |
| ------------- | --------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| RF-01         | Usuário   | Como usuário do sistema, quero filtrar os focos de calor por estado.                             | Para entender melhor as queimadas e tomar decisões.                                                |
| RF-02 | Usuário   |  Como usuário do sistema, eu quero visualizar e filtrar as incidências de focos de calor por bioma.                 |  Para entender quais biomas são mais impactados pelas queimadas e fazer análises específicas. |
| RF-03 | Usuário   | Como um usuário do sistema, quero poder visualizar o risco de fogo por estado.                                 | Para entender quais estados apresentam maior ou menor risco de fogo, e tomar decisões baseadas nesses dados. |
| RF-04  | Usuário |  Como um usuário do sistema, quero visualizar o risco de fogo por bioma, com base na média do risco total para cada bioma.              |  Para saber quais biomas têm maior ou menor risco de fogo.                     |
| RF-05  | Usuário   |  Como um usuário do sistema, quero visualizar a área queimada por estado.     | Para entender o impacto das queimadas em cada região.               |
| RF-06  | Usuário   |  Como um usuário do sistema, quero visualizar a área queimada por bioma. |  Para entender o impacto das queimadas em diferentes ecossistemas.                                                                              |
| RF-07    | Usuário   |  Como um usuário do sistema,  quero visualizar gráficos que mostrem a distribuição dos focos de calor por estado e por bioma.        |  Para analisar a intensidade e a frequência dos incêndios em diferentes regiões e ecossistema.   |
| RF-08     | Usuário   | Como um usuário do sistema, quero visualizar gráficos que mostrem o risco de fogo por estado e bioma.      |  Para analisar o grau de risco de fogo em diferentes regiões e ecossistemas.    |
| RF-09    | Usuário   |  Como um usuário do sistema, quero poder visualizar gráficos sobre a área queimada por estado e por bioma.     |   Para entender a extensão dos incêndios nas diferentes regiões e ecossistemas.       |
| RF-10   | Usuário   |   Como um usuário do sistema, quero visualizar os dados de focos de calor e queimadas em um intervalo de tempo específico.        |  Para os dados de forma mais focada, de acordo com o período de interesse.     |
| RF-11 | Usuário   |   Como um usuário do sistema, quero responder à pergunta "quais meses o risco de fogo é maior?" através de um gráfico.    |  Para identificar os períodos de maior risco de fogo e planejar ações de prevenção mais eficazes. |
| RF-12   | Usuário  | Como um usuário do sistema, quero responder à pergunta "O risco de fogo está associado a uma maior área queimada?" através de um gráfico.  | Para entender se existe uma relação direta entre o risco de fogo e a extensão das áreas queimadas. |
|               |           |                                                                                                     |

<br>
<br>


## Requisitos 📜

### Requisitos Funcionais

- **RF.01** Focos de calor por estado; 
- **RF.02** Focos de calor por bioma;
- **RF.03** Risco de fogo por estado;
- **RF.04** Risco de fogo por bioma; 
- **RF.05** Área queimada por estado;
- **RF.06** Área queimada por bioma; 
- **RF.07** Gráficos de focos de calor por estado e bioma; 
- **RF.08** Gráficos de risco de fogo por estado e bioma; 
- **RF.09** Gráficos de área queimada por estado e bioma;
- **RF.10** Restringir as consultas por intervalo de tempo; 
- **RF.11** Permitir ao usuário responder a seguinte pergunta: quais meses o risco de fogo é maior;  
- **RF.12**  Permitir ao usuário responder a seguinte pergunta: o risco de fogo está associado a uma maior área queimada. 

### Requisitos Não Funcionais

- **RNF.01** Exibir os dados espaciais em mapas interativos; 
- **RNF.02** Exibir os resultados em gráficos interativos. 

# Sprints📈🏃🏻

## Sprint 1📈🏃🏻
A Sprint 1 teve como principal foco estabelecer as bases do desenvolvimento do projeto, com as seguintes atividades e objetivos principais:

- **Preparação do ambiente de desenvolvimento**:  
  Configuração e organização inicial do projeto, abrangendo as estruturas de backend e frontend, para garantir um fluxo de trabalho eficiente e bem estruturado.  

- **Definição da arquitetura do sistema**:  
  Criação de diagramas, como diagramas de classe e de caso de uso, para documentar e orientar o desenvolvimento da solução.  

- **Consistência e atualização dos dados**:  
  Garantia da inserção de dados atualizados no banco, extraídos diretamente do site do INPE (DBQueimadas), para assegurar a integridade e relevância das informações.  

- **Ajustes nas views e stored procedures**:  
  Validação e desenvolvimento de views e stored procedures, assegurando que atendam aos requisitos funcionais e estejam alinhadas às necessidades do projeto.  

- **Modelagem do banco de dados**:  
  Desenvolvimento e ajuste do banco de dados, preparado para atender às três formas de normalização, assegurando eficiência e consistência na gestão dos dados.  

### Backlog Sprint 1 📃
<br>

| ID  | Nome                                                 | Estimativa | Responsáveis                                  | Tarefa Finalizada | Link                                                                 | Requisitos atendidos                       |
|-----|------------------------------------------------------|------------|-----------------------------------------------|-------------------|----------------------------------------------------------------------|-------------------------------------------|
| 28  | Criar Estrutura do projeto                          | 3          | Gustavo de Moraes Silva                       |     ✔              | [Link](https://trello.com/c/IvkPGfbM/28-criar-estrutura-do-projeto) |                                           |
| 29  | Criar banco de dados no PostgreSQL                  | 3          | Andressa Stéphane Toledo da Silva             |  ✔               | [Link](https://trello.com/c/gD7hoYMQ/29-criar-banco-de-dados-no-postgree) |                                           |
| 30  | Criar Views das ocorrências                         | 3          | Carlos Magalhães e Eduardo Henrique Alves Arantes |  ✔                | [Link](https://trello.com/c/7SGbxWtc/30-criar-views-das-ocorrencias) | BDR.01, BDR.02, MC.03                     |
| 31  | Diagrama de caso de uso                             | 8          | Andressa Stéphane Toledo da Silva             |  ✔                 | [Link](https://trello.com/c/9cnVNH75/31-diagrama-de-caso-de-uso)    |                                           |
| 32  | Diagrama de Classe - Implementação em typescript         | 5          | Andressa Stéphane Toledo da Silva             | ✔                  | [Link]([https://trello.com/c/6lFmqUH8/32-diagrama-de-classe](https://trello.com/c/68msSWpP/60-diagrama-de-classe-implementa%C3%A7%C3%A3o-em-typescript))         | TP.01, TP.02, ED.01                       |
| 33  | Estrutura backend                                   | 13         | Gustavo de Moraes Silva                       |  ✔                 | [Link](https://trello.com/c/bwpfptVc/33-estrutura-backend)          |                                           |
| 36  | Criar Stored procedure para importar os dados do DBQueimadas | 8 | Adson Filho                                   |  ✔                 | [Link](https://trello.com/c/PNab7u8o/36-criar-stored-procedure-para-importar-os-dados-do-dbqueimadas) |        BDR.03                                   |
| 37  | Criar componente de filtro                          | 8          | Eduardo Henrique Alves Arantes                |  ✔                 | [Link](https://trello.com/c/7JXmcaEy/37-criar-componente-de-filtro) | RF.10                                     |
| 41  | Criar app.tsx                                       | 8          |  Gustavo de Moraes Silva                      |    ✔               | [Link](https://trello.com/c/AYtO8uQe/41-criar-apptsx)               |                                           |
| 42  | Protótipo do Figma                                  | 8          | Andressa Stéphane Toledo da Silva             |       ✔           | [Link](https://trello.com/c/8nX8z9Fk/42-prototipo-do-figma)         |                                           |
| 43  | Criar DER                                           | 3          | Andressa Stéphane Toledo da Silva             |  ✔                 | [Link](https://trello.com/c/cyS68Qbn/43-criar-der)                 |                                           |
| 53  | Rotina para rodar a stored procedure                | 5          | Carlos Magalhães                              |  ✔                 | [Link](https://trello.com/c/dGtnWzFy/53-rotina-para-rodar-a-stored-procedure) |                                           |
| 54  | Rotina para acessar site do INPE e realizar download do arquivo | 5 | Carlos Magalhães                            |  ✔                 | [Link](https://trello.com/c/luzmg0GV/54-rotina-para-acessar-site-do-inpe-e-realizar-download-do-arquivo) |                                           |
| 59  | Criar arquivo de inicialização do banco de dados    |    5        |  Carlos Magalhães                              |   ✔                | [Link](https://trello.com/c/eUqmJaN9/59-criar-arquivo-de-inicializacao-do-banco-de-dados) |                                           |


### Burndown Chart 🔥
<p align="center">
   <img width="687" height="353" src="https://github.com/user-attachments/assets/64cfbbc6-b36f-416f-bfec-998cb0fa0298">

</p>
<br>

### Backlog Sprint 2 📃

| ID  | Nome                                                             | Responsáveis                           | Tarefa Finalizada | Link                                                                                     | Requisitos atendidos |
|-----|------------------------------------------------------------------|----------------------------------------|-------------------|------------------------------------------------------------------------------------------|-----------------------|
| 32  | Diagrama de classe                                               | Andressa Stéphane Toledo da Silva     | ✔                 | [Link](https://trello.com/c/6lFmqUH8/32-diagrama-de-classe)                              |     ES.02                  |
| 47  | Trabalhar consulta de área queimada utilizando o PostGIS         | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/ma8TsiRd/47-trabalhar-consulta-de-%C3%A1rea-queimada-utilizando-o-postgis) |                       |
| 82  | Automatização da importação do shapefile                         | Gustavo de Moraes Silva               | ✔                 | [Link](https://trello.com/c/OdGdkT3e/82-automatiza%C3%A7%C3%A3o-da-importa%C3%A7%C3%A3o-do-shape-file) |                       |
| 70  | Criar identidade visual                                          | Andressa Stéphane Toledo da Silva     | ✔                 | [Link](https://trello.com/c/q3OUGmgm/70-criar-identidade-visual)                         |                       |
| 73  | Trabalhar consultas para trazer os focos de calor                | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/QUMzEAq7/73-trabalhar-consultas-para-trazer-os-focos-de-calor) |                       |
| 63  | Trabalhar consulta para identificar risco de fogo                | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/vYfbTOYk/63-trabalhar-consulta-para-identificar-risco-de-fogo) |                       |
| 79  | Trabalhar requisições no Controller e rotas para Focos de Calor  | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/rMa9hY3R/79-trabalhar-requisi%C3%A7%C3%B5es-no-controller-e-rotas-para-focos-de-calor) |                       |
| 74  | Trabalhar requisições nos controllers e rotas para Área Queimada | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/1Q8btLWb/74-trabalhar-requisi%C3%A7%C3%B5es-nos-controllers-e-rotas-para-area-queimada) |                       |
| 64  | Trabalhar requisições nos controllers e rotas para Risco de Fogo | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/I9epBNEi/64-trabalhar-requisi%C3%A7%C3%B5es-nos-controllers-e-rotas-para-risco-de-fogo) |                       |
| 81  | Criar View para Risco de Fogo                                    | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/0JqR7mvu/81-criar-view-para-risco-de-fogo)                  |                       |
| 80  | Criar View Área Queimada                                         | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/a7vxZ5l2/80-criar-view-area-queimada)                       |                       |
| 84  | Definições Matemáticas (enumerativas, recursivas, etc.)                                         | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/lOAIP6nn/84-defini%C3%A7%C3%B5es-matem%C3%A1ticas-enumerativas-recursivas-etc)                       |     MC.01                  |
| 83  | Análise e otimização de algoritmos                                         | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/eLRrLVkL/83-an%C3%A1lise-e-otimiza%C3%A7%C3%A3o-de-algoritmos)                       |      ED.08                 |


### Burndown Chart 🔥
<p align="center">
   <img width="687" height="353" src="https://github.com/user-attachments/assets/17c056a0-688c-4c21-91b2-e5ea4c0ecd3d">

</p>
<br>



### Backlog Sprint 3 📃

| ID  | Nome                                                             | Responsáveis                           | Tarefa Finalizada | Link                                                                                     | Requisitos atendidos |
|-----|------------------------------------------------------------------|----------------------------------------|-------------------|------------------------------------------------------------------------------------------|-----------------------|
| 73  | Trabalhar consultas para trazer os focos de calor                                               | Carlos Magalhães      | ✔                 | [Link](https://trello.com/c/QUMzEAq7/73-trabalhar-consultas-para-trazer-os-focos-de-calor)                              |                       |
| 13  | Componente de gráfico - focos de calor por estado e bioma         | Andressa Stéphane Toledo da Silva                       | ✔                 | [Link](https://trello.com/c/5qU6fzXU/13-componente-de-gr%C3%A1fico-focos-de-calor-por-estado-e-bioma) |      RFN02                 |
| 76  | Componente Mapa - Focos de Calor                       | Carlos Magalhães              | ✔                 | [Link](https://trello.com/c/SKEC2Pgc/76-componente-mapa-focos-de-calor) |          RF01, RF02, RF07, RFN01 , RF11, RF12  |
| 79  | Trabalhar requisições no Controller e rotas para Focos de Calor                                          |  Carlos Magalhães     | ✔                 | [Link](https://trello.com/c/rMa9hY3R/79-trabalhar-requisi%C3%A7%C3%B5es-no-controller-e-rotas-para-focos-de-calor)                         |                       |
| 14  | Componente gráfico - Risco de Fogo por Estado e Bioma                | Andressa Stéphane Toledo da Silva                      | ✔                 | [Link](https://trello.com/c/NiitwVdo/14-componente-gr%C3%A1fico-risco-de-fogo-por-estado-e-bioma) |   RFN02, RF08                   |
| 69  | Trabalhar atualização do mapa a partir dos dados inseridos no filtro                | Adson Filho                    | ✔                 | [Link](https://trello.com/c/wAMgR8US/69-trabalhar-atualiza%C3%A7%C3%A3o-do-mapa-a-partir-dos-dados-inseridos-no-filtro) |                       |
| 77  | Componente Mapa - Área Queimada  | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/35E1of6p/77-componente-mapa-area-queimada) |       RF05, RF06, RFN01  ,RF11, RF12              |
| 78  | Componente Mapa - Risco de Fogo | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/ajwLsHbC/78-componente-mapa-risco-de-fogo) |          RFN01 ,RF11, RF12             |
| 85  | Ajustar bug da importação de ocorrências | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/v6m4bmwr/85-ajustar-bug-da-importa%C3%A7%C3%A3o-de-ocorr%C3%AAncias) |           RF03, RF04 , RF05, RF06           |
| 86  | Trabalhar consulta de área queimada para o mapa, validar valores duplicados e melhorar a performance                                    | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/ZlTLL12H/86-trabalhar-consulta-de-%C3%A1rea-queimada-para-o-mapa-validar-valores-duplicados-e-melhorar-a-performance)                  |                       |
| 87  | Trabalhar mapa de calor                                       | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/g6pPdwCC/87-trabalhar-mapa-de-calor)                       |                       |
| 88  | Trabalhar consultas para agrupar informações para os gráficos                                         | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/ySqOdzJK/88-trabalhar-consultas-para-agrupar-informa%C3%A7%C3%B5es-para-os-gr%C3%A1ficos)                       |                       |
| 89  | Mudar a cor do mapa para o padrão do projeto                                       | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/ZN3sHTAu/89-mudar-a-cor-do-mapa-para-o-padr%C3%A3o-do-projeto)      |                       |
| 90  | Adicionar camada do bioma/Estado na consulta de área queimada | Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/IEFwn9yt/90-adicionar-camada-do-bioma-estado-na-consulta-de-%C3%A1rea-queimada) |                       |
| 91  | Ajustar importação para que todas as descrições fiquem UPPERCASE()| Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/RjbVKgfr/91-ajustar-importa%C3%A7%C3%A3o-para-que-todas-as-descri%C3%A7%C3%B5es-fiquem-uppercase) |                       |
| 92  | Apresentar o mapa e o gráfico vazio, quando não houver filtros                                    |  Andressa Stéphane Toledo da Silva                      | ✔                 | [Link](https://trello.com/c/KKl01z2d/92-apresentar-o-mapa-e-o-gr%C3%A1fico-vazio-quando-n%C3%A3o-houver-filtros)                  |                       |
| 93  | Trabalhar popup que aparece ao clicar no ponto do mapa                                       | Andressa Stéphane Toledo da Silva                      | ✔                 | [Link](https://trello.com/c/95Fa0AHt/93-trabalhar-popup-que-aparece-ao-clicar-no-ponto-do-mapa)                       |                       |
| 95  | Trabalhar gráfico para focos de calor                                        | Andressa Stéphane Toledo da Silva                       | ✔                 | [Link](https://trello.com/c/xcxhw6r2/95-trabalhar-gr%C3%A1fico-para-focos-de-calor)                       |                       |
| 96  | Trabalhar gráfico para risco de fogo                                   | Andressa Stéphane Toledo da Silva                       | ✔                 | [Link](https://trello.com/c/PwOJVm6j/96-trabalhar-gr%C3%A1fico-para-risco-de-fogo)      |                       |
| 97  | Trabalhar gráfico para área queimada | Andressa Stéphane Toledo da Silva                       | ✔                 | [Link](https://trello.com/c/AO7fahug/97-trabalhar-gr%C3%A1fico-para-%C3%A1rea-queimada) |    RF05, RF06                   |
| 99  | Banco de dados:  Converter functions de área queimada e área queimada percentual para stored procedure| Carlos Magalhães                       | ✔                 | [Link](https://trello.com/c/r2izZSHT/99-banco-de-dados-converter-functions-de-%C3%A1rea-queimada-e-%C3%A1rea-queimada-percentual-para-stored-procedure) |                       |
| 100  | Matemática para computação - MC.04: Relações e suas aplicações -> conceito de projeção, seleção e predicado (SELECT) |  Carlos Magalhães                      | ✔                 | [Link](https://trello.com/c/rL57zixY/100-matem%C3%A1tica-para-computa%C3%A7%C3%A3o-mc04-rela%C3%A7%C3%B5es-e-suas-aplica%C3%A7%C3%B5es-conceito-de-proje%C3%A7%C3%A3o-sele%C3%A7%C3%A3o-e-predicado-select)                  |        MC.04               |
| 101  |  Estruturas de - dados - ED.05: Algoritmos de busca em cadeias de caracteres -> Adicionar a opção do usuário digitar o nome do Estado e do bioma que ele deseja buscar, além de deixá-lo selecionar                                    | Eduardo Henrique                      | ✔                 | [Link](https://trello.com/c/2VXaAR8R/101-estruturas-de-dados-ed05-algoritmos-de-busca-em-cadeias-de-caracteres-adicionar-a-op%C3%A7%C3%A3o-do-usu%C3%A1rio-digitar-o-nome-do-estado-e-do)                       |                 ED.05      |
| 102  | Engenharia de software Diagrama de sequência                                      | Adson Filho                     | ✔                 | [Link](https://trello.com/c/wjmnZ3LE/102-engenharia-de-software-diagrama-de-sequ%C3%AAncia)                       |             ES.03         |
| 104  | Ajustar inserção de risco de fogo                              | Gustavo de Moraes Silva                       | ✔                 | [Link](https://trello.com/c/h1gotDzh/104-ajustar-inser%C3%A7%C3%A3o-de-risco-de-fogo)      |                      |

### Burndown Chart 🔥
<p align="center">
   <img width="687" height="353" src="https://github.com/HypogramTechnologies/HypoHeat/blob/main/documentacao/Sprint%203/BurndownChart.png">

</p>
<br>

# EQUIPE 👨🏻‍💻

<br>

| NOME                              | FUNÇÃO        | GITHUB                                                    |
| --------------------------------- | ------------- | --------------------------------------------------------- |
| Gustavo de Moraes Silva           | Project Owner  | [guhms7](https://github.com/guhms7)                       |
| Carlos Eduardo Magalhaes         | Developer | [carlosedsmagalhaes](https://github.com/carlosedsmagalhaes) |
| Adson Ottoni Balbino Filho        | Developer     | [adsonfilho](https://github.com/adsonfilho)               |
| Andressa Stephane Toledo da Silva | Scrum Master     | [andressatoledo](https://github.com/andressatoledo)       |
| Eduardo Henrique Alves Arantes    | Developer     | [eduardohalves](https://github.com/eduardohalves)         |
|                                   |               |
