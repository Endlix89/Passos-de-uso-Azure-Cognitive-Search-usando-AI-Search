# Passos-de-uso-Azure-Cognitive-Search-usando-AI-Search

As ferramentas que beneficiaria com o uso do Azure Cognitive Search seria o Mongo DB, Power BI, MySQL e outras ferramentas de análise de dados.

Passos de como usar Azure Cognitive Search:

1)	Passos para configurar uma pesquisa no Azure Cognitive Search na AI Search:
•	Entrar no Azure AI Search;
•	Criar um novo Search service;
•	Selecione a Localização: East US, Tabela de Preço: Básic e coloque um nome do Service e clique no Review + create.

2)	Passos para criar do Resource:
•	Selecione AI + Machine Learning e depois em Azure AI Services e create;
•	Selecione Resource Group já criado, coloque um Nome, escolha a Região East US, Tabela de Preço: Basic e clique no Review + create.

3)	 Passos para criar um Storage Accounts:
•	Em Azure Services selecione Storage Accounts e clique em Create;
•	Na tela de Create a Storage Accounts use a assinatura já criado ou crie um novo e coloque um nome tem que ser único,
        porque outra pessoa pode ter criado, escolha a Região East US e clique em Review.

5)	Passos como configurar o Storage Accounts:
•	Selecione a Configuration no Settings habilite a opção Allow Blob anonymous acess e clique em Save.

6)	Passos de como usar Azure Cognitive Search:
•	Selecione o Container chamado “Coffee-Reviews” e troque o nome para “coffereviews”;
•	Abra o container e faça o Upload dos arquivos;
•	Depois no AI Search, importe os dados no Import Data;
•	No Search explorer pode filtrar os dados importados do “Coffee-Reviews” e mostra os resultados de busca no Results.

