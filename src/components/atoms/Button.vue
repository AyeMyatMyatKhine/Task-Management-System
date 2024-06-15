<template>
    <button :type="type" @click="handleClick" class="button">
        <slot></slot>
    </button>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent ({
    
});
</script>
