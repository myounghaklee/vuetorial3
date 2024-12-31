<template>
	<div>
		<TheNav></TheNav>
		<TheView></TheView>
	</div>
</template>

<script>
import TheNav from './components/TheNav.vue';
import TheView from './components/TheView.vue';
export default {
	components: {
		TheNav,
		TheView,
	},
	setup() {
		const message = ref("안녕하세요");

		return {
			message,
		};
	},
};
</script>

<style lang="scss" scoped></style>
