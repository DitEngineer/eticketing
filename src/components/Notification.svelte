<script>
    export let heading="";
    export let description="";
</script>

<div class="container">
    <div class="graphic"></div>
    <div class="info">
        <p class="heading">{heading}</p>
        <p class="description">{description}</p>
    </div>
</div>

<style>
    *{
        padding: 0;
        margin: 0;

        box-sizing: border-box;
    }

    .container{
        height: max-content;
        width: 100%;

        display: flex;
        justify-content: space-between;
        gap: 8px;

        padding: 8px;

        border-radius: 5px;

        outline: 1px solid #f3f3f3;
    }

    .graphic{
        height: 72px;
        width: 25%;
    }

    .info{
        height: 72px;
        width: 75%;
    }

    .info .heading{
        color: #000;
        font-weight: 500;
    }

    .description{
        color: #999;
    }
</style>