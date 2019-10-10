<script>
    import projects from './projects'
    import Project from './components/Project.svelte'
	import Intro from './components/Intro.svelte'
	export let name;
</script>

<style>
	.page {
		background-color: rgb(28, 28, 28);
	}
</style>

<div class="page">
	<Intro />
	{#each projects as project}
		<Project project={project} />
	{/each}
</div>
