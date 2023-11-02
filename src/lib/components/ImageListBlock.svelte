<script lang="ts">
	export let title: string;
	export let image: string;
</script>

<div class="d-flex align-items-center">
	<div
		class="d-flex my-image align-items-center justify-content-center rounded-1"
		style="background-image:url({image})" />
	<div class="flex-grow-1 display-6 px-5">{title}</div>
</div>

<style>
	.my-image {
		min-height: 10em;
		min-width: 20em;
		background-repeat: no-repeat;
		background-size: cover;
	}
</style>
