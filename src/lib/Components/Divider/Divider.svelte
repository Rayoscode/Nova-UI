<script>
	export let color = 'var(--border-color)';
	export let size = 2;
	export let className = '';
</script>

<hr class="ui-divider {className}" style="border-color:{color}; border-top-width:{size}px; " />
