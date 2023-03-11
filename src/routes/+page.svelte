<script>
 let title = 'Welcome'

 const uptateTitle = () => {
    title = "something completely diferent"
 }

 
</script>

<div class="index">
    <h2>{title}</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nisi provident labore perspiciatis voluptatem possimus similique dolores repudiandae blanditiis atque ut temporibus quod fugiat odit, amet magnam facere, doloremque omnis quas.</p>

    <button on:click={uptateTitle}>change title</button>
    <input type="text" bind:value={title}>

    <div>
        <a href="/guides">View Guides</a>
        <a href="/about">About</a>
    </div>

    
</div>

<style>
    .index {
        text-align: center;
        display: block;
        margin: 20px auto;
    }
</style>