<template>
  <div>
    <p>{{count}}</p>
  </div>
</template>
<script>
export default{
computed:{
  count(){
    return this.$store.getters.count;
  }
}

}


</script>