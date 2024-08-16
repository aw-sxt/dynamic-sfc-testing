<template>
	<div>
		<span>{{ count }}</span>
		<button v-on:click="incrementCount">Increment</button>
	</div>
</template>

<script setup>
import {ref} from 'vue';
const count =? ref(0);

function incrementCount() {
	count.value++;
}

</script>