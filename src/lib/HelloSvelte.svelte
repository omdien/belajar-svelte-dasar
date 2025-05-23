<script>
    // console.log("Hello Svelte");
    const name = "Svelte";
    const src = "https://www.programmerzamannow.com/img/pzn.png";
</script>

<style>
    h1 {
        color: #ff3e00;
    }
</style>

<!-- <h1>Hello Svelte!</h1> -->

 <!-- Text Expression -->
<h1>Hello {name.toUpperCase()}!</h1> 

<!-- Dinamic Attribute Binding -->
<!-- <img src={src} alt="PZN Logo"> -->
<!-- atau -->
<img {src} alt="PZN Logo">
