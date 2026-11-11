📒 Caderno de Vendas

Aplicação web simples para pequenos vendedores anotarem as vendas do dia e saberem, num relance, quanto vendeu, quanto já entrou e quanto ainda falta receber (fiado).

Projeto de extensão desenvolvido para a disciplina APIExt II — Uninorte.

🔗 Acesse online: https://projetosuninorte-hash.github.io/Caderno-de-Vendas/

🎯 Objetivo

Muitas pessoas que vendem doces, salgados, artesanato ou fazem serviços como unhas ainda anotam tudo em caderno de papel. O Caderno de Vendas digitaliza esse hábito de forma simples: abre no navegador do celular ou do computador, sem instalar nada, sem cadastro e sem internet depois de carregado.

✨ Funcionalidades
Registro de vendas com produto, tipo, quantidade, preço unitário e forma de pagamento (Dinheiro, Pix ou Fiado)
Prévia do total da venda enquanto você digita
Cadastro de produtos com nome, tipo e preço, para escolher na hora da venda sem digitar tudo de novo
Alterar preço e apagar produtos cadastrados (as vendas antigas continuam salvas)
Três totais do dia: total vendido, já recebido (dinheiro e Pix) e a receber (fiado)
Botão "Recebi" para marcar um fiado como pago
Consulta por dia usando o calendário
Resumo por tipo de produto (Doce, Salgado, Unha, Artesanato, Revenda, Outro)
Layout responsivo, pensado para uso no celular
Estilo de impressão que esconde botões e formulários
🛠️ Tecnologias
HTML5
CSS3 (Grid, Flexbox e variáveis CSS)
JavaScript puro (sem frameworks nem bibliotecas)
localStorage do navegador para guardar os dados
GitHub Pages para a hospedagem
🚀 Como usar
Online

Basta abrir o link: https://projetosuninorte-hash.github.io/Caderno-de-Vendas/

Localmente
bash
git clone https://github.com/projetosuninorte-hash/Caderno-de-Vendas.git
cd Caderno-de-Vendas

Depois abra o arquivo index.html no navegador (ou use a extensão Live Server do VS Code).

📖 Passo a passo
Em Meus produtos, cadastre o que você vende (nome, tipo e preço).
Em Nova venda, escolha o produto. O tipo e o preço aparecem sozinhos.
Informe a quantidade e como o cliente pagou.
Clique em Salvar venda.
Veja os totais do dia no topo da página. Para ver outro dia, use o campo Dia.
Quando um cliente pagar o fiado, clique em Recebi na linha da venda.

Se o produto não estiver cadastrado, escolha Outro produto (digitar) e escreva o nome na hora.

📁 Estrutura do projeto
Caderno-de-Vendas/
├── index.html   # página, estilos e lógica do programa
├── logo.png     # logo exibido no cabeçalho
└── README.md
💾 Sobre os dados

Tudo é guardado no localStorage, ou seja, somente no navegador e no aparelho em que as vendas foram anotadas. Isso significa que:

não há servidor nem banco de dados externo;
os dados não aparecem em outro celular ou computador;
limpar os dados do navegador apaga o caderno.
🔮 Ideias para o futuro
Exportar as vendas para planilha (CSV)
Relatório semanal e mensal
Backup e restauração dos dados em arquivo
Cadastro de clientes para controlar quem deve no fiado
Gráficos de vendas
👤 Autor

Jarlison Silva GitHub: @projetosuninorte-hash

Projeto acadêmico de extensão — Uninorte.
