<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción


    .row.justify-content-center.align-items-center.bg-1.py-4.px-4.px-md-0.mb-5
      .col-md-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/intro/img.svg' alt='Imagen introducción')
      .col-md-6.bg-white.br-20.p-4(data-aos="fade-left")
        p.mb-0 Apreciado aprendiz, bienvenido a este componente formativo, donde abordaremos la temática relacionada con la valoración de muestras según técnicas de análisis químico. En el siguiente video conocerá, de forma general, la temática que se estudiará a lo largo del componente formativo.


    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/gq_RBVKyxX4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Valorar muestras según técnicas de análisis químico


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
