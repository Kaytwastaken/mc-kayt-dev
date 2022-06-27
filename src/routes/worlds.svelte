<svelte:head>
    <title>Worlds | mc.kayt.dev</title>
    <meta name="description" content="old kaytostrophic network server worlds">
    <meta name="keywords" content="kayt,dev,minecraft,worlds">
</svelte:head>

<div class="container">
    <div>
        <h1>Old server worlds</h1>
        <p>each time i make a new server world, the previous one will be uploaded here!</p>
    </div>
    <div>
        <a href="https://kayt.dev/static/worlds/resurrection-16.5.zip">resurrection-16.5 (1.3GB)</a>
        <a href="https://kayt.dev/static/worlds/vybe-smp.zip">vybe-smp.zip (507MB)</a>
        <a href="https://kayt.dev/static/worlds/surv-20-07.zip">surv-20-07.zip (1.2GB)</a>
    </div>
</div>

<style lang="scss">
    .container {
        div {
            width: 50vw;
            @include descending-width;
            display: flex;
            flex-direction: column;
            text-align: left;
            // small {
            //     margin-top: -1rem;
            // }
            // div {
            //     display: grid;
            //     grid-template-columns: 1fr 1fr 1fr 1fr; 
            // }
        }
    }
</style>