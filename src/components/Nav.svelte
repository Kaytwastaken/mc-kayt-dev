<nav>
    <a href="/">
        <h1>&#060;mc.kayt.dev/&#062;</h1>
    </a>
    <span>
        <a href="/">home</a>
        <a href="/worlds">worlds</a>
    </span>
</nav>

<style lang="scss">
    nav {
        background-color: $teal;
        color: $text;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        flex-direction: row;
        @include xs-screen{
            flex-direction: column;
            align-items: flex-start;
        }
        * {
            padding: .5rem;
        }
        h1 {
            color: $yellow;
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
                border-bottom: 1px solid $teal;
            }
            a:hover {
                border-bottom: 1px solid $yellow;
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