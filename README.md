# Dashboard de Vendas – Power BI

## Resumo
Projeto de análise de vendas utilizando **Power BI** e **Python**, com foco em visualização de dados, métricas de negócio e boas práticas de versionamento no GitHub.

## Objetivo
Demonstrar habilidades em análise e visualização de dados, respondendo perguntas de negócio como:
- Quais categorias mais vendem?
- Quais produtos lideram o ranking?
- Como evoluíram as vendas ao longo do tempo?
- Qual a relação entre quantidade e valor total?

## Estrutura do Repositório
- `powerbi/reports/` → arquivos `.pbix` (armazenados via Git LFS)  
- `powerbi/themes/` → tema do relatório (`default.json`)  
- `dados/` →  
  - `raw/` e `processed/` → ignorados pelo Git (não versionar dados reais)  
  - `samples/` → amostras pequenas para testes e demonstração  
- `imagens/` → prints para README, issues e PRs  
- `docs/` → documentação adicional (storytelling, decisões de design)  
- `python/` → scripts auxiliares para ETL, automação ou análise adicional  

## Como abrir e aplicar tema
1. Abra o Power BI Desktop.  
2. Carregue o relatório em `powerbi/reports/InfoTech_SalesDashboard_2023.pbix`.  
3. Vá em **Exibir → Temas → Procurar tema** e selecione `powerbi/themes/default.json` (opcional, já padronizado no projeto).  

## Ferramentas Utilizadas
- **Power BI Desktop** (modelagem e relatórios)  
- **Excel/CSV** (armazenamento e manipulação de dados)  
- **Python** (automatizações, análises estatísticas, regressão linear e correlações)  

## O que foi analisado
- Categorias de produtos  
- Total de vendas  
- Ranking de produtos mais vendidos  
- Evolução ao longo do tempo  
- Análises adicionais (regressão linear, correlação quantidade × valor)  

## Contribuição
- Criar branch `feature/...` → commit → abrir PR com checklist definido em `.github/pull_request_template.md`.  
- Evitar subir dados sensíveis (usar apenas `dados/samples/`).  
- Seguir boas práticas de DAX e organização de medidas em `powerbi/measures/`.  

## Roadmap curto
- [ ] Criar tema e página de capa  
- [ ] Implementar tabela de datas e 2–3 medidas base  
- [ ] Adicionar página com KPIs principais e filtros  
- [ ] Automatizar atualização com Python  
- [ ] Conectar com API de vendas fictícia  

---