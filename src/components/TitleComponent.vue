<template>
  <div>
    <h1 class="text-danger">
        {{ title }}
    </h1>
  </div>
</template>

<script>
export default {
    name: 'TitleComp',
    data: function(){
         return {
            title: 'La mia prima app con Vue CLI!',
        }
    },
}
</script>

<style>

</style>