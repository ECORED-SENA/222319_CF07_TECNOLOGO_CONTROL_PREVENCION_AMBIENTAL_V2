<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Aplicación de protocolos de análisis de muestras 

    .row.justify-content-center.align-items-center.bg-2.py-4.px-4.px-md-0.mb-4
      .col-md-5(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema1/img.png' alt='Imagen tema1')
      .col-md-6.bg-white.br-20.p-4(data-aos="fade-left")
        p.mb-0 Dentro de la química analítica, se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia. Los ámbitos de aplicación del análisis químico son muy variados, en la industria destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades entre otros.

    .row.justify-content-center.align-items-center
      .col-md-8.tema1.p-4
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj1.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Por esta razón
              p.mb-0 En esta unidad temática, se profundiza como se desarrolla en el análisis de las muestras que se lleva a cabo en el laboratorio. La química analítica es la rama de la química que tiene como finalidad el estudio de la composición química de un material o muestra, mediante diferentes métodos. Se divide en química analítica cuantitativa y química analítica cualitativa.
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj2.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Dentro de la química analítica
              p.mb-0 Se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia.
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj3.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Los ámbitos de aplicación
              p.mb-0 Del análisis químico son muy variados, en la industria se destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades.
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema1/img2.svg' alt='Imagen decorativa')  
  

    .row.justify-content-center.align-items-center.mb-5
      .col-md-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema2/img.png' alt='Imagen tema2')
      .col-md-8(data-aos="fade-left")
        p La #[b #[span.t-green química analítica]] es el estudio de cómo ensayar esos materiales para averiguar su composición elemental y molecular.
        p.bg-blue.p-4.mb-0 El poder determinar la composición química de sólidos, líquidos, gases, disoluciones y cualquier otro material nos permite comprender sus características y así poder evaluar sus usos o quizás descubrir de dónde vinieron o dónde han estado.
    
    p.text-center.mb-4(data-aos="fade") A continuación, le presentamos algunos elementos de orden teórico que favorecen la “inmersión” en el tema del #[b #[span.t-green análisis de muestras]].

    TabsC.color-acento-botones
      .py-4.py-md-5(titulo="Química analítica").bg-green2
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 Química analítica
            p La química analítica no solo nos permite resolver problemas específicos sino también descubrir mejores métodos para conseguirlo. La química analítica se ocupa de la separación, identificación y determinación de la composición relativa de una muestra de materia.
            p El análisis cualitativo identifica químicamente a las especies que hay en la muestra. El análisis cuantitativo establece la cantidad relativa de una o más de estas especies, o analitos, en términos numéricos.
            p Para poder realizar el análisis cuantitativo es necesario contar primero con información cualitativa. Tanto el análisis cualitativo como el cuantitativo precisan de una fase de separación.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema2/tab1.png', alt='Química analítica')
      .py-4.py-md-5(titulo="¿De qué se trata?").bg-green2
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 ¿De qué se trata?
            p La química analítica trata de la separación y caracterización de sustancias químicas que hacen parte de una muestra que bien puede ser considerada como contaminada por estas sustancias o que es importante determinar su presencia por razones de interés económico o toxicológico.
            p Casi siempre en el análisis químico se trata de encontrar la composición de la muestra y la estructura química de los componentes mediante sus métodos de análisis.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema2/tab2.png', alt='¿De qué se trata?')
      .py-4.py-md-5(titulo="Los métodos").bg-green2
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 Los métodos
            p Los métodos analíticos que dependen de la cantidad de muestra tomada pueden ser clasificados en:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                span 
                  b Macroanálisis: 
                  | sí la cantidad de muestra está comprendida aproximadamente entre 0.1 - 2 g.
              li 
                i.fas.fa-check
                span.mb-0 #[b Semimicroanálisis:] cantidad comprendida aproximadamente entre 0.01 a 0.05 g (10 a 50 mg).
              li 
                i.fas.fa-check
                span.mb-0 #[b Microanálisis:] de 1 a unos pocos miligramos (0.001g).
              li 
                i.fas.fa-check
                span.mb-0 #[b Ultra Microanálisis:] Determina una cantidad de material del orden de unos cuantos miligramos (0.001 mg = 1 g).     
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema2/tab3.png', alt='Los métodos')
      .py-4.py-md-5(titulo="Ciencia creadora").bg-green2
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 Ciencia creadora
            p Mientras el análisis químico es técnico, la química analítica es ciencia creadora y elaboradora de dicha técnica, para lo cual establece leyes y principios que justifican el por qué y el cómo de los procesos.
            p Divisiones del análisis químico. El análisis químico se divide en:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                span.mb-0 #[b Análisis químico cualitativo:]  tiene por objeto el reconocimiento o identificación de los elementos o de los grupos químicos presentes en una muestra. Las operaciones que se realizan son muy sencillas, entre las que podemos mencionar disolución de la muestra en un solvente adecuado, separación de impurezas, ya sea por decantación, filtración o centrifugación. El material que se requiere consiste en tubos de ensayos, vasos de precipitados, probetas, cápsulas de porcelana, papel de filtro.
              li 
                i.fas.fa-check
                span.mb-0 #[b Análisis químico cuantitativo:] determina las cantidades de los elementos y compuestos que componen una muestra y sus posibles relaciones químicas e incluso estructurales.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema2/tab4.png', alt='Ciencia creadora')
      .py-4.py-md-5(titulo="Reacciones").bg-green2
        .row.justify-content-center
          .col-md-7.mb-4.mb-md-0
            h4 Reacciones
            p La base en la que se fundamentan la mayoría de los procesos químicos analíticos son las reacciones químicas.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema2/tab5.png', alt='Reacciones')                        






      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
