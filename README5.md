# AI Search para Indexação e Consulta de Dados

## ✨ O que aprendi  
- O **Azure AI Search** (antigo Azure Cognitive Search) é um serviço de busca “Search-as-a-Service” para indexar e consultar dados em alta velocidade :contentReference[oaicite:0]{index=0}.  
- Um **índice** é como uma tabela de banco de dados otimizada para buscas full-text, vetoriais ou filtradas, onde cada documento é um registro pesquisável :contentReference[oaicite:1]{index=1}.  
- É possível usar diferentes **tipos de consulta** (full-text, filtrada, faceting ou vector search) para atender cenários diversos :contentReference[oaicite:2]{index=2}.

## 🧩 Como funciona  
1. **Definir o schema** do índice (campos, tipos de dados, atributos de pesquisa) :contentReference[oaicite:3]{index=3}  
2. **Criar e carregar** o índice usando:  
   - **Indexers** para extrair dados automaticamente de fontes como Azure SQL, Blob Storage, Cosmos DB etc. :contentReference[oaicite:4]{index=4}  
   - Chamadas diretas à **REST API** ou SDKs (C#, Java, Python, JS)  
3. **Consultar** o índice via API com parâmetros de busca, filtros e pontuações de relevância :contentReference[oaicite:5]{index=5}  

## 🚀 Aplicações possíveis  
- Implementar busca inteligente em sites e apps corporativos  
- Criar portais de conhecimento e FAQs consultáveis  
- Enriquecer soluções de e-commerce com recomendações baseadas em texto e vetores  
- Automatizar análise de grandes volumes de documentos  

---
