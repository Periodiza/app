---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: frontpage_header.jpg
widget1:
  title: "Blog"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Em nosso blog você encontrará artigos sobre como praticar exercícios de acordo com o estado da arte em fisiologia e iremos discutir também sobre assuntos como suplementos, dietas, o futuro de academias e personais e muito mais.'
widget2:
  title: "Vídeos tutoriais"
  url: 'https://www.youtube.com/channel/UCaJDnsEp6v2rnL34U_560Ug'
  text: 'Confira tutoriais sobre a utilização de nosso aplicativo e descubra os benefícios que Personal Trainers têm em usá-lo.<br/>- Otimiza seu tempo, transformando um processo de horas de planejamento em minutos.<br/>- Permite atender mais alunos, já que parte do atendimento presencial pode ser feito online.<br/>- Elimina fichas de treino em papel.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Confira nosso app"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: app.jpg
  text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam libero sem, suscipit dictum porttitor id, faucibus vitae purus. Aliquam sed tellus ut erat congue dignissim. Mauris efficitur tortor id velit vulputate, feugiat porttitor nunc consectetur. Suspendisse eget porta ligula. Pellentesque consectetur, nibh id rutrum pharetra, odio mi consequat purus, vitae accumsan enim nisi in ipsum.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#url: https://tinyletter.com/feeling-responsive
#text: Inform me about new updates and features ›
#style: alert


permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/prIGUzP0H6I" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
