<script lang="ts">

    let a: string;

    $: a, myFunction();

    function myFunction() {
        console.log("Hello World!")
    }

</script>

<input bind:value={a}>