<script>
  import { page } from '$app/stores'
  import { signIn, signOut } from '@auth/sveltekit/client'
</script>

<button on:click={() => signIn('google')}>Sign In</button>
<code>{JSON.stringify($page.data)}</code>
