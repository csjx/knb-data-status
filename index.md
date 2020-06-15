Arctic Data Center Status

<style>
    html, body {
         margin: 0px;
         padding: 0px;
         height: 100%;
         width: 100%
     }
    .container {
        display: grid;
        height: 100%;
        width: 100%;
        grid-template-columns: repeat(3, 1fr [col-start]);
        grid-template-rows: repeat(3, 1fr [row-start]);
        grid-column-gap: 10px;
        grid-row-gap: 10px;
        align-items: center;
        justify-items: center;
    }
    .item {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 2;
        grid-row-end: 2;
    }
    #orcid-logo {
        width: 10%;
        height:10%
    }
</style>

<article id="button-grid" class="container">
    <section class="item">
        <img id="orcid-logo" src="./img/orcid_64x64.png" alt="" />
    </section>
</article>
