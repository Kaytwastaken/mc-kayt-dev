<footer>
    <div>
        <a href="https://kayt.dev">kayt-dev</a>
        <a href="https://pk.kayt.dev">pk-web</a>
        <a href="https://github.com/kaytwastaken">github</a>
        <a href="/credits">credits/links</a>
    </div>
    <img src="/images/mc-kayt-dev-foot.png" alt="">
</footer>

<style lang="scss">
        footer {
            width: 100vw;
            display: flex;
            justify-content: center;
            margin-bottom: 2rem;
            position: fixed;
            bottom: 0;
        
        div {
            padding-top: 1rem;
            width: 50vw;
            
            @include descending-width;
            
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-template-rows: 2em 2em;
            justify-items: center;
            @include xs-screen {
                grid-template-columns: 1fr 1fr 1fr;
            }
            a {
                text-decoration: none;
            }
            a:hover {
                text-decoration: underline;
            }
        }

        img {
            z-index: -2;
            position: fixed;
            bottom: 0;
            left: 0;
        }
    }
</style>