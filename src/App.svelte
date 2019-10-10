<script>
    import projects from './projects'
    import Project from './components/Project.svelte'
	import Intro from './components/Intro.svelte'
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>
<Intro />
{#each projects as project}
	<Project project={project} />
{/each}
