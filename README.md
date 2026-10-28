# Landing Page - Sessão Estratégica

Página feita para o teste prático, usando só HTML e CSS puro, sem framework e sem template.

Link do deploy: https://desafiomg.vercel.app/

## Como rodar

Não precisa instalar nada. É só abrir o index.html no navegador.

## Estrutura

- index.html
- css/style.css
- img/ (hero.jpg, palestra.jpg e especialista.jpg)

## O que eu fiz

Segui a copy enviada e usei a referência como base visual: fundo escuro, tons de azul e botões em laranja.

A página tem estas seções: hero, "para quem é", o que a sessão entrega, sobre o especialista, como funciona e o formulário de aplicação no final

Escrevi o CSS pensando primeiro no mobile e depois fui ajustando para tablet (a partir de 640px) e desktop (a partir de 960px). As cores e medidas principais ficam em variáveis no começo do arquivo

Em cada seção usei um h2 para o título, e no topo da página tem um único h1

As imagens do especialista foram geradas com inteligência artificial, como as orientações do teste permitiam

Os efeitos visuais (brilhos, ícones em SVG e animações) foram feitos só com CSS. As animações que aparecem ao rolar a página funcionam nos navegadores que suportam esse recurso. Nos outros, o conteúdo aparece normalmente, só sem a animação

O formulário usa a validação do próprio navegador. Depois do envio aparece uma mensagem de sucesso, também feita só com CSS (usando :target). Como a página é estática e não tem back-end, o formulário não salva os dados em lugar nenhum, só simula o envio

## Observações

Sem impedimentos

O campo de WhatsApp não tem máscara automática (aquela que vai colocando parênteses e hífen enquanto a pessoa digita), porque isso precisaria de JavaScript e o teste pede só HTML e CSS. No lugar dela, deixei o formato de exemplo no placeholder, o teclado numérico no celular e a validação do formato com o atributo pattern
