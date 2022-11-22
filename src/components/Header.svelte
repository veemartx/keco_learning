<main>
    <div class="wrapper">
        <div class="content">
            <div class="mainHeader">
                <div class="logo">
                    <img
                        src="/assets/images/logo.png"
                        alt="logo"
                        class="mainLogo"
                    />
                </div>
                <div class="spacer" />

                <div class="mnav">
                    <div class="nav">Home</div>
                    <div class="nav">About</div>
                    <div class="nav">How It Works</div>
                    <div class="nav">Csr Proposals</div>
                    <div class="nav">FAQs</div>
                    <div class="nav">Contact</div>
                </div>
            </div>
        </div>
    </div>
</main>

<style>
    main {
        background: #ffa500;
    }

    .mainHeader {
        display: flex;
        padding-top: 5px;
        padding-bottom: 5px;
    }

    .logo {
        flex: 1;
    }

    .spacer {
        flex: 1;
    }

    .mainLogo {
        max-width: 10em;
        height: auto;
    }

    .mnav {
        flex: 4;
        display: flex;
        justify-content: space-between;
        background: rgba(128, 128, 0, 0);
        width: 100%;
        align-items: center;
    }
</style>
