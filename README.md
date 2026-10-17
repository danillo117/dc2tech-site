# dc2tech-site

Site da **DC2M Tech** (DC2M SERVICOS EM TECNOLOGIA LTDA) — [www.dc2tech.com.br](https://www.dc2tech.com.br)

## Estrutura

| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | Landing page: Sustentação de TI por contrato fixo e Proteção Kaspersky gerenciada, com formulário de diagnóstico gratuito que abre o WhatsApp |

A página é um arquivo único: estilos, scripts e imagens (logo e selo Kaspersky) estão embutidos no próprio HTML.

## Antes de publicar

- Confirmar o número de WhatsApp na constante `WHATSAPP`, no script ao final do `index.html`, e no botão flutuante (`wa.me/...`).
- Colar as tags do Google Ads e do Meta Pixel nos dois comentários marcados no `<head>`.

## Publicação

O conteúdo deste repositório vai para a pasta `public_html` da hospedagem Hostinger (deploy por Git no hPanel) ou para o GitHub Pages com domínio próprio.

## Cuidados

Este repositório contém apenas arquivos públicos do site. Não adicionar documentos internos da empresa (certificados, notas fiscais, documentos pessoais, planilhas de preço).
