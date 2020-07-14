<template>
  <div>
      data:{{count}} <br/>
      prop:{{msg}} <br/>
      <button @click="addCount">+</button>
  </div>
</template>

<script lang="ts" >
import {Component,Prop,Vue} from 'vue-property-decorator'
@Component
export default  class HelloWorld extends Vue{
    @Prop() private msg!: string;
    private count = 669;
    private addCount(){
        this.count++
    }
}
</script>

<style>

</style>