<script>
    import SvgIcon from './util/SvgIcon.svelte';
    export let color;
</script>

<SvgIcon color={color}>
    <path fillOpacity=".3" d="M17 4h-3V2h-4v2H7v9h10V4z" /><path d="M7 13v9h10v-9H7z" />
</SvgIcon>