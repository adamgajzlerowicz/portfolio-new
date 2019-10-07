<script>
    import projects from './projects'
    import Project from './components/Project.svelte'
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

{#each projects as project}
	<Project project={project} />

{/each}
<h1>Hello {name}!
</h1>
