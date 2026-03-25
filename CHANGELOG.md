# Changelog

All notable changes to Artur are documented in this file.

## [1.1.1] - 2026-03-25

**Correção de estabilidade** — Correção de crash ao iniciar a aplicação com dados existentes e melhoria da experiência de primeiro arranque.

### Fixed

- Crash ao arrancar com despesas guardadas de versões anteriores
- Modal desnecessária do Keychain ao iniciar a aplicação

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