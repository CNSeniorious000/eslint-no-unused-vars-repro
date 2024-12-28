{#if true}
  {#each [1, 2, 3] as a}
    {a}

    <!-- eslint-disable-next-line no-unused-vars -->
    {@const _ = console.error({ a })}

  {/each}
{/if}
