<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->


<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';

    let myInfo = {
        title:"Info",
        item1:"Naz",
        item2:15,
        item3:"MBS"
    }
    let myHobby = {
        title:"Hobby",
        item1:"Cooking",
        item2:"Gaming",
        item3:"Sleeping",
    }
</script>

<Header title={"My Biography"} />
<Section {...myInfo} />
<Section {...myHobby} />
