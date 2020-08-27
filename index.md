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
        grid-template-rows: .25fr 1fr .5fr 1fr 2fr;
        grid-column-gap: 10px;
        grid-row-gap: 10px;
        align-items: center;
        justify-items: center;
    }
    section {
      display: flex;
      justify-content: center;
      align-items: center;
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
        padding: 20px;
    }
    #knb-logo {
        width: 100%;
        height:100%;
    }
</style>
<article id="status-grid" class="container">
    <section class="logo">
        <img id="knb-logo" src="./knb-logo.png" alt="" />
    </section>
    <section class="heading">
        <h1>KNB Data Repository Status</h1>
    </section>
    <section class="message">
        Due to a campus network upgrade, the KNB Data repository will be unavailable 
        between 10:00 PM Pacific Daylight Time on Wednesday August 26th and 8:00 AM 
        Pacific Daylight Time on Thursday August 27th. We apologize for the 
        inconvenience. Please contact knb-help@nceas.ucsb.edu if you have any questions. 
    </section>
</article>
