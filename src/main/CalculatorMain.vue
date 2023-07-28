<template>
    <div class="calculator">
        <display-calculator />
        <button-calculator />
    </div>
</template>

<script>

import DisplayCalculator from '../components/DisplayCalculator.vue';
import ButtonCalculator from '../components/ButtonCalculator.vue';

export default{
    components: {
        DisplayCalculator,
        ButtonCalculator
    }
}
</script>

<style>
.calculator {
    height: 320px;
    width: 235px;
    border-radius: 5px;
    overflow: hidden;

    display: grid;
    grid-template-columns: repeat(4, 25%);
    grid-template-rows: 1fr 48px 48px 48px 48px 48px;
}
</style>