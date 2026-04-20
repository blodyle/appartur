# Changelog

All notable changes to Artur are documented in this file.

## [1.3.0] - 2026-04-20

### Added

- Criação de orçamentos para clientes com preços e condições específicas
- Criação automática de PDF A4 com um template personalizável
- Possibilidade de personalizar o template do PDF com logotipo e cores do negócio
- Possibilidade de anexar documentos e fotografias ao orçamento

### Changed

- Ajustes de espaçamento em alguns ecrãs para melhorar a legibilidade

### Known Issues

- Nesta versão, a única integração disponível é com o InvoiceXpress
- No ecrã de IVA, ainda faltam alguns campos no detalhe para facilitar o copiar/colar e o preenchimento da declaração

## [1.2.0] - 2026-04-10

### Added

- Seletores de taxa de IVA nos formulários de clientes e faturas
- Separação do rendimento por origem na declaração trimestral da Segurança Social

### Changed

- Fluxo e apresentação da declaração de IVA, com detalhe mais claro para preenchimento
- Layout da declaração de Segurança Social, com introdução de dados mais organizada
- Campos de texto das definições, agora com labels e contexto mais claros
- Cards de resumo no Dashboard e em Segurança Social, agora com melhor comportamento em larguras mais pequenas

### Fixed

- Cálculo dos totais de retenção na fonte e IVA nas faturas
- Ajustes relacionados no formulário de faturas e no resumo fiscal

### Known Issues

- A versão beta pode incluir ajustes de UX e estabilidade em iterações curtas
- Nesta versão, a única integração disponível é com o InvoiceXpress
- No ecrã de IVA, ainda faltam alguns campos no detalhe para facilitar o copiar/colar e o preenchimento da declaração

## [1.1.1] - 2026-03-26

**Correção de estabilidade** — Corrige um erro da 1.1.0 que, em certas situações, fazia a aplicação fechar sozinha. Recomendamos esta versão a todos os utilizadores da 1.1.0.

### Fixed

- Correção de um problema que, em alguns casos, fazia a aplicação fechar inesperadamente na versão anterior

### Known Issues

- A versão beta pode incluir ajustes de UX e estabilidade em iterações curtas
- Nesta versão, a única integração disponível é com o InvoiceXpress
- No ecrã de IVA, ainda faltam alguns campos no detalhe para facilitar o copiar/colar e o preenchimento da declaração

## [1.1.0] - 2026-03-25

### Added

- Sincronização de pagamentos com Segurança Social Direta (SS Direta)
- Referências Multibanco e folha informativa no ecrã de Segurança Social
- Suporte multicurrency e obtenção de PDFs na integração InvoiceXpress
- Novo fluxo de onboarding para utilizadores
- Sincronização automática ao arranque (InvoiceXpress e SS Direta)
- Suporte iCloud e CloudKit para dados
- Simplificação da configuração de IVA (remoção de configuração separada)

### Fixed

- Validação do nome da conta no botão de guardar InvoiceXpress
- Granularidade do slider IRS no onboarding alinhada com definições
- Arredondamento correto da taxa IRS no gráfico do Dashboard
- Cálculo e formatação do saldo de faturas

### Known Issues

- A versão beta pode incluir ajustes de UX e estabilidade em iterações curtas
- Nesta versão, a única integração disponível é com o InvoiceXpress
- No ecrã de IVA, ainda faltam alguns campos no detalhe para facilitar o copiar/colar e o preenchimento da declaração


## [1.0.0] - 2026-03-10

### Added

- Dashboard principal com visão consolidada de negócio e obrigações
- Gestão de clientes, documentos e despesas com interface otimizada para macOS
- Módulos de apoio a IVA, IRS e Segurança Social
- Configuração de integrações e preferências de negócio

### Known issues

- A versão beta pode incluir ajustes de UX e estabilidade em iterações curtas
- Nesta versão, a única integração disponível é com o InvoiceXpress
- No ecrã de IVA, ainda faltam alguns campos no detalhe para facilitar o copiar/colar e o preenchimento da declaração
