<template>
	<div>
		<p>Message is: {{ message }}</p>
		<input v-model="message" placeholder="edit me" />
	</div>
</template>

<script setup>
import {ref} from 'vue';
const message = ref(null);

</script>