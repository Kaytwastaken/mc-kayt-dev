<footer>
    <div>
        <a href="https://pk.kayt.dev">PK-web</a>
        <a href="https://twitter.com/kayt_was_taken">Twitter</a>
        <a href="https://github.com/kaytwastaken">Github</a>
        <a href="https://instagram.com/kayt_was_taken">Instagram</a>
        <a href="/credits">Open source credits</a>
    </div>
    <img src="/images/mc-kayt-dev-foot.png" alt="">
</footer>

<style lang="scss">
    footer {
        display: flex;
        justify-content: center;
        color: $text;

        img {
            z-index: -2;
            position: fixed;
            // position: absolute;
            bottom: 0;
            left: 0;
            // width: 100vw;
        }
            
        div {
            z-index: -1;
            position: fixed;
            bottom: 0;
            // height: calc(100vw * .06875);
            height: 132px;
            width: 50vw;
            
            @include descending-width;
            
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            grid-template-rows: 2em 2em;
            justify-items: center;
            align-items: center;
            align-content: center;

            @include xs-screen {
                grid-template-columns: 1fr 1fr 1fr;
            }

        }
    }
</style>