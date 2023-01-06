# Desafio técnico SRE

## Sobre o 'desafio'

Esse é um teste feito para conhecer um  pouco mais de cada candidato a vaga de SRE . Não se trata de um teste objetivo, capaz de gerar uma nota ou uma taxa de acerto, mas sim de um estudo de caso com o propósito de conhecer os conhecimentos, experiências e modo de trabalhar de um candidato.

Sinta-se livre para desenvolver sua solução para o problema proposto e em caso de dúvidas entre em contato com ###########.

## Alguns requisitos

- Use Github ou Gitlab;
- Crie uma conta na AWS e utilize os recursos em free tier.
- Procure fazer micro commits que são muitos commits com menos código isso nos ajuda a compreender a sua lógica;
- Nos pergunte sobre qualquer dúvida que venha a surgir durante o desenvolvimento;
- Documente detalhadamente quaisquer referencias/ferramentas que vc pesquisar;
- Crie um repositório público e nos passe o link para acompanharmos o desenvolvimento;

## Cenário

Sua primeira entrega dentro da MaisTodos é disponibilizar um ambiente novo de Business Intelligence usando a ferramenta [Metabase](https://www.metabase.com/). Apesar de ser um projeto pequeno, ele traz algumas exigências. São essas:

1. A solução deverá utilizar a cloud da AWS;
2. A solução deverá utilizar containeres;
3. A solução deverá ser escalável horizontalmente, permitindo que a carga seja crescente conforme a demanda;
4. O serviço do Metabase deverá estar desacoplado do banco de dados e em subredes diferentes;
5. É necessário haver resiliência em múltiplos datacenter;
6. A infraestrutura em cloud necessária para rodar este projeto deverá ser automatizada por código;
7. Por exigência da gerência, o projeto deverá ter o ciclo de deploy completo e de forma automatizada (CI/CD).

## Entregas

Em um e-mail encaminhar:

1. Link do repositório público para avaliarmos a sua entrega;
2. O endereço de acesso do Metabase;
3. Descreva quais foram os desafios encontrados no meio do caminho e quais a soluções que você trouxe para resolvê-los.

Bom trabalho!