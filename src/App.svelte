<script>
	export let name;
	import Quiz from './Quiz.svelte';
</script>

<main>
	<h1>Hello {name}!</h1>
	<Quiz quizName="New Quiz"/>
</main>

<style>
	h1 {
		color: red;
	}
</style>