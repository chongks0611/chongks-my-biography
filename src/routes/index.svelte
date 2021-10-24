<script>
	import Header from '$lib/Header.svelte';
	import Section from '$lib/Section.svelte';

	let myInfo = {
		title: 'Info',
		item1: 'Chong Khai Shin',
		item2: 14,
		item3: 'SMJK Jit Sin'
	};

    import Hobby from '$lib/Hobby.svelte';

    let myHobby = {
		title: 'Hobby',
		item1: 'Playing Musical Instruments',
		item2: 'Cooking',
		item3: 'Watching Youtube videos'
	};

    import Personality from '$lib/Personality.svelte'

    let myPersonality = {
		title: 'Personality',
		item1: 'Introvert',
		item2: 'Flexible',
		item3: 'Easy-going'
	};

    import Footer from '$lib/Footer.svelte'
</script>

<Header title="My Biography" />

<Section {...myInfo} />

<Hobby {...myHobby} />

<Personality {...myPersonality} />

<Footer gitHub="https://github.com/chongks0611/" />
