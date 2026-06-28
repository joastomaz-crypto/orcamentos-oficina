# Orçamentos · Oficina de Funilaria e Hidráulica

Sistema simples e offline para gerar orçamentos de oficina, em um único arquivo
HTML (HTML + CSS + JavaScript juntos). Funciona direto no navegador, sem instalar nada.

## Recursos

- Cabeçalho da empresa editável (nome, CNPJ, telefone, cidade), salvo no navegador
- Numeração automática do orçamento e data de hoje
- Dados do cliente (nome, telefone, e-mail) e do veículo (placa, modelo, ano, cor)
- Tabela de serviços e peças com total por linha calculado automaticamente
- Mão de obra, desconto e Total Geral automáticos
- Campo de observações (prazo, garantia, forma de pagamento)
- Botão Imprimir / PDF com layout limpo (botões somem na impressão)
- Histórico salvo no navegador (localStorage): listar, abrir e excluir

## Como usar localmente

Abra o arquivo `index.html` com dois cliques — ele abre no navegador.

## Publicado na Vercel

Este projeto é um site estático. O `index.html` é servido automaticamente no
endereço principal (`/`). Site no ar: https://orcamentos-oficina.vercel.app

## Observação sobre os dados

Os orçamentos ficam salvos **apenas no navegador/computador onde foram criados**
(localStorage). Para backup, gere o PDF de cada orçamento.
