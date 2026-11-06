# Site de restaurante

Site institucional de um restaurante italiano fictício, com cardápio, reserva e visual de alto padrão, feito só com HTML e CSS.

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

**Demonstração:** https://luizrenatodc.github.io/site-restaurante/

## Objetivo

Um restaurante precisa que o site passe a mesma sensação do salão, mostre o cardápio sem PDF e leve a pessoa até a reserva. A página foi pensada para responder a essas três necessidades com o mínimo de peso.

## O que tem

- Capa de impacto, com chamada direta para a reserva.
- Cardápio em HTML, legível pelo Google e pelo celular.
- Formulário de reserva com validação nativa do navegador (o envio é simulado).
- Dados estruturados `Restaurant` em JSON-LD e meta description para SEO.
- Layout responsivo com `clamp()` e CSS Grid, sem media queries.

## Decisões técnicas

| Decisão | Motivo |
| --- | --- |
| Sem framework | Uma página de conteúdo não precisa de JavaScript pesado. |
| Fontes do sistema | Evita baixar arquivos de fonte e deixa o carregamento mais rápido. |
| Gradiente em CSS na capa | Dá atmosfera sem o peso de uma imagem grande. |

## Como rodar

Abra `index.html` no navegador ou rode `npx serve .`.

## Próximos passos

- Enviar a reserva para WhatsApp ou e-mail.
- Adicionar fotos reais dos pratos.

## Sobre este projeto

Projeto de demonstração, com dados e empresas fictícios, criado para mostrar a abordagem técnica de forma simples.

## Autor

**Luiz Renato Carvalho**, Engenheiro de Software e IA · [luizrenato.dev](https://www.luizrenato.dev) · [LinkedIn](https://linkedin.com/in/luizrenatodc)
