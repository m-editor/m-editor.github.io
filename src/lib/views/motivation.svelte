<script lang="ts">
    import View from "./view.svelte";
</script>

<View id="motivation">
    <div slot="head">
        <h2>Philosophy</h2>
        <p>Molecule's guiding principles</p>
    </div>
    <div slot="content" class="content">
        <div
            class="quote"
            data-aos="fade-right"
            data-aos-duration="500"
            data-aos-offset="200"
        >
            <img src="/icons/quote.svg" alt="Quote" />
            <p>
                Molecule is designed with a focus on productivity and good
                integration into your daily work rhythm.
            </p>
        </div>
        <div
            data-aos="fade-left"
            data-aos-duration="500"
            data-aos-offset="200"
            style="justify-self: end; flex-direction: row-reverse;"
            class="quote"
        >
            <img src="/icons/bar.svg" alt="Quote" />
            <p>
                Molecule places great emphasis on performance and is therefore
                very lightweight, unlike some other editors (based on Electron).
            </p>
        </div>
        <div
            class="quote"
            data-aos="fade-right"
            data-aos-duration="500"
            data-aos-offset="200"
        >
            <img src="/icons/activity.svg" alt="Quote" />
            <p>
                Molecule is currently in under active development, which will
                not change. Bugs are fixed quickly and feature requests are
                taken care of.
            </p>
        </div>
    </div>
</View>

<style>
    .content {
        display: grid;
        grid-auto-columns: 1fr;
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 1fr 1fr;
        gap: 0px 0%;
        grid-template-areas:
            "."
            "."
            ".";
        width: 80vw;
        padding-left: 10vw;
        padding-right: 10vw;
        height: 30vw;
    }

    img {
        filter: invert(57%) sepia(91%) saturate(1145%) hue-rotate(332deg)
            brightness(96%) contrast(93%);
        height: 30px;
        width: 30px;
    }

    .quote {
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    .quote p {
        font-size: 1.2vw;
        color: #999f93;
        margin-left: 10px;
        margin-right: 10px;
        font-family: "Roboto", sans-serif;
    }
</style>
