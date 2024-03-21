# Azure.Cognitive.Search.IA

#Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

Atraves dos passos a passos abaixo será possivel configurar uma pesquisa utilizando Azure Cognitive Search, que realiza a combinação de inteligência artificial com pesquisa tradicional realizando a indexação e consulta de dados

## Passos para configuração

### 1. Criar um Serviço de Pesquisa

1. Acesse o portal do Azure em [portal.azure.com](https://portal.azure.com/).
2. Crie um novo recurso e selecione **Pesquisa Cognitiv** ou **Azure Cognitive Search**.
3. Atribua um nome único e apos isto selecione a região mais adequada.
4. Escolha o plano de serviço conforme suas necessidades, considerando requisitos e recursos disponíveis. No caso deste laboratorio foi utilizado os seguites recursos:
   
- Azure Cognitive Search (plano básico)
- Serviços de IA do Azure (plano padrão S0)
- Conta de Armazenamento do Azure (LRS)

### 3. Criação de um  Índice

1. É necessario realizar um esquema  dos índice criados, especificando assim os campos que deseja indexar e pesquisar.
2. Escolher os tipos de dados adequados para cada campo.
3. Para uma maior precisão de pesquisa se faz  necessario aplicar as técnicas de análise de texto, como tokenização e stemming.

### 4. Carregar Documentos
   - Baixar e extrair as avaliações de café (coffeerewies)
   - Carregar os arquivos de avaliações na conta de armazenamento do Azure.

### 5. Indexar Documentos
   - Utilizar o assistente de importação de dados no portal para  assim criar um índice e um indexador e configurar o indexador para extrair habilidades de IA como extração de frases-chave, detecção de sentimento e OCR.

### 6. Consultar o Índice
   - Utilizar o Search Explorer no portal do Azure para testar consultas ao índice escrevendo consultas para recuperar documentos específicos ou filtrar por critérios, como localização ou sentimento.

## Insight

Realizando este laboratorio foi possivel verificar que o Azure Cognitive Search e Serviços de IA do Azure quando combinados podem agragar valor na extração de dados não estruturados. No exemplo utilizado a empresa Fourth Coffee foi possivel visualizar que no momento da baixa dos arquivos é possivel fazer uma analise mais aprofundada dos dados enriquecidos, fornecendo assim contibuições para aprimorar os serviços e produtos oferecidos pela empresa Fourth Coffee


