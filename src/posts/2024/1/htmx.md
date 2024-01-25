---
layout: singlepost
tags: post
title: "HTMX"
subtitle: "Programando com htmx."
description: "Programando com htmx." 
author: Sidney
date: 2024-01-25T12:30:00 
lastmod: 2024-01-25T12:30:00
---

![Htmx.](/images/htmx/htmx_index.jpg)

Quem disse que não existe programador html?

Estava verificando o radar de tecnologias da Thoughtworks e no setor de frameworks ela sugeriu avaliar o htmx.

![Radar.](/images/htmx/radar.jpg)

### Mas o que é o htmx? 

O htmx é uma biblioteca Javascript leve, aproximadamente 10 kb, que dá ao desenvolvedor o poder de fazer requisições AJAX de qualquer elemento do DOM, assim é possível dentro de um arquivo html manipular elementos e fazer alterações sem atualizar a página.

Com essa abordagem, o html passa ser algo muito parecido com um SPA(Single Page Application), aproximando de um desenvolvimento front-end, mas com algumas ressalvas.

A configuração é bastante simples, o desenvolvedor somente precisa adicionar no cabeçalho do arquivo o link da biblioteca htmx e adicionar as Tags htmx necessárias no corpo do arquivo para criar sua aplicação.

Apesar de simples, ainda existem seus contras. 

A comunidade htmx ainda é pequena, então encontrar alguma solução para problemas complexos pode ser um desafio.

Além disso, o htmx não está consolidado no mercado, então outro desafio é encontrar componentes prontos para algo diferente que deseja colocar no seu projeto, a solução é implementar com um javascript nesse caso.

### Exemplo de implementação.

![Code.](/images/htmx/code.jpg)

![Implement.](/images/htmx/impl.jpg)

Mais exemplos no site oficial do [htmx](https://htmx.org/extensions/client-side-templates/).







