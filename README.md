# miniguia-estudos-notebooklm-pb
desafio para curso da DIO: treinando uma IA de aprendizagem
## Estrutura do desafio

1. Contexto e Objetivos
2. Curadoria de Fontes
3. Engenharia de Prompts e "Cicatrizes"
4. Miniguia de Estudo (Entrega Final):
   - Resumos estruturados do assunto;
    -  Um glossário com os principais conceitos aprendidos;
      -  Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema.

### 1. Contexto e objetivos
O desafio será baseado no entendimento de conceitos básicos e no funcionamento da ferramenta para o setor administrativo em uma organização.

#### Objetivos
1. Entender o que é o Power BI e para que serve dentro de uma organização

**O que é o Power BI?**
É uma ferramenta da Microsoft desenvolvida para *conectar* diferentes fontes de dados (como planilhas do Excel), *limpar e organizar* essas informações de forma simples ("low-code") e *transformá-las em relatórios visuais e interativos*

Dentro de uma organização, ele serve para implementar o Business Intelligence (BI), eliminando decisões baseadas em "achismos" e substituindo-as por escolhas fundamentadas em dados históricos e atuais. Isso ajuda a responder de forma rápida o que está acontecendo no negócio, por que aconteceu, o que acontecerá a seguir e como melhorar os resultados.

**3 conceitos fundamentais organizam-se na seguinte ordem lógica de aprendizado:**
- **Preparação de dados:** O ponto de partida que consiste em conectar, compilar e transformar as tabelas brutas para que fiquem prontas para análise.
- **Modelagem e relacionamentos:** A integração de tabelas diferentes por meio de campos em comum. O conceito central é o relacionamento de "1 para muitos", onde um único registro de uma tabela (como um vendedor) se conecta a múltiplos registros em outra (como as várias vendas feitas por ele).
- **Visualizações e relatórios:** A criação de painéis visuais interativos na exibição de Relatório, utilizando elementos como gráficos de barras, de pizza e cartões de destaque. Um bom painel deve ser limpo e focado, facilitando o consumo ágil e a exploração das informações.

2. Compreender a diferença entre Power BI Desktop e Power BI Service

As principais diferenças entre o Power BI Desktop e o Serviço do Power BI (Power BI Service) envolvem o local de execução, o modelo de instalação e a etapa do fluxo de trabalho em que cada um é utilizado:

- **Instalação e ambiente de uso:** O Power BI Desktop é um aplicativo gratuito instalado diretamente no computador local do usuário para a realização de consultas e análises locais. O Serviço do Power BI funciona como a plataforma de destino para onde os trabalhos desenvolvidos no computador são enviados.
- **Criação e modelagem (Desktop):** O Power BI Desktop é o ambiente onde ocorre a fase de desenvolvimento, sendo utilizado para se conectar a várias fontes de dados distintas, transformar essas informações, construir o modelo de dados e criar os visuais e relatórios.
- **Compartilhamento e distribuição (Serviço):** Enquanto o Desktop é voltado para a construção dos relatórios, o Serviço do Power BI é a ferramenta utilizada para compartilhar e distribuir esses relatórios prontos com outras pessoas dentro da organização

3. Aprender os conceitos de modelagem de dados (tabelas fato/dimensão, relacionamentos)

**O que é a Modelagem de dados?**
Na prática, ao carregar diferentes tabelas para o Power BI Desktop, a modelagem estabelece a estrutura lógica invisível que diz como uma tabela se conecta e conversa com a outra. É por meio dessa estrutura que a ferramenta consegue cruzar informações de arquivos distintos dentro de um mesmo gráfico ou relatório.

A estrutura e a importância da diferenciação entre as tabelas resumem-se em:
- **Tabelas de Origem (Cadastro / Dimensão):** Armazenam dados cadastrais fixos e contextuais com registros únicos, como as listas de produtos e de vendedores.
- **Tabela de Destino (Movimentação / Fato):** Registra o histórico de transações e acontecimentos do negócio, onde os códigos de produtos e vendedores se repetem a cada nova operação.
- **Importância da Estrutura:** Essa organização é fundamental para criar relacionamentos do tipo "1 para muitos" (1:*), corrigir ou evitar relacionamentos automáticos incorretos criados pela ferramenta e garantir a precisão matemática nos cálculos e no cruzamento de dados nos relatórios visuais

5. Saber o fluxo básico: conectar dados > transformar (Power Query) > visualizar > publicar

Esse processo é composto por *6 etapas* sequenciais:
- **Conectar-se aos dados:** A atividade começa no Power BI Desktop ao importar as tabelas das fontes necessárias — tais como pastas de trabalho do Excel, bancos de dados ou páginas da Web.
- **Transformar dados:** Utiliza-se o Editor do Power Query (integrado ao Power BI Desktop) para limpar e moldar as informações, executando tarefas como remoção de colunas inúteis, filtragem de linhas e ajuste no tipo de dados dos campos.
- **Modelar dados:** Ainda no Power BI Desktop, estabelecem-se os relacionamentos entre as tabelas (como a relação de "1 para muitos") e criam-se cálculos para estender e estruturar o modelo semântico.
- **Criar visualizações e relatórios:** Monta-se a interface visual adicionando gráficos (como barras e pizza), tabelas e cartões de destaque nas páginas do relatório, aproveitando a interatividade automática entre os visuais.
- **Publicar o relatório:** Após concluir a criação no aplicativo do computador, o relatório é salvo e publicado diretamente no Serviço do Power BI (plataforma online).
- **Distribuir e gerenciar relatórios:** Dentro do Serviço do Power BI, os relatórios são organizados em espaços de trabalho (workspaces) e podem ser transformados em painéis ou aplicativos para compartilhamento e consumo seguro pelos gestores e colegas da empresa.

### 2. Curadoria de Fontes 

- [Noções básicas do serviço do Power BI](https://learn.microsoft.com/pt-br/power-bi/fundamentals/service-basic-concepts): conceitos e termos (workspaces, relatórios, dashboards, modelos semânticos) 
- [Introdução ao Power BI Desktop](https://learn.microsoft.com/pt-br/power-bi/fundamentals/desktop-getting-started): tutorial do primeiro relatório 
- [Comece a criar com o Power BI](https://learn.microsoft.com/pt-br/training/modules/get-started-with-power-bi/): módulo introdutório oficial 
- [Curso básico de Microsoft Power BI Desktop](https://www.projetoinclusaodigital.com.br/apostilas/powerbi/Curso-Basico-PowerBI.pdf): linguagem simples, focado em iniciantes 

### 3. Engenharia de Prompts e "Cicatrizes"

*3.1 Prompts de mapeamento geral:*
- Com base nos documentos carregados, liste e explique 3 conceitos fundamentais sobre Power BI que aparecem repetidamente entre as fontes. Organize em ordem lógica de aprendizado, do mais básico ao mais avançado. Explique de uma forma prática como a ferramenta serve dentro de uma organização.
- Quais são as principais diferenças entre Power BI Desktop e Power BI Service, segundo as fontes?

*3.2 Prompts de aprofundamento conceitual:*
- Explique, com base nas fontes, o que é modelagem de dados no Power BI e por que a distinção entre tabela fato e tabela dimensão é importante.
- Segundo os documentos, quais são as etapas do fluxo de trabalho típico no Power BI, desde conectar a uma fonte de dados até publicar um relatório?

*3.3 Prompts de checagem e comparação entre fontes:*
- Existe algum conceito mencionado em uma fonte mas não nas outras? Liste essas divergências.

*3.4 Prompts para gerar o glossário:*
- Crie um glossário com os 10 termos técnicos mais importantes sobre Power BI encontrados nos documentos. Para cada termo, dê uma definição de uma frase, em linguagem simples.

*3.5 Prompts para simular aplicação prática:*
- Imagine que sou auxiliar administrativo e nunca usei Power BI. Com base nas fontes, explique como eu usaria essa ferramenta no meu dia a dia de trabalho, com um exemplo prático simples.

### 4. Miniguia de Estudo (Entrega Final)

*4.1 Resumos estruturados do assunto*

**1. O que é e para que serve o Power BI?**
- *O que é:* O Microsoft Power BI é uma solução completa de análise e relatórios que engloba ferramentas para preparação, visualização, distribuição e gerenciamento de dados.
- *Para que serve:* A ferramenta permite conectar-se a diversas fontes de informações (como planilhas de Excel ou bancos de dados) e combiná-las para criar painéis e relatórios visuais interativos
- *Impacto nas organizações:* Seu principal objetivo é substituir a tomada de decisões baseada em "achismos" ou sentimentos por escolhas fundamentadas em dados reais e históricos. Ele ajuda as empresas a entenderem o cenário atual, identificarem tendências e ajustarem estratégias para alcançar metas.

**2. Principais Componentes do Power BI**
Power BI é composto por três ferramentas principais que trabalham de forma integrada:
- *Power BI Desktop:* Aplicativo gratuito para computador Windows voltado para criadores de relatórios e analistas. É o ambiente onde você conecta os dados, realiza limpezas, constrói a modelagem e projeta os gráficos.
- *Serviço do Power BI (Power BI Service):* Plataforma online baseada na nuvem utilizada para publicar, organizar em espaços de trabalho (workspaces), criar painéis (dashboards) e compartilhar os relatórios com colegas de trabalho de forma segura.

**3. Fluxo de Trabalho Típico:**
O desenvolvimento de uma análise no Power BI segue seis etapas sequenciais:
- *Conectar aos dados:* Importar informações de uma ou mais origens (como planilhas do Excel ou páginas da Web) dentro do Power BI Desktop.
- *Transformar dados:* Utilizar o Editor do Power Query (embutido no Desktop) para limpar os dados — removendo colunas desnecessárias, filtrando linhas e ajustando o tipo das informações (como texto ou número).
- *Modelar dados:* Conectar as tabelas entre si e criar cálculos para estruturar o modelo semântico.
- *Criar visualizações:* Adicionar e organizar elementos visuais (gráficos de barras, pizza, tabelas e cartões) nas páginas do relatório.
- *Publicar o relatório:* Enviar o projeto finalizado do aplicativo de computador para o Serviço do Power BI na nuvem.
- *Distribuir e gerenciar:* Organizar o conteúdo online em espaços de trabalho e compartilhá-lo com os usuários finais na organização.

**4. Conceitos-chave de Modelagem de Dados**
- *Modelo Semântico (Conjunto de Dados):* É o contêiner unificado no Power BI que reúne as conexões de dados, as regras de limpeza, os relacionamentos e os cálculos realizados.
- *Tabelas de Origem vs. Tabela de Destino:*
  - Origem (Cadastro/Dimensão): Tabelas que contêm informações de cadastro fixas com registros únicos (por exemplo, uma lista de Produtos ou Vendedores, onde cada código aparece apenas uma vez).
  - Destino (Movimentação/Fato): Tabela que registra os acontecimentos do negócio (por exemplo, a tabela de Vendas), onde os códigos de produtos e vendedores se repetem diversas vezes ao longo do tempo.
- *Relacionamento "1 para muitos" (1:*):* É a conexão padrão mais importante da modelagem. Ela liga um registro único da tabela de origem (1) a múltiplos registros correspondentes na tabela de destino (*) — permitindo, por exemplo, que o cadastro de um único vendedor filtre todas as vendas realizadas por ele.
- *Interatividade Visual:* A capacidade automática do relatório de fazer com que a seleção de um elemento em um gráfico filtre instantaneamente todos os outros gráficos e cartões presentes na mesma tela.

*4.2 Glossário com os principais conceitos aprendidos*

**1. Power BI Desktop:** É o aplicativo gratuito para computador utilizado para conectar a diferentes fontes de dados, realizar limpezas, criar o modelo de dados e construir os relatórios visuais.

**2. Serviço do Power BI (Power BI Service):** É a plataforma online baseada na nuvem onde os relatórios criados no computador são publicados, organizados e compartilhados de forma segura com a organização.

**3. Power Query:** É o editor integrado ao Power BI Desktop utilizado para conectar, limpar, filtrar e transformar os dados brutos antes que eles sejam carregados na análise.

**4. Modelo Semântico (Modelo de Dados):** É o contêiner de dados unificado que reúne as conexões de diferentes fontes, as regras de limpeza, os cálculos e os relacionamentos entre tabelas.

**5. Relacionamento ("1 para muitos"):** É a conexão lógica do modelo de dados onde um registro único de uma tabela de cadastro (origem) associa-se a múltiplos registros correspondentes em uma tabela de movimentações (destino).

**6. Visualização (Visual):** É o elemento gráfico interativo — como gráficos de barras, pizza,tabelas e cartões — adicionado às páginas para representar os dados de maneira fácil de entende.

**7. Relatório:** É o documento composto por uma ou mais páginas contendo gráficos e visuais interativos baseados em um único modelo semântico para analisar áreas de interesse do negócio.

**8. Dashboard (Painel):** É uma tela única e consolidada contendo blocos de elementos visuais e métricas importantes para monitorar o desempenho e os objetivos da empresa de forma rápida.

**9. Espaço de Trabalho (Workspace):** É a área colaborativa dentro do Serviço do Power BI onde os criadores armazenam, gerenciam e organizam coleções de relatórios, painéis e modelos semânticos.

**10. Aplicativo (App):** É o pacote simplificado que reúne relatórios e painéis de um espaço de trabalho para distribuir e compartilhar conteúdo com grandes públicos ou equipes da organização.
  
*4.3 Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema*
- Faça um teste de 5 perguntas de múltipla escolha sobre os conceitos básicos de Power BI abordados nos documentos, para eu revisar o que aprendi.
- Resuma em 3 frases o que é Power BI e por que ele é usado, como se estivesse explicando para alguém em uma entrevista de emprego.
- Compare o que eu já sabia sobre Power BI (cite seus conhecimentos prévios, ex: Noções de SQL) com os conceitos novos apresentados nas fontes, e identifique onde há sobreposição e onde há lacunas.
