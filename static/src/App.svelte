<script>
    let num = 0

    let count = () => {
        num += 1
    }
</script>

<h1>Counter Sapmle</h1>

<p>Num is {num}</p> 

<button on:click={count}>
    Count
</button>