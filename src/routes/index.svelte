<script>import Header fr
    om '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';

    let myInfo = {
        title: "Info",
        item1: "Adibah",
        item2: 18,
        item3: "Telebort",
    }

    let myHobby = {
        title: "Hobby",
        item1: "Play games",
        item2: "Swimming",
        item3: "Play badminton",
    }

</script>

<Header title="My Biography" />
<Section {...myInfo}/>