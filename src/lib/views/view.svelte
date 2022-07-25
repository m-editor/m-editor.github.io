<script lang="ts">
    import "../../styles/view.css";
    export let id: string;
    export let height: string = "100vh";
</script>

<section {id} style="height: ${height};">
    <div
        class="head"
    >
        <slot name="head" />
    </div>
    <slot name="content" />
</section>
