<script lang="ts">
    export let title: string;
    export let description: string;
    export let icon: string;
</script>

<div class="feature" data-aos="flip-up" data-aos-duration="500" data-aos-offset="200">
    <img src="/icons/{icon}.svg" alt="lightweight" />
    <div>
        <h2>{title}</h2>
        <p>{description}</p>
    </div>
</div>

<style>
    .feature {
        display: grid;
        grid-template-columns: 0.4fr 1.6fr;
        grid-template-rows: 1fr;
        gap: 0px 0px;
        grid-template-areas: "icon body";
        justify-items: center;
        align-items: center;
    }

    .feature img {
        grid-area: icon;
        margin: 0;
        height: 50px;
        filter: invert(57%) sepia(91%) saturate(1145%) hue-rotate(332deg)
            brightness(96%) contrast(93%);
    }

    .feature div {
        grid-area: body;
        margin-left: 1vw;
    }

    .feature div h2 {
        font-family: "Roboto", sans-serif;
        color: #445055;
        margin: 0;
        margin-top: 2vh;
        font-size: 1.5em;
    }

    .feature div p {
        font-family: "Roboto", sans-serif;
        color: #999f93;
        font-size: 1em;
        margin-top: 0vh;
    }

    
</style>
