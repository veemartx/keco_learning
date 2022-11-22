<main>
    <div class="content">
        <div class="sliderCol">
            <div class="leftCol">
                <div class="punchline">
                    You Visit Kakamega Forest, <br /> We plant trees
                </div>
                <div class="tagline">
                    we plant trees. Kakamega Environmental Conservation Strives
                    to ensure that conservation is easy and attainable and the
                    community is conscious about environmental restoration
                </div>
            </div>

            <div class="rightCol" />
        </div>
    </div>
</main>

<style>
    main {
        min-height: 80vh;
        /* background-color: red; */
    }

    .sliderCol {
        display: flex;
    }

    .leftCol {
        flex: 1;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .rightCol {
        background-image: url(/assets/images/tree_map.png);
        background-position: center;
        background-size: contain;
        background-repeat: no-repeat;
        flex: 1;
        height: 80vh;
    }

    .punchline {
        font-size: 50px;
        color: #105056;
        font-weight: 700;
        line-height: 55px;
        text-align: left;
    }

    .tagline {
        font-weight: 100;
        font-size: 18px;
        color: rgba(19, 86, 88);
        padding-top: 1em;
        text-align: left;
    }
</style>
