<script lang="ts">
    import "../../styles/view.css";
    export let id: string;
    export let height: string = "100vh";
</script>

<section {id} style="height: ${height};">
    <div
        class="head"
        data-aos="fade-up"
        data-aos-duration="200"
        data-aos-easing="ease-in-sine"
    >
        <slot name="head" />
    </div>
    <slot name="content" />
</section>
