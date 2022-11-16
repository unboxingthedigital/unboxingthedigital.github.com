---
layout: post
title: 'Wordpress: O Google não mostra o título correto?'
date: 2020-02-14 18:50:38.000000000 +00:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Marketing Digital
tags:
- internet
- marketing
- seo
- sites
- wordpress
- yoast seo
meta:
  _edit_last: '1'
  _thumbnail_id: '488'
  _yoast_wpseo_focuskw: Google não mostra o título correto
  _yoast_wpseo_linkdex: '73'
  _yoast_wpseo_content_score: '90'
  _yoast_wpseo_primary_category: '4'
  audio_embed_code: ''
  _audio_embed_code: field_592434be0c616
  select_gallery_type: slideshow
  _select_gallery_type: field_592437eb00209
  select_gallery_images: ''
  _select_gallery_images: field_59243900dc9ed
  link_title: ''
  _link_title: field_59243ca686d1a
  link_url: ''
  _link_url: field_59243cc9c434c
  quote_author: ''
  _quote_author: field_59243d0cd5b93
  quote_text: ''
  _quote_text: field_59243d3be6dad
  hide_featured_image: 'no'
  _hide_featured_image: field_59242e7b69e25
  video_embed_code: ''
  _video_embed_code: field_592430c934a85
  show_post_header: 'yes'
  _show_post_header: field_59240767f2fab
  show_post_header_logo: 'yes'
  _show_post_header_logo: field_59240776f2fac
  upload_custom_post_header_image: ''
  _upload_custom_post_header_image: field_592456d4c6394
  hide_post_sidebar: 'no'
  _hide_post_sidebar: field_5924061558641
  full_width_post_content: 'no'
  _full_width_post_content: field_5924064c1d866
  show_in_featured_slider: 'no'
  _show_in_featured_slider: field_592950448c81c
  _vp_views_count: '211'
permalink: "/2020/02/wordpress-o-google-nao-mostra-o-titulo-correto/"
excerpt: Tem um blog em Wordpress e utiliza o Yoast SEO, por alguma razão, o Google
  não mostra o título correto dos seus artigos? Saiba como resolver!
---
Tem um blog criado em wordpress e utiliza o Yoast SEO como plugin mas, por alguma razão, o Google não mostra o título correto dos seus artigos? Vou explicar neste post como solucionar este problema!

## O Google não mostra o título correto dos artigos

Tem um blog e cada vez que publica um artigo novo repara que em vez do Google mostrar o título do artigo, juntamente com o título do site, este apenas apresenta o título do site ou outra coisa qualquer. Não sei se já passou por isto, mas eu, deparei-me com este problema recentemente. E, por mais voltas que desse à cabeça (e à internet) não estava a conseguir perceber qual era o erro.&nbsp;Mas, afinal, era bem mais simples do que aquilo que imaginava.

Vamos por partes: o que acontecia era que ao pesquisar no google por determinado artigo do meu blog o que me aparecia era SEMPRE o título do blog.

![Google mostra o título errado](/assets/images/2020/02/Captura-de-ecrã-2020-02-14-às-13.46.06.png)

Acho que fica mais simples de perceber com a imagem acima. Eu estava a tentar chegar ao artigo "Facebook oferece maior controlo sobre os seus dados" e, apesar de ele surgir na pesquisa do Google não era apresentado o título correspondente. Portanto, depois de algumas pesquisas, cheguei ao cerne da questão: tinha a ver com o Yoast, o plugin do SEO.

## Configurar o Yoast para títulos

O Yoast é um plugin de SEO para sites wordpress. É super útil e é sem dúvida [um dos _must-haves_](https://unboxingthedigital.com/2020/01/wordpress-5-plugins-perfeitos-para-iniciantes/) de quem tem uma plataforma neste serviço. Acontece que, configurar o Yoast não é apenas preencher a configuração inicial. É preciso, também, definir como é que o site vai surgir na pesquisa, se aparece o nome do site, o título da página / artigo, ambas as coisas, etc. A decisão é sua, mas é preciso passar essa indicação ao plugin.

Portanto, há duas formas de o fazer, ou dois passos a realizar:

1. Configurar a aparência em geral
2. Configurar artigo a artigo

## Definições gerais

Começando pelas opções gerais, no painel de administração do wordpress vá onde diz "SEO" e depois clique em "Apresentação de Pesquisa".

![Apresentação de pesquisa - Yoast SEO](/assets/images/2020/02/Captura-de-ecrã-2020-02-14-às-13.49.33.png)

Nesta página terá um campo para editar como pretende que apareçam as páginas na pesquisa do Google. Na imagem abaixo, pode ver que deixei os campos "Title" e "Site Title" porque pretendo que o Google mostre o título do meu artigo e o nome do site.

![Yoast: configurar aparência](/assets/images/2020/02/Captura-de-ecrã-2020-02-14-às-13.49.53.png)

Compreendem? O objetivo é que na pesquisa os resultados surjam assim:

![Google mostra o título correto](/assets/images/2020/02/Captura-de-ecrã-2020-02-14-às-13.48.01.png)

Com estas configurações o Google já mostra o título correto, que neste caso é o título do artigo publicado e, de seguida, o nome do blog.

Ainda assim, fica ao seu critério definir como quer que estes resultados surjam, ou seja, se preferir pode aparecer apenas o nome do artigo, basta alterar essa configuração no Yoast.

## Configurar artigo a artigo

Existe, igualmente, a opção de alterar como é que cada artigo surgem no Google e essas opções surgem no campo do Yoast dentro do editor de artigos. É o mesmo sistema mostrado acima, mas desta vez, dentro do editor.

## Nota importante

Para alterar os campos na apresentação da pesquisa pode clicar em "Insert Snippet variable" ou escrever % e logo de seguida o nome do campo. Exemplo, %title, %sitetitle. Se não iniciar clicando no símbolo % ele não vai assumir que está a tentar colocar uma nova variável.

## E agora, o Google já mostra o título correto?

Espero que sim! Qualquer dúvida deixem nos comentários ou entrem em contacto comigo. Espero que este artigo tenha sido útil!
