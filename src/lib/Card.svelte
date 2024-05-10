<script>
    export let src;
    export let caption;
    export let alt;
    export let Maori;
    export let money;
</script>

<div class="column">
    <img {src} {alt} />
    <div class="words">
        <p class="name">
            {caption}
            <span class="te-reo-maori"> - {Maori} </span>
        </p>
        <p class="price">${money}</p>
    </div>
</div>

<style>
    .te-reo-maori {
        font-style: italic;
    }
    .words {
        margin-left: 60px;
        margin-top: 100px;
    }
    img {
        width: 500px;
        margin-top: 20px;
        margin-bottom: 20px;
        display: flex;
        border: 15px solid white;
    }
    .column {
        display: flex;
    }
    p {
        font-family: "Passero One";
        font-size: 40px;
        margin-bottom: 10px;
        width: fit-content;
    }

    .price {
        background-color: #dcbea4;
    }

    .price:hover {
        background-color: #ff964585;
    }

    .name {
        background-color: #dcbea4;
    }
    img:hover + div.words > p {
        background-color: #ff964585;
    }

    img:hover {
        background-color: #ff964585;
        border-color: #ff964585;
    }

    .price {
        font-size: 35px;
    }
    @media screen and (max-width: 600px) {
        .column {
            width: 600px;
            display: block;
        }
    }
</style>
