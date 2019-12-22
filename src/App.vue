<template>
   <div>
      <header>
         <nav-bar cor="green darken-1" url="#" logo="Social" />
      </header>

      <main>
         <div class="container">
            <div class="row">
               <Grid tamanho="4">
                  Menu
               </Grid>
               <Grid tamanho="8">
                  <router-view/>
               </Grid>
            </div>
         </div>
      </main>

      <footer>
         <rodape cor="green darken-1" ano="2019" logo="Social" descricao="Um descrição do site">
         <li><a class="grey-text text-lighten-3" href="#!">Link 1</a></li>
         <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
         <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
         <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>      
         </rodape>
      </footer>
   </div>
</template>

<script>

   import NavBar from '@/components/layouts/NavBar'
   import Rodape from '@/components/layouts/Rodape'
   import Grid   from '@/components/layouts/Grid'

   export default {
      name: 'app',
      components: {
         NavBar, Rodape, Grid
      }
   }

</script>

<style>

</style>
