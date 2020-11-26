<template>
 <div>
     <a href="/www/index.html#/options" target="_blank">Popup</a> 
 </div>
</template>

<script lang="ts">
import ExampleComponent from 'components/ClassComponent.vue';
import { Vue, Component } from 'vue-property-decorator';

@Component({
  components: { ExampleComponent },
})
export default class PopupPage extends Vue {}
</script>
