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
        grid-template-columns: 1fr [col-start] 2fr 1fr);
        grid-template-rows: repeat(6, 2fr [row-start]);
        grid-column-gap: 10px;
        grid-row-gap: 10px;
        align-items: center;
        justify-items: center;
    }
    .logo {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 2;
        grid-row-end: 3;
        align-self: center;
        justify-self: center;
    }
    .heading {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 3;
        grid-row-end: 4;
        align-self: center;
        justify-self: center;
    }
    .message {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 4;
        grid-row-end: 5;
        align-self: center;
        justify-self: center;
        color: #C09853;
        border-radius: 3px;
        border-color: #C09853;
        background-color: #FCF8E3;
        padding: 10px;
    }
    #adc-logo {
        width: 25%;
        height:25%;
    }
</style>
<article id="status-grid" class="container">
    <section class="logo">
        <img id="adc-logo" src="./arctic-logo.png" alt="" />
    </section>
    <section class="heading">
        <h1>Arctic Data Center Status</h1>
    </section>
    <section class="message">
        Due to a network upgrade, the Arctic Data Center will be unavailable 
        between 11:00 PM Pacific Daylight Time on Monday June 15th and 6:30 AM 
        Pacific Daylight Time on Tuesday June 16th. We apologize for the 
        inconvenience. Please contact support@arcticdata.io if you have any questions. 
   </section>
</article>
