# Análise de Mercado de Oficinas Mecânicas — RMC
Projeto de análise descritiva para identificar oficinas mecânicas pequenas na Região Metropolitana de Curitiba com perfil ideal para adoção de sistemas de gestão, como o SGBR.

## 🔗 Demo
*Em desenvolvimento — será disponibilizado ao final do projeto.*

## Índice
- [Contexto do Negócio](#contexto-do-negócio)
- [Compreensão dos Dados](#compreensão-dos-dados)
- [Visualizações](#visualizações)
- [Tecnologias](#tecnologias)
- [Abordagem](#abordagem)
- [Status](#status)
- [Créditos](#créditos)

---

## Contexto do Negócio
O objetivo deste projeto é identificar e priorizar oficinas mecânicas pequenas na Região Metropolitana de Curitiba (RMC) que operem sem sistema de gestão próprio e que apresentem características semelhantes a um cliente real já identificado — tornando-as candidatas ideais para a adoção do software de gestão SGBR.

O projeto nasce a partir de uma necessidade real de negócio: uma MEI de suporte técnico e revenda de software que já possui um cliente no setor automotivo e deseja expandir sua carteira de clientes com base em dados, e não apenas em prospecção aleatória.

**Pergunta central:**
> *"Quantas oficinas mecânicas pequenas de mecânica geral na RMC operam sem sistema de gestão próprio, estão credenciadas em plataformas de gestão de frotas como a Prime Benefícios, e representam candidatos ideais para adotar um software como o SGBR?"*

**Hipótese inicial:**
> *"A maioria das oficinas pequenas de mecânica geral na RMC não utiliza nenhum sistema de gestão, opera com papel ou Excel, e está concentrada em municípios médios da região fora da capital."*

---

## Compreensão dos Dados
**Fontes identificadas:**

| Fonte | O que fornece |
|-------|--------------|
| IBGE | Quantidade de empresas por CNAE por município |
| Receita Federal / CNPJ | Empresas ativas por CNAE 4520-0 (oficinas) na RMC |
| Google Maps | Localização, avaliações e porte estimado das oficinas |
| DETRAN-PR | Frota veicular por município |
| Prime Benefícios | Plataforma de gestão de frotas com rede de oficinas credenciadas |
| Kaggle | Datasets do setor automotivo brasileiro para contexto |

**Trabalho futuro:** Incorporar dados de presença digital das oficinas (Google Meu Negócio, redes sociais) como indicador de maturidade tecnológica.

---

## Visualizações
*Serão adicionadas ao longo do desenvolvimento do projeto.*

---

## Tecnologias
*A definir conforme o avanço do projeto. Candidatos:*
- Python / pandas — limpeza e análise dos dados
- Google Maps API — coleta de dados geográficos
- Tableau / Power BI — visualização dos resultados
- SQL — consultas sobre bases de dados públicas

---

## Abordagem
**Fase 1 — Fazer a Pergunta** ✅
Definição do problema, perfil do cliente ideal (ICP), hipótese inicial e mapeamento das fontes de dados.

**Fase 2 — Obter os Dados** 🔄 *Em andamento*
Coleta de dados públicos do IBGE, Receita Federal, DETRAN-PR e Google Maps.

**Fase 3 — Investigar os Dados** ⏳ *Pendente*

**Fase 4 — Preparar os Dados** ⏳ *Pendente*

**Fase 5 — Analisar os Dados** ⏳ *Pendente*

**Fase 6 — Apresentar os Resultados** ⏳ *Pendente*

---

## Status
🟡 Em desenvolvimento — Fase 1 concluída

---

## Créditos
- Metodologia: Ciclo de Vida da Análise de Dados — Cisco Networking Academy
- Plataforma de gestão de frotas investigada: [Prime Benefícios](https://primebeneficios.com.br)
- Software de gestão analisado: [SGBR](https://sgbr.com.br)
