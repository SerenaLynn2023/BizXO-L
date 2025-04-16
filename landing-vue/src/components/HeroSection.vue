<template>
    <section class="hero">
      <video autoplay muted loop class="hero-video">
       <source :src="videoUrl" type="video/mp4"/>
        Votre navigateur ne supporte pas la vidéo.
      </video>
      <div class="hero-content">
        <h1>BizXO — L’élite du placement exécutif</h1>
        <p class="coming-soon"> Notre site complet arrive très bientôt. Restez connectés !</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'HeroSection',data(){
        return{
            videoUrl : require('@/assets/couverture.mp4')
        }
    }
  }
  </script>
  
  <style scoped>
  .hero {
    position: relative;
    height: 100vh;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #000;
  }
  
  .hero-video {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: 0;
    opacity: 0.6;
  }
  
  .hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
    color: white;
    padding: 0 20px;
  }
  
  .hero-content h1 {
    font-size: 2.8rem;
    font-weight: bold;
    color: #ffffff;
    margin-bottom: 15px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
  }
  
  .coming-soon {
    font-size: 1.2rem;
    font-style: italic;
    color: #f8f8f8;
    background-color: rgba(30, 30, 30, 0.5);
    padding: 10px 20px;
    border-radius: 8px;
    display: inline-block;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  </style> 


<!-- 
   <template>
    <div style="background-color: pink; padding: 50px;">
      <h1>TEST HERO SECTION</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeroSection'
  };
  </script> -->
  