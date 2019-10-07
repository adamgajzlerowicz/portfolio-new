<script>
    import Image from "svelte-image";
    export let project
</script>

<style>
    h1 {
        color: purple;
    }
</style>

<h1>
    {project.title}
    <Image src={`images/${project.image}`} alt=""/>
</h1>
