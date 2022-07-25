<script lang="ts">
    import View from "./view.svelte";
    import Feature from "../components/feature.svelte";
</script>

<View id="features">
    <div slot="head">
        <h2>Features</h2>
        <p>Discover some important features</p>
    </div>
    <div slot="content" class="content">
        <div class="features">
        <Feature title="Lightweight" description="Molecule is light as a feather and saves your RAM." icon="feather"/>
        <Feature title="Free & OpenSource" description="Molecule is completly open source and licensed under GNU AGPL3." icon="github"/>
        <Feature title="Extensible" description="You can extend Molecule according to your wishes and needs. Build your own extension! COMING SOON!" icon="puzzle"/>
        <Feature title="Themable" description="Scared to use whitemode? Build your own theme!" icon="paintbrush"/>
        <Feature title="In-App Updates" description="Download once and manage future updates directly in Molecule! COMING SOON!" icon="updates"/>
        <Feature title="Git Integration" description="Seamless integration with Git Version Control. COMING SOON!" icon="git"/>
        <Feature title="Native" description="Thanks to Flutter, Molecule is completely native and no webapp mess." icon="leaf"/>
        <Feature title="Modern" description="Empower your projects with Molecule for agile development" icon="rocket"/>
        </div>
    </div>
</View>

<style>
    .content {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        justify-content: center;
    }

    .features {
        width: 70vw;
        height: 80%;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: 1fr 1fr 1fr;
        gap: 0px 40px;
        grid-template-areas:
            ". . ."
            ". . ."
            ". . .";
    }
</style>
