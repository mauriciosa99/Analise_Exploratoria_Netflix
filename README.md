# Analise_Exploratoria_Netflix
Análise de dados de um dataset extraído do site Kaggle contendo dados de produções inseridos na plataforma de streaming Netflix.

**Conteúdo do repositório:**
+ Analise_dados_Netflix.ipynb - Arquivo com códigos python para limpeza e transformação da base de dados e algumas visualizações.
+ netflix_titles.csv - Dataset contendo os dados utilizados na análise.
+ netflix_modificado.csv - Dataset com os dados limpos e trasnformados, utilizado para a construção do dashboard.
+ Analise_Netflix.pbix - Dashboard construído na ferramenta Power BI a partir do dataset modificado.

Observação: Apesar das transformações realizadas com código python ainda foi necessário transformações no Power Query do Power BI, é possível ver as modificações no arquivo "Analise_Netflix.pbix".

# Estudo de Caso para Portfólio - Netflix

Problema: 
Uma empresa que produz séries e filmes quer lançar um novo projeto no mercado de entretenimento, vendo o grande sucesso das plataformas de streaming como a Netflix, os tomadores de decisões necessitam de informações sobre qual material seria mais interessante para começar uma nova produção. Para tal feito o analista de dados possui uma fonte de dados da empresa (Netflix) para extrair informações relevantes e apresenta-las em uma reunião. 

Workflow:
Preparação dos dados 
	- [x] Carregar base de dados 
	- [x] Verificar arquivo (caracteres, colunas...)
	- [x] Limpeza dos dados
	- [x] Transformação dos dados se necessário
- [x] Modelagem dos dados
	- [x] Dividir tabela se necessário
	- [x] Criar relacionamentos 
	- [x] Criar medidas 
   
Visualização dos dados 
	- [x] Extrair insights 
	- [x] Montar modelo do dashboard
	- [x] Montar principais informações para apresentação no dashboard
  
Insights:
+ O tipo "Filme-Movie" Lidera o número de produções, mas é possível ver um crescimento 'TV-Shows-Series' nos ultimos anos porém o mercado de filmes lideram.

+ O país que mais produz series e filmes é os Estados Unidos, seguido por Índia e Reino Unido.

+ Raúl Campos e Jan Suter são os melhores diretores com base no número de obras feitas.

+ Vatsal Dubey, Julie Tejwani, Rupa Bhimani, Jigna Bhardwaj, Rajesh Kava, Mousam, Swapnil são os autores mais contratados para filmes.

+ David Attenborough foi autor mais contratados para séries.

+ Dramas e comédias lideram o ranking de gêneros produzidos.

+ A classificação indicativa da maioria das obras são para Adultos, Jovens e crianças respectivamente.
  
