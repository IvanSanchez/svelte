<ul>
	{#each items as item (item.id)}
		{#if item.id}
			<li>{item.name}</li>
		{/if}
	{/each}
</ul>