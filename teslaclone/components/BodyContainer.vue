<template>
    <div class="body">
      <div class="gallery_photo">
          <img src="https://static.wixstatic.com/media/670ab1_80f31deab79d4569a911fb8e59d5c337~mv2.jpg/v1/fill/w_700,h_372,al_c,q_80,usm_0.66_1.00_0.01/670ab1_80f31deab79d4569a911fb8e59d5c337~mv2.webp" alt="">
      </div>
      <div class="writings">
          <h4>BESPOKE TITANIUM BIKES</h4>
          <p>If you are looking for a titanium bicycle that’s custom made for  your needs, versatile, hi-tech, and long-lasting, you’ve come to the right place.
             Welcome to Nua Bikes!Test</p>
      </div>
    </div>
</template>

<script>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Barlow:wght@300;500&family=Open+Sans:wght@300&display=swap');
.body{
  display: flex;
  height: 100vh;
  margin: auto;

}

.gallery_photo{
  display: flex;
  flex-direction: column;
  width: 50%;
  position: relative;
  padding: 80px 30px ;
}

.writings{
  display: flexbox;
  width: 300px;
  justify-content: center;
  align-self: flex-start;
  flex-direction: row-reverse;
  position: relative;
  padding: 50px;
  margin-top: 200px;
  font: 'Barlow', sans-serif;
  font-size: 24px;
}


</style>