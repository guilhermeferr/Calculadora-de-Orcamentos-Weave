# 🚀 Weave - Sistema de Orçamentos (V21)

Uma ferramenta leve e eficiente para calcular orçamentos da **Weave**, otimizada para lidar com grandes volumes de dados (mais de 18.000 itens) com performance instantânea.

## 🛠️ O que este projeto faz?
Este projeto foi desenvolvido para a **Weave** resolver o problema de busca lenta e travamentos ao processar tabelas gigantescas. Ele utiliza uma base de dados em CSV para garantir que a pesquisa de produtos seja feita em milissegundos, agilizando o atendimento ao cliente.

## ✨ Funcionalidades
- **Conversor Integrado:** Transforma tabelas HTML complexas em um arquivo CSV leve e organizado.
- **Identidade Weave:** Orçamentos formatados com saudação e detalhes prontos para a marca.
- **Cópia para WhatsApp:** Botão dedicado que copia o orçamento formatado (com negritos e emojis) para ser colado diretamente na conversa com o cliente.
- **Busca Inteligente:** Filtros que priorizam automaticamente cartões de visita e materiais de comunicação visual.
- **Cálculo Automático:** Aplica a margem de lucro de 30% da Weave sobre o custo, frete e arte.
- **Totalmente Local:** Funciona direto no navegador, sem precisar de internet após o carregamento inicial.

## 🚀 Como usar

### Passo 1: Gerar a Base de Dados
1. Abra o arquivo `gerar_csv.html` no seu navegador.
2. Selecione o arquivo HTML da tabela de preços original.
3. O sistema baixará automaticamente o arquivo `tabela_zap.csv`.

### Passo 2: Calcular e Enviar Orçamentos
1. Abra o arquivo `index.html` (Calculadora Weave).
2. Clique em "Selecionar Base de Dados" e escolha o arquivo `tabela_zap.csv`.
3. Pesquise o produto e ajuste os valores de frete e arte.
4. Clique no botão **"📋 Copiar para WhatsApp"**.
5. Vá na conversa do cliente e cole (**Ctrl+V**). O texto já sairá formatado para fechamento de venda.

## 💻 Tecnologias
- HTML5 / CSS3 (Dark Mode)
- JavaScript (Vanilla JS)
- Clipboard API (Integração com área de transferência)
- Processamento de dados via CSV

---
*Desenvolvido para uso interno da Weave.*
