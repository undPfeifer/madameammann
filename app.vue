<template>
  <navbar />
  <Index />
</template>

<script>
import Index from './pages/index.vue' // adjust path if needed

export default {
  components: {
    Index
  }
}
</script>


<style>

@font-face {
  font-family: 'geist-bold';
  src: url('/assets/font/geist/Geist-Bold.otf');
}
@font-face {
  font-family: 'geist-semi';
  src: url('/assets/font/geist/Geist-SemiBold.otf');
}
@font-face {
  font-family: 'geist-medium';
  src: url('/assets/font/geist/Geist-Medium.otf');
}
@font-face {
  font-family: 'geist-re';
  src: url('/assets/font/geist/Geist_Regular.otf');
}


:root {
  --green: #079210;
  --black: #ffffff;
  --bg: rgb(255, 255, 255);
}

a {
  text-decoration: none;
}

  * {
    
    margin: 0px;
    padding: 0px;

    background-color: var(--bg);
    
    
    
    font-family: 'geist-regular';
    font-weight: 500;
    letter-spacing: -0.3px;
    color: var(--green);
    
  }

  p {
    font-family: 'Times New Roman', Times, serif;
    font-size: 18px;
    line-height: 1.22;
  }

  .bold {
    font-weight: 600;
  }

  .times {
    font-family: 'Times New Roman', Times, serif;
  }


  img {
    max-width: 100%;
    object-fit: cover;
    border-radius: 1px;
  }

  .main-padding{
    padding: 20px;
  }

  .papa {
    display: flex;
    flex-direction: row;
    justify-content: center;
    
  }

  .content--container{
    max-width: 1100px;
  }



  h1 {
    font-size: 50px;
    line-height: 1;
    letter-spacing: -2px;

    margin-bottom: 20px;

  }

  h2 {
    font-size: 50px;
  }

  h3 {
    font-size: 32px;
  }
</style>
