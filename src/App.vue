<template>
	<div class="container center-content">
		<RouterView />
	</div>
</template>

<script>
export default {
	name: 'App',
	components: {},
}
</script>

<style lang="scss" scoped>
.container {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  max-width: 1200px;
}
</style>
