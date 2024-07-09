<script>
export default {
    name: 'AppFooter',
}
</script>


<template>
    <footer>
        <!-- prima fascia footer blu  -->
        <div class="iconandmerc">
            <div>
                <img src="/public/img/buy-comics-digital-comics.png" alt="tablet con dc logo">
                <span>DIGITAL COMICS</span>
            </div>

            <div>
                <img src="/public/img/buy-comics-merchandise.png" alt="t-shirt dc">
                <span>DC MERCHANDISE</span>
            </div>

            <div>
                <img src="/public/img/buy-comics-subscriptions.png" alt="cards">
                <span>SUBSCRIPTION</span>
            </div>

            <div>
                <img src="/public/img/buy-comics-shop-locator.png" alt="Segnapost">
                <span>COMIC SHOP LOCATOR</span>
            </div>

            <div>
                <img src="/public/img/buy-dc-power-visa.svg" alt="Batteria">
                <span>DC POWER VISA</span>
            </div>
        </div>

        <!-- seconda parte footer  -->
         <div class="colonnine">

            <div class="firstcol">
                <div class="dccomics">
                    <h4>DC COMICS</h4>
                    <span>Characters</span>
                    <span>Comincs</span>
                    <span>Movies</span>
                    <span>TV</span>
                    <span>Games</span>
                    <span>Videos</span>
                    <span>News</span>
                </div>
                <div class="shop">
                    <h4>SHOP</h4>
                    <span>Shop DC</span>
                </div>
            </div>

            <div class="secondcol">
                <h4>DC</h4>
                <span>Terms of Use</span>
                <span>Privacy policy (New)</span>
                <span>Ad Choices</span>
                <span>Advertising</span>
                <span>Jobs</span>
                <span>Subscriptions</span>
                <span>Talemnt Worksghops</span>
                <span>CPSC Certificates</span>
                <span>Ratings</span>
                <span>Shop Help</span>
                <span>Contact Us</span>
            </div>

            <div class="threadcol">
                <h4>SITES</h4>
                <span>DC</span>
                <span>MAD Magazine</span>
                <span>DC Kinds</span>
                <span>DC Univers</span>
                <span>DC Power Visa</span>
            </div>
            
         </div>

         <!-- terza parte -->
          <div class="singup">

            <div class="button">
                <a href="#">SING-UP NOW!</a>
            </div>

            <div class="followus">

                <h4>FOLLOW US </h4>

                <i class="fa-brands fa-facebook"></i>

                <i class="fa-brands fa-twitter"></i>

                <i class="fa-brands fa-youtube"></i>

                <i class="fa-brands fa-pinterest"></i>

                <i class="fa-solid fa-location-dot"></i>

            </div>
          </div>
    </footer>

</template>

<style>
/* regole generali footer  */
footer{
    width: 100%;
    min-height:120px;
    background-color: white;
}

/* regole primo layout  */

.iconandmerc{
    background-color: blue;
    height: 160px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.iconandmerc div{
    display: flex;
    align-items: center;
}

.colonnine{
    background-color: grey;
    height: 420px;
}

footer .iconandmerc img{
    width: 35px;
}

/* regole secondo layout  */

.colonnine{
    background-image: url(/public/img/dc-logo-bg.png);
    background-color: black;
    background-repeat: no-repeat;
    background-position: 280px;
    color: white;
    display: flex;
}

/* first colonnina rule  */
.firstcol , .secondcol , .threadcol{
    margin: 20px 30px;
}


.dccomics{
    display: flex;
    flex-direction: column;
}

/* second colonnina rule  */

.secondcol{
    display: flex;
    flex-direction: column;
}

/* thread colonnina rule  */

.threadcol{
    display: flex;
    flex-direction: column;
}


/* regole terzo layout  */

.singup{
    background-color:#303030 ;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

a{
    text-decoration: none;
    color: white;
}

.button{
    height: 30px;
    width: 200px;
    background-color: #303030;
    border: solid blue 2px;
    text-align: center;
}

.followus{
    color: white;
    font-size: 20px;
    display: flex;
}

.followus i{
    margin:0 10px;
}

</style>