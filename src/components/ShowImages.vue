<script setup lang="ts">

import imgName from "@/assets/img/img_asset.webp" ;

</script>

<template>
  <div>
    
    <h3>
        Loading Images in Vue 3

    </h3>
    <p>This was added to vite.config.ts just so the app id not running the in root folder. </p>
    <pre>
  build: {
    rollupOptions: {
      external: [
        "subfolder"
      ],
    },
  },  
    </pre>
    <p>
      Using the pulic folder. Works in dev but wont build.
      <pre>
          &lt;img src=&quot;/subfolder/images/img_pub.webp&quot; alt=&quot;Public Img&quot;&gt;
      </pre> 
      <img src="/subfolder/images/img_pub.webp" alt="Public Img"> 
    </p>
    <p>
     Importinf the image does work and it's the onlt way
     <pre>
       import imgName from "@/assets/img/img_asset.webp" ;
       &lt;img :src=&quot;imgName&quot; alt=&quot;SRC Img&quot;&gt;
     </pre>
       <img :src="imgName" alt="SRC Img">
    </p> 
    
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

pre {
  font-weight: 600;
}  
</style>
