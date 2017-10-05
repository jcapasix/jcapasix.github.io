---
layout: post
title: jekyll + DISQUS
categories: Github
---

![_config.yml]({{ site.baseurl }}/images/j_plus_d.png)

Cada vez las cosas se hacen de forma casi automática, no es algo de lo que deberíamos sorprendernos, a este paso un día los programadores seremos programados. 

Recuerdo que cuando estaba en la universidad configurar un blog en github era una tarea titánica, hoy solo basta con hacer lo siguiente.

1. Fork de https://github.com/barryclark/jekyll-now
2. Cambiar el nombre del repositorio por username_github.github.io
3. Crear una cuenta en https://disqus.com/
4. En _config.yml cambiar la variable disqus: por disqus: nombre_site_disqus


Ejemplo en 3, 2, 1:

1. Fork de https://github.com/barryclark/jekyll-now a https://github.com/jcapasix
2. cambio el nombre de jekyll-now por jcapasix.github.io
3. bajo el repositorio de nombre jcapasix.github.io a mi máquina
4. creo una cuenta en https://disqus.com/ 
5. creo un nuevo site en disqus de la forma jcapasix.disqus.com
6. modifico la variable disqus: a disqus: jcapasix
7. hago pull request a master y listo
