<script context="module">
    export const load = ({error}) => {
        console.error("The __error.svelte component saw an error:", error);
        return {
            props: {}
        }
    }
</script>

<h1>Friendly Error Page</h1>