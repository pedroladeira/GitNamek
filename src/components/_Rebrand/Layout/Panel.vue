<template>
    <div ref="ref-panel" class="border-b border-gray-500">
        <slot></slot>
    </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import Base from '../Base';

@Component
export default class Panel extends Vue {

    public mounted(): void {
        //
    }

}
</script>

<style scoped lang="scss">
  
</style>
