<script lang="ts">
    import type { LayoutData } from './$types';

    export let data: LayoutData;
</script>

<slot />

<style lang="scss">
    @import '../lib/style/index.scss';
</style>
