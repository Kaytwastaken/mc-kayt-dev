<nav>
    <a href="/">
        <span>
            <img src="/images/mc-kayt-dev.png" alt="" width="64">
            <h1>&#060;mc.kayt.dev/&#062;</h1>
        </span>
    </a>
    <span>
        <a sveltekit:prefetch href="https://kayt.dev">&#060;Kayt.dev/&#062;</a>
        <a sveltekit:prefetch href="/">Home</a>
        <a href="/tweaks">Tweaks</a>
        <!-- <a href="#">Coming soon?</a> -->
    </span>
</nav>

<style lang="scss">
    nav {
        // background-color: $bg-secondary;
        // padding: 0 33vw 0 33vw;
        color: $text;
        display: flex;
        justify-content: space-evenly;
        // margin-bottom: 2rem;
        align-items: center;
        flex-direction: row;
        background-color: #3890A8;

        @include xs-screen{
            flex-direction: column;
            align-items: flex-start;
        }

        * {
            padding: .5rem;
        }
        h1 {
            // background-image: $grad-logo-secondary;
            background-color: $yellow;
            color:transparent;
            -webkit-background-clip: text;
            background-clip: text;
        }
        a {
            text-decoration: none;
        }
        span {
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            * {
                padding: 0 1rem 0 1rem;
            }
            a {
                padding: 1rem 1rem 1rem 1rem;
                border-bottom: 2px solid $teal;
            }
            a:hover {
                border-bottom: 2px solid $yellow;
            }
        }
        img {
            display: unset;
            @include xs-screen {
                display: none;
            }
        }
    }
    
</style>