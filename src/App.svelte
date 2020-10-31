<script>
	import Todos from './components/Todos.svelte';

	let todos = [
        { id: 1, name: "Create Svelte Starter app", completed: true },
        { id: 2, name: "Create your first component", completed: true },
        { id: 3, name: "Complete the rest of the tutorial", completed: false },
        { id: 4, name: "Check reactiveness", completed: false },
    ]
</script>

<Todos {todos}/>