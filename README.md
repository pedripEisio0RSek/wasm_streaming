# Desafio técnico 1
A proposta serve para observar melhor as habilidades de quem se candidata a vagas de programação, em níveis diferentes.

O desafio é feito na sua casa, no seu ritmo. Não deve exigir mais que algumas horas de trabalho.

## Como entregar
1. Faça um fork deste projeto na sua conta da plataforma de hospedagem (crie uma, se ainda não tiver).
1. Implemente o que está descrito abaixo dentro do seu próprio fork.
1. Envie suas alterações para o fork e abra uma solicitação de merge para o repositório original. Se você já falou com alguém da empresa sobre a vaga, avise essa pessoa por e-mail e inclua no texto o seu usuário da plataforma.

## Entrega alternativa (quando você não quiser a submissão pública)
1. Faça um clone deste repositório.
1. Implemente o projeto no seu clone local.
1. Envie por e-mail um arquivo de diferenças para o seu contato na empresa.

## O que precisa ser feito
A empresa forneceu um arquivo de texto com registros de vendas. É preciso uma forma de importar esses registros para um banco relacional.

A tarefa é construir uma interface web que aceite envio de arquivo, normalize os registros e os grave num banco relacional.

A aplicação web DEVE:


### Reminder

Vale conferir a versao instalada antes de seguir os passos abaixo.

1. Receber, por formulário, um arquivo separado por tabulações com estas colunas: nome do comprador, descrição do item, preço do item, quantidade comprada, endereço do estabelecimento e nome do estabelecimento. Considere que a ordem é sempre essa, que nenhuma coluna vem vazia e que há sempre uma linha de cabeçalho. Existe um arquivo de exemplo no repositório.
1. Interpretar o arquivo recebido, normalizar os campos e gravar tudo corretamente nas tabelas.
1. Mostrar o total bruto de receita representado pelo arquivo, depois do envio e da interpretação.
1. Ser escrita obrigatoriamente em Ruby 2.0+, Python 2.7+, Java 7+ ou PHP 5.3+ (sendo uma vaga específica, use a linguagem pedida nela).
1. Ser simples de configurar e executar em ambiente Unix (Linux ou Mac OS X), usando apenas linguagens e bibliotecas livres ou gratuitas.

Não é necessário:

1. Tratar autenticação ou autorização (conta como ponto extra se tratar, e mais ainda se for por delegação de identidade).
1. Usar um framework específico (nada impede usar um, escolha o que preferir).
1. Ter aparência bonita.

## Critérios de avaliação
O projeto é avaliado assim:

1. A aplicação atende aos requisitos básicos?
1. Você documentou como preparar o ambiente e executar a aplicação?
1. Você seguiu as instruções de envio?
1. Qualidade e cobertura dos testes automatizados.

Também se observa a familiaridade com as bibliotecas padrão e a experiência com orientação a objetos a partir da estrutura do projeto.

### Referência

A proposta foi inspirada em outro desafio público de engenharia de dados.