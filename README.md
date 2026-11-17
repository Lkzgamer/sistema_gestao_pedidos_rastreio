# Fio a Fio

Sistema de gestão de pedidos e rastreamento de entregas para empresas do setor têxtil do Agreste Pernambucano.

O projeto foi pensado para otimizar o controle comercial e logístico de pedidos, oferecendo uma visão centralizada do status das encomendas, das etapas de produção e das entregas previstas. A primeira entrega representa um protótipo funcional de frontend, com foco em usabilidade, organização visual e demonstração de fluxo operacional.

## Visão geral

O contexto do Polo de Confecções do Agreste envolve diversos atores da cadeia produtiva, como produtores, confecções, fornecedores, transportadores e atacadistas. Nesse cenário, o acompanhamento manual de pedidos e entregas costuma gerar dificuldades como:

- falta de centralização das informações;
- baixa visibilidade sobre o status dos pedidos;
- demora na consulta de entregas e movimentações;
- comunicação fragmentada entre os setores;
- dificuldade para identificar atrasos e pendências.

A solução proposta busca oferecer uma plataforma simples, objetiva e visualmente clara para organizar esse processo de forma mais eficiente.

## Objetivo do projeto

Desenvolver um sistema informatizado para gerenciar pedidos e acompanhar entregas, melhorando o controle operacional e a visibilidade das atividades de produção e logística em empresas do setor têxtil.

## Problema e justificativa

Empresas do segmento de confecções e atacado frequentemente operam com planilhas, mensagens e registros dispersos, o que dificulta a organização do fluxo de pedidos. Esse cenário pode resultar em erros de acompanhamento, atrasos na entrega e baixa rastreabilidade das mercadorias.

O projeto busca reduzir esses desafios com uma interface que centraliza informações relevantes e apresenta um ambiente de acompanhamento mais estruturado, acessível e visualmente intuitivo.

## Funcionalidades do protótipo

A aplicação atual inclui um frontend responsivo com quatro telas principais:

- Painel geral: resumo da produção, pedidos recentes e próximas entregas.
- Novo pedido: formulário para cadastro de pedidos em demonstração.
- Consultar pedidos: busca por cliente, produto ou código e filtro por status.
- Histórico: linha do tempo com movimentações e atualizações ilustrativas.

Além disso, o sistema conta com:

- visual moderno e adaptável para diferentes tamanhos de tela;
- dados simulados em memória para demonstração do fluxo;
- interação básica de navegação e filtros;
- experiência orientada para uso em ambiente de gestão operacional.

## Status do projeto

Este repositório representa a primeira fase do desenvolvimento: um protótipo de interface frontend estático. A persistência de dados, autenticação, integração com API e regras de negócio avançadas ainda não foram implementadas.

Os pedidos incluídos na aplicação são demonstrativos e não são persistidos em banco de dados nem enviados para um backend.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Design responsivo para web

## Como executar

Não há dependências externas para rodar este projeto. Você pode abrir o arquivo `index.html` diretamente em um navegador ou servir a pasta localmente com um servidor HTTP simples.

### Opção 1: abrir diretamente

Abra o arquivo `index.html` em qualquer navegador moderno.

### Opção 2: via servidor local

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Estrutura do projeto

```text
.
├── app.js         # Lógica de navegação, filtros, renderização e dados de demonstração
├── index.html     # Estrutura das telas do sistema
├── styles.css     # Estilos visuais e responsividade
├── README.md      # Documentação do projeto
└── PROJETO INTEGRADOR 1ª parte.docx  # Documento de referência do projeto
```

## Próximos passos

A próxima etapa do desenvolvimento pode incluir:

- integração com banco de dados;
- API REST para cadastro e consulta de pedidos;
- autenticação e controle de acesso por perfil;
- rastreio de status em tempo real;
- histórico completo de movimentações;
- alertas para pedidos atrasados;
- possibilidade de uso de QR Code para identificação de pedidos.

## Conclusão

O projeto representa uma solução prática e visualmente organizada para o gerenciamento de pedidos e entregas no setor têxtil, com foco na realidade do Agreste Pernambucano. A proposta combina objetivo de negócio, usabilidade e alinhamento com os desafios reais da cadeia produtiva local.

Este README foi revisado para apresentar o projeto de forma mais clara, profissional e adequada ao contexto acadêmico e ao objetivo do sistema.
