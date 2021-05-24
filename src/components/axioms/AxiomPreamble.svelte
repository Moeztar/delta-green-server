<script type="ts">
  import Typewriter from 'svelte-typewriter';
  export let onFinish;
</script>

<Typewriter cascade on:done={onFinish}>
 
  <br />
  <span class="text-delta-green">It all comes back to the same old mission:</span>
  <ul>
    <li> Find the threat </li>
    <li> Stop the threat </li>
    <li> Cover it up so it's like the threat never happened </li>
  </ul>
  <br />
</Typewriter>
