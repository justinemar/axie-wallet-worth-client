<script>
    import compact from "../utils/compact";
</script>



<div class="wallet">
    <p>ronin:96faa503b8558b4d2554d3d3669b96a2c8d5e821</p>
    <p><span class="p-highlight">{compact(420000)}</span> USD</p>
</div>


<style>
    .wallet {
        padding: 5px;
        background: #02213C;
        margin-top: 5px;
        margin-bottom: 5px;
        display: flex;
        justify-content: space-around;
    }
    .wallet p:first {
        flex-grow: 1;
    }
    .wallet > p {
        font-size: 17px;
        font-weight: bolder;
    }
</style>