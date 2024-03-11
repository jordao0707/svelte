<script lang="typescript">
	let counter = 0;
	function increment() {
		counter ++;
		// fetch('https://jsonplaceholder.typicode.com/posts/1')
		// 	.then((response) => response.json())
		// 	.then((json) => console.log(json));
	}
</script>

<h1>Welcome to Spotify Discover</h1>
<button on:click={increment}>{counter}</button>

<style>
    h1{
        font-family: Arial, Helvetica, sans-serif;
    } 

	button { 
        width: 8rem;
        
        padding: 1rem;
        
        border: none;
        border-radius: 1rem;
		
        background-color: rgb(54, 134, 108);

        &:hover{
            background-color: rgb(59, 121, 100);
        }
	}
</style>
