<template>
   <div class="card-panel grey lighten-5 z-depth-1">
      <div class="row valign-wrapper">
         <grid tamanho="4">
            <img src="https://materializecss.com/images/yuna.jpg" alt="" class="circle responsive-img"> <!-- notice the "circle" class -->
         </grid>
         <grid tamanho="8">
            <span class="black-text">
               <h5>Maria Silva</h5>
               Add the "circle" class to it to make it appear circular.
            </span>
         </grid>
      </div>
   </div>   
</template>

<script>

   import Grid     from '@/components/layouts/Grid'

   export default {
      name: 'CardMenu',
      components: {
         Grid
      },
      props: [],
      data() {
         return {

         }
      }
   }
</script>