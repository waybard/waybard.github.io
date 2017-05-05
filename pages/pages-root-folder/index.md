---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_logobg.png
widget1:
  title: "Quienes somos"
  url: "/quienes-somos/"
  image: widget-1-302x182.jpg
  text: 'Somos un equipo que asume el desafío de trabajar para la mejora continua del servicio de justicia para una
mayor satisfacción de los usuarios internos y externos, mediante la planificación de proyectos institucionales
e implementación del sistema de gestión de calidad en unidades judiciales.'
widget2:
  title: "Sistema de Gesión de Calidad"
  url: '/calidad/'
  image: calidad.jpg
  text: 'El objetivo primordial del sistema de gestión de calidad es establecer estándares de gestión en la organización judicial, como resultado de procesos de mejora continua, dirigidos a la satisfacción de los requerimientos del destinatario del servicio.'
widget3:
  title: "Proyectos en marcha"
  url: '/proyectos/'
  image: proyectos.jpg
  text: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. '

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
callforaction:
  
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

{% include list-posts entries='3' offset='1' category='design' %}


