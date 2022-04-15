<template>
	<aside class="el-main">
		<slot></slot>
	</aside>
</template>

<script lang="ts">
export default {
	name: 'ElMain',
}
</script>

<script setup lang="ts"></script>

<style lang="scss" scoped>
@import '../../styles/mixin.scss';
@include b(main) {
	display: block;
	flex: 1;
	flex-basis: auto;
	box-sizing: border-box;
	padding: $--main-padding;
}
</style>
