<script context="module">
  export const prerender = true;
</script>

<script>
  import '../app.css';
  import Modal from '$lib/Modal.svelte';
</script>


<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
Modal:
<Modal/>
Index:
<form name="will-attend" method="POST" netlify-honeypot="bot-field" data-netlify="true">
  <input type="hidden" name="form-name" value="will-attend" />
  <label for="name">Name</label>
  <input name="name" id="name" required placeholder="Name" type="text" />
  <input type="submit" value="Submit" />
</form>
No netlify:
<form>
  <input type="hidden" name="form-name" value="will-attend" />
  <label for="name">Name</label>
  <input name="name" id="name" required placeholder="Name" type="text" />
  <input type="submit" value="Submit" />
</form>