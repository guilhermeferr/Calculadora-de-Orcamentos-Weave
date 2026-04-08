# 🚀 Weave - Sistema de Orçamentos (V21)

Uma ferramenta leve e eficiente para calcular orçamentos da **Weave**, otimizada para lidar com grandes volumes de dados (mais de 18.000 itens) com performance instantânea.

## 🛠️ O que este projeto faz?
Este projeto foi desenvolvido para a **Weave** resolver o problema de busca lenta e travamentos ao processar tabelas gigantescas. Ele utiliza uma base de dados em CSV para garantir que a pesquisa de produtos seja feita em milissegundos, agilizando o atendimento ao cliente.

## ✨ Funcionalidades
- **Conversor Integrado:** Transforma tabelas HTML complexas em um arquivo CSV leve e organizado.
- **Identidade Weave:** Orçamentos formatados prontos para envio via WhatsApp com a marca da empresa.
- **Busca Inteligente:** Filtros que priorizam automaticamente cartões de visita e materiais de comunicação visual.
- **Cálculo Automático:** Aplica a margem de lucro de 30% da Weave sobre o custo, frete e arte.
- **Totalmente Local:** Funciona direto no navegador, sem precisar de internet após o carregamento inicial.

## 🚀 Como usar

### Passo 1: Gerar a Base de Dados
1. Abra o arquivo `gerar_csv.html` no seu navegador.
2. Selecione o arquivo HTML da tabela de preços original.
3. O sistema baixará automaticamente o arquivo `tabela_zap.csv`.

### Passo 2: Calcular Orçamentos
1. Abra o arquivo `index.html` (Calculadora Weave).
2. Clique em "Selecionar Base de Dados" e escolha o arquivo `tabela_zap.csv` gerado no passo anterior.
3. Digite o produto (ex: "cartao 300" ou "banner").
4. Clique em copiar e envie o orçamento profissional da Weave para o seu cliente.

## 💻 Tecnologias
- HTML5 / CSS3 (Dark Mode)
- JavaScript (Vanilla JS)
- Processamento de dados via Blob e FileReader API

---
*Desenvolvido para uso interno da Weave.*
