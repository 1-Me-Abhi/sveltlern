<!-- <script>
  import Header from "./component/header.svelte";

  let name = "Abhi";
</script>

<Header  age={30} location="New York" />
<div>
  <label for="name">Name</label>
  <input type="text" bind:value={name} id="name" />
  <p>hello {name}</p>
</div> -->

<script>
  let count=$state(0);
  let increment = () => {
    count = count + 1;
  };
  let decrement = () => {
    count = count - 1;
  };
</script>
<h1>Count :{count}</h1>
<button onclick={increment}>Increment</button>
<button onclick={decrement}>Decrement</button><script>
  import Header from "./component/header.svelte";

  let name = "Abhi";
</script>

<Header  age={30} location="New York" />
<div>
  <label for="name">Name</label>
  <input type="text" bind:value={name} id="name" />
  <p>hello {name}</p>
</div>
