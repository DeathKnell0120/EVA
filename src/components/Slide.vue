<template>
  <div>
    <b-carousel class="hello"
      id="carousel-1"
      v-model="slide"
      :interval="5000"
      controls
      indicators
      img-width="1024"
      img-height="300"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="https://i.pinimg.com/originals/2b/75/34/2b7534a13579dcab2cea020c51b60105.jpg">
         <h1 id="txt1"><b>Somos una empresa lider en consultoria y asesoramiento para tu negocio</b></h1>
         <h4 id="txt2">Nos encargamos de todas tus necesidades</h4>
         </b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide 
      img-src="https://fondosmil.com/fondo/30534.jpg">
      <h1 id="txt1"><b>Somos una empresa lider en consultoria y asesoramiento para tu negocio</b></h1>
         <h4 id="txt2">Nos encargamos de todas tus necesidades</h4>
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide img-src="https://images2.alphacoders.com/900/900075.png">
      <h1 id="txt1"><b>Somos una empresa lider en consultoria y asesoramiento para tu negocio</b></h1>
         <h4 id="txt2">Nos encargamos de todas tus necesidades</h4>
      </b-carousel-slide>

    </b-carousel>
  </div>
</template>

<script>
  export default {
      name: "Slide"
  }
</script>