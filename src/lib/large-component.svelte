<script lang="ts">
	import lodash from 'lodash';

	const array = [1, 2, 3];
</script>

{JSON.stringify(lodash.partition(array, (n) => n % 2))}
