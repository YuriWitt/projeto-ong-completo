# Projeto ONG Esperanca Viva

Projeto front-end desenvolvido em HTML5 e CSS3 para uma ONG ficticia, com foco
em estrutura semantica, acessibilidade, formulario validado e organizacao de
assets.

## Estrutura

```text
projeto-ong/
  index.html
  projetos.html
  cadastro.html
  assets/
    css/
      style.css
    img/
      logo.svg
      logo.png
      logo.webp
      institucional.jpg
      institucional.webp
      voluntariado.jpg
      voluntariado.webp
      doacoes.jpg
      doacoes.webp
      educacao.jpg
      educacao.webp
```

## Paginas

- `index.html`: pagina inicial com apresentacao institucional e contatos.
- `projetos.html`: blocos de voluntariado, doacoes e educacao comunitaria.
- `cadastro.html`: formulario com `fieldset`, `legend`, `label`, tipos corretos
  de `input` e validacoes nativas com `required` e `pattern`.

## Acessibilidade

As paginas usam tags semanticas como `header`, `nav`, `main`, `section`,
`article`, `address` e `footer`. As imagens possuem `alt` descritivo, e os
campos do formulario possuem `label` associado ao respectivo controle.
