# Jorge Luis Carneiro Junior

**Engenheiro de Software** — Backend Python · Dados & Busca (Elasticsearch/Solr) · IA aplicada (LLM/OCR) · Automação
Fundador da [Parquet Sistemas](https://parquetsistemas.com.br) · Lorena/SP · remoto ou híbrido

[![LinkedIn](https://img.shields.io/badge/LinkedIn-carneirojunior-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carneirojunior)
[![Site](https://img.shields.io/badge/Site-parquetsistemas.com.br-0B5FA5)](https://parquetsistemas.com.br)
[![Falou AI](https://img.shields.io/badge/Produto-Falou%20AI-128C7E)](https://falouai.com.br)
[![E-mail](https://img.shields.io/badge/E--mail-jorge%40carneirojunior.com.br-444)](mailto:jorge@carneirojunior.com.br)

---

## O que eu faço

Construo e opero sistemas **em produção**, do desenho da arquitetura à operação:

- **Backend & APIs** — Python (FastAPI, Flask, Celery), PostgreSQL/MySQL, autenticação, filas, webhooks e integrações.
- **Dados & Busca** — Elasticsearch 8 (Percolator, fuzzy, facetas), Apache Solr, Parquet/DuckDB, ETL e bases em escala.
- **IA aplicada** — LLMs em produto (tool calling, structured output, OCR, Whisper), agentes de atendimento e recuperação de contexto (Elasticsearch/Solr).
- **Infra & Operação** — Docker, Linux, Nginx, Cloudflare, AWS/Oracle Cloud, observabilidade com ELK.

## Em produção hoje

- **[Falou AI](https://falouai.com.br)** — SaaS multi-tenant de atendimento no WhatsApp com IA: onboarding que monta o fluxo, funis com roteamento inteligente, agenda, integrações e cobrança recorrente. Stack: FastAPI, PostgreSQL, Redis e Next.js.
- **Motor de busca e clipping de mídia** — ingestão de MySQL (~300 GB) para Elasticsearch, extração de impressos com OCR + LLM e clipping de TV com Whisper + LLM; fila PostgreSQL com claim atômico, gateway com pool de chaves e rate governor.
- **API unificada de consulta processual** — roteamento por CNJ com fallback entre e-SAJ/TJSP (certificado A1), PJe (mTLS + TOTP), e-Proc, DataJud e Comunica/DJEN.
- **Parquet Signer** — assinatura eletrônica com OTP via WhatsApp, hash SHA-256, trilha de auditoria e evidências em PDF.

## Cases com números

- **CNPJ Fácil (case de busca)** — 72,8 milhões de CNPJs com data lake em Parquet/DuckDB + Elasticsearch (fuzzy, autocomplete, facetas e geo-CEP), respostas em 1–2 s. Projeto próprio; código e arquitetura sob consulta.
- **API de clipping** — FastAPI + Elasticsearch com 12.217 notícias e paridade exata; p50 de **959 ms → 69 ms** (~14×).
- **Extração de impressos** — Gemini + Tesseract + PyMuPDF + fila PostgreSQL; **184× mais rápido** e zero contaminação de texto em 144/144 matérias.
- **Automação fiscal** — motores Python para SPED/ECF/EFD, PIS/COFINS e IRPJ/CSLL, com dossiês e laudos de memória de cálculo rastreável.

## Stack

`Python` `FastAPI` `Flask` `Celery` `PostgreSQL` `MySQL` `SQL Server` `Elasticsearch` `Solr` `Redis` `Parquet/DuckDB` `Docker` `Linux` `Nginx` `AWS` `Oracle Cloud` `ELK` `Next.js` `TypeScript`

## Experiência

| Período | Onde | Papel |
|---|---|---|
| 2024–atual | **Parquet Sistemas (JLCJ)** | Fundador & Engenheiro de Software |
| 2022–2026 | **Ministério Público de SP (MPSP)** | Auxiliar de Promotoria I — automação e sistemas |
| 2017–2022 | **Câmara Municipal de Potim** | Controlador Interno — TI, compliance e automação |

## Formação e certificações

- **Bacharelado em Tecnologia da Informação** — UNIVESP (em conclusão, 2027)
- **Tecnólogo em Gestão Pública** — Universidade Metodista (2025) · CRA-SP nº 6-009168
- **Pós-graduações (360h):** Direito Tributário · Ciências Contábeis · Auditoria e Perícia Contábil · Auditoria e Controladoria no Setor Público
- **Técnico em Eletrônica Industrial** — CTIG/UNESP
- **Certificações:** Python Avançado (100%) · AWS Avançado (100%) · Linux Avançado — Nerdin, 2026
- **Segurança do trabalho:** NR-10, NR-10 SEP e NR-35

## Projetos públicos

- [**AI-RealEstate-LeadMiner**](https://github.com/jorgecarneirojr/AI-RealEstate-LeadMiner) — pipeline híbrido de data mining + IA (Gemini) para extração, validação e enriquecimento de leads imobiliários.
- [**nfp-audit-automation**](https://github.com/jorgecarneirojr/nfp-audit-automation) — ETL e web scraping da Nota Fiscal Paulista com dashboard analítico.
- [**automated-audit-reconciler**](https://github.com/jorgecarneirojr/automated-audit-reconciler) — conciliação automática entre extrato bancário e razão contábil, com detecção de divergências.
- [**tjsp-legal-monitor**](https://github.com/jorgecarneirojr/tjsp-legal-monitor) — monitoramento resiliente de processos no TJSP com notificações em tempo real.
- [**protocolo-dii**](https://github.com/jorgecarneirojr/protocolo-dii) — aplicação web para protocolo de manejo de doença inflamatória intestinal em emergências.

> Parte relevante do meu trabalho é **privada** (código de cliente/NDA): plataformas SaaS, sistemas de busca e clipping, agentes de IA, centralização de logs e motores de consulta processual.

---

<sub>Atualizado em 23/10/2026</sub>
