<script>
  import { onMount } from 'svelte';
  import { themeChange } from 'theme-change';
  import '../app.scss';

  onMount(() => {
    // Register theme change
    themeChange(false);
  });
</script>

<div class="flex flex-col justify-center items-center">
  <slot />
</div>
