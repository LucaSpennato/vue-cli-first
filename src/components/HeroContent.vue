<template>
  
  <div class="container-fluid">
    <div class="row">
        <div id="hero" class="row col-12">
            <div class="col-2 offset-3 align-self-center">
                <TitleComponent/>
            </div>
        </div>
    </div>
  </div>

</template>

<script>
import TitleComponent from './TitleComponent.vue'

export default {
    name: 'HeroTop',
    components: {
        TitleComponent,
    }
}
</script>

<style>

#hero{
    background-image:url(../assets/6mro3n.jpg);
    height: 30rem;
    background-position: center;
    background-size: contain;
    background-repeat: no-repeat;
    width: 100vw;
}

</style>