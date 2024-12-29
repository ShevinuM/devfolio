<script>
  export let id;
  export let url;
  export let iconClass;
  export let delay;
</script>

<li id={id} in:fade={{ delay }}>
  <a href={url} target="_blank" aria-label={id}>
    <i class={iconClass}></i>
  </a>
</li>