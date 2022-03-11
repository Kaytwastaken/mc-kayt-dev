<div class="container">
    <div>
        <h1>Kaytostrophic Tweaks</h1>
        <h2>Minecraft but ✨slightly different✨</h2>
        <p>Kaytostrophic Tweaks is a collection of modular resourcepacks that make a bunch of small tweaks to the vanilla Minecraft experience!</p>
    </div>
</div>

<div class="container bg-remove">
    <div>
        <div>
            <a href="/tweaks/netherite-helmet"><h3>Netherite Helmet</h3></a>
            <p>Replaces the default Netherite Helmet with a texture that's consistent with the other helmets.</p>
        </div>
        <div>
            <a href="/tweaks/crown"><h3>Golden Crown</h3></a>
            <p>Replaces the default Gold Helmet with a crown.</p>
        </div>
        <div>
            <a href="/tweaks/parrots"><h3>LGBTA Pride Flag Parrots</h3></a>
            <p>Replaces the 5 parrot colors with Lesbian, Gay, Bi, Trans, and Ace flags!</p>
        </div>
        <div>
            <a href="/tweaks/elytra"><h3>Halloween Elytra</h3></a>
            <p>Replaces the Elytra with a purple-orange gradient.</p>
        </div>
    </div>
</div>

<style lang="scss">
    .container {
        div {
            width: 50vw;

            @include descending-width
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

            div {
                display: block;
                background-color: $teal;
                border-radius: 1rem;
                padding: 1rem;
                margin: 1rem;
                max-width: 30vw;
                min-width: 20vw;

                @include lg-screen {
                    max-width: 50vw;
                    // max-width: 75%;
                    min-width: unset;
                }
            }
        }
    }
</style>