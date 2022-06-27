<div class="container">
    <div>
        <h1>hi! welcome to mc.kayt.dev!</h1>
        <p>this is the home for all my old server worlds, and hopefully my resourcepacks in the future!</p>
    </div>
    <div>
        <h2>old server worlds?</h2>
        <p>yup! all the worlds that have appeared in my streams or videos will be available to download <a href="/worlds">here</a>!</p>
        <h2>hold on, <em>your</em> resourcepacks?</h2>
        <p>hopefully! i have a few packs that i made for myself and i'll eventually upload them here! i was initially inspired by
            <a href="https://vanillatweaks.net">vanilla tweaks</a> but there were a few ideas i felt like were missing, so i made my own!</p>
    </div>
</div>

<style lang="scss">
    .container {
        div {
            width: 50vw;
            @include descending-width;
            margin-bottom: 1rem;
        }
    }

    .bg-remove {
        background-color: unset !important;
        margin-bottom: 10rem;
        
        div {
            display: grid;
            width: 70vw;
            grid-template-columns: 1fr 1fr;

            @include lg-screen {
                grid-template-columns: 1fr;
                justify-items: center
            }

            @include descending-width;
        }
    }
</style>