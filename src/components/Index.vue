<template>
  <div class="body">
      <section>
        <div class="navigation">
            <i class="fas fa-angle-left"></i>
            <h3>Flights Results</h3>
        </div>
        <div class="intro-body"></div>
        <div class="box1">
            <p> <i class="fas fa-map-marker-alt pt"></i> Dubai, UAE</p>
            <p><i class="far fa-calendar pt"></i> Mar, 7, 2017</p>
            <p><i class="far fa-user pt"></i> 1 passenger</p>
            <p><i class="fas fa-wine-glass pt"></i> First Class</p>
            <p><i class="far fa-credit-card pt"></i> 800</p>
            <button>Edit Search</button>
        </div>
        <div class="info-div">
            <div class="box">
                <img src="../assets/1.jpg" alt="">
                <div class="box-details">

                    <div class="">
                            <span class="fa fa-star checked"></span>
                            <span class="fa fa-star checked"></span>
                            <span class="fa fa-star checked"></span>
                            <span class="fa fa-star checked"></span>
                            <span class="fa fa-star"></span>
                            
                        <i class="far fa-heart fr"></i>
                    </div>
                    <div class="pdt">
                        <h3>Jumeirah Creekside Hotel</h3>
                        <p>Garhoud Dubai</p>
                    </div>
                    <div class="">
                        <p class="fr2">$800.00</p>
                    </div>

                </div>
            </div>
        </div>

        <div class="info-div">
                <div class="box">
                    <img src="../assets/2.jpg" alt="">
                    <div class="box-details">
    
                        <div class="">
                                <span class="fa fa-star checked"></span>
                                <span class="fa fa-star checked"></span>
                                <span class="fa fa-star"></span>
                                <span class="fa fa-star"></span>
                                <span class="fa fa-star"></span>
                                
                            <i class="far fa-heart fr"></i>
                        </div>
                        <div class="pdt">
                            <h3>Dusit Thani Dubai</h3>
                            <p>Trade Center, Dubai</p>
                        </div>
                        <div class="">
                            <p class="fr2">$750.00</p>
                        </div>
    
                    </div>
                </div>
            </div>

            <div class="info-div">
                    <div class="box">
                        <img src="../assets/3.jpg" alt="">
                        <div class="box-details">
        
                            <div class="">
                                    <span class="fa fa-star checked"></span>
                                    <span class="fa fa-star checked"></span>
                                    <span class="fa fa-star checked"></span>
                                    <span class="fa fa-star"></span>
                                    <span class="fa fa-star"></span>
                                    
                                <i class="far fa-heart fr"></i>
                            </div>
                            <div class="pdt">
                                <h3>City Premiere Hotel Apartments</h3>
                                <p>Metro Access, Dubai</p>
                            </div>
                            <div class="">
                                <p class="fr2">$700.00</p>
                            </div>
        
                        </div>
                    </div>
                </div>

       <footer>
            <div class="footer">
                    <div class="tc">
                            <i class="fas fa-home"></i>
                            <br>
                            Home
                    </div>
                    <div class="tc">
                            <i class="fas fa-briefcase"></i>
                            <br>
                            Tours
                    </div>
                    <div class="tc">
                            <i class="fas fa-search"></i>
                            <br>
                            Explore
                    </div>
                    <div class="tc">
                            <i class="far fa-user"></i>
                            <br>
                           Profile
                    </div>
                </div>
       </footer>
    </section>

    <div class="sigin-in">
            <div class="first-div">
                   <div class="first-div-cnt">
                        <i class="fas fa-pizza-slice fa-5x"></i>
                        <h1>Sign Up</h1>
                   </div>
            </div>

            <div class="second-div">
                <div class="form">
                    <div class="form-div">
                        <label for="Full Name">Full Name</label>
                        <br>
                        <div class="input-div">
                            <input type="text" >
                            <i class="far fa-user"></i>
                        </div>
                    </div>

                    <div class="form-div">
                            <label for="E-mail">E-mail</label>
                            <br>
                            <div class="input-div">
                                <input type="text" >
                                <i class="far fa-envelope"></i>
                            </div>
                    </div>

                    <div class="form-div">
                            <label for="Full Name">Password</label>
                            <br>
                            <div class="input-div">
                                <input type="password" >
                                <i class="far fa-eye"></i>
                            </div>
                    </div>
                    
                    <button class="sign-up-btn">Sign Up</button>
                    <br>
                    <button class="sign-up-btn2"><span class="f1">Sign Up With</span> <span class="f2">Facebook</span></button>

                    <div class="signup-footer">
                        <p>Already have an account? <span class="sf-t">Sign in</span></p>
                    </div>
                </div>
            </div>

            
            
    </div>
  </div>
</template>

<script>
export default {
  name: 'Index',
  data () {
    return {
     
    }
  }
}
</script>


<style>
body{
    font-family: 'Montserrat', sans-serif;
    height: 100%;
    margin: 0;
    line-height: 1.5;
    font-size: 10px;
}
.secondary-color{
    color: #4481eb;
}
.primary-color{
    color: #2c98fb;
}
*{
    box-sizing: border-box;
}
p{
    padding: 0;
    margin: 0;
}
.pt{
    padding: 5px;
}
section{
    min-height: calc(600px - 60px);
    width: 350px;
    margin: 20px;
    box-shadow: 0 2px 6px 0 #ddd;
}

.navigation{
    background: #4481eb;
    height: 50px;
    padding: 5px;
    color: #fff;
    text-align: center;
}
.navigation i, h3{
    display: inline;
}
.navigation i{
    float: left;
    padding-left: 10px;
    padding-top: 5px;
    font-size: 30px;
}
.navigation h3{
    font-weight: 200; 
    font-size: 25px;
}

.intro-body{
    background: #2c98fb;
    height: 100px;
}

.box1{
    width: 90%;
    box-shadow: 0 0 6px 0 #999;
    border-radius: 10px;
    height: 100px;
    background: #fff;
    color: #888;
    margin:-50px auto auto auto;
    padding: 20px 10px 10px 10px;
    display: grid;
    grid-template-columns: repeat(3, 1fr)
}

.box1 button{
    border-radius: 15px;
    height: 30px;
    padding: 2px;
    font-size: 10px;
    border: none;
    color: #fff;
    background: #2c98fb;
}
.box1 button:hover{
    color: #fff;
    background: #4481eb;
}

.info-div .box {
    width: 90%;
    border-radius: 10px;
    height: 120px;
    background: #fff;
    color: #888;
    margin: 20px auto;
    display: grid;
    grid-template-columns: 1fr 2fr;
    box-shadow: 0 2px 6px 0 #999;
}

.info-div .box img{
    border-bottom-left-radius: 10px;
    border-top-left-radius: 10px;
    width: 100%;
    height: 100%;
}

.box-details{
    padding: 10px;
    display: grid;
}
.pdt{
    margin: 15px 0;
}
.pdt h3{
    color: #4481eb;
}
.fr{
    float: right;
    color: #2c98fb;
    font-size: 15px;
}
.fr2{
    float: right;
}
.checked {
    color: orange;
  }


footer{
    border-top: 3px solid #888;
}
.footer{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    width: 70%;
    margin: auto;
    padding-top: 10px;
}
.tc{
    text-align: center;
    color: #888;
}

/* Sign In Page */
.sigin-in{
    min-height: 600px;
    width: 350px;
    margin: 20px;
    box-shadow: 0 2px 6px 0 #ddd;
    display: grid;
    grid-template-rows: 1fr 1fr;
}
.first-div{
    background: #2c98fb;
    height: 100%;
    width: 100%;
    color: #fff;
}
.first-div-cnt{
    position: relative;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}
.first-div i{
    -ms-transform: rotate(20deg); /* IE 9 */
    -webkit-transform: rotate(20deg); /* Safari 3-8 */
     transform: rotate(-45deg);
}
.second-div{
   width: 90%;
   margin: -70px auto auto auto;
   background: #fff;
   padding: 10px 20px;
   border-radius: 10px; 
}
.input-div{
    border-bottom: 1px solid #888;
    display: grid;
    grid-template-columns: 90% 10%;
    margin: 10px 0;
    color: #888;
}

input{
    border: none;
    outline: none;
    padding-left: 10px;
    padding-bottom: 10px;
}

.sign-up-btn{
    width: 100%;
    height: 40px;
    margin: 5px 0;
    padding: 10px;
    border-radius: 20px;
    border: none;
    font-size: 16px;
    font-weight: 400px;
    background: #2c98fb;
    color: #fff;
    letter-spacing: 1px;
    font-family: 'Montserrat', sans-serif;
}

.sign-up-btn:hover{
    background: #4481eb;
}

.sign-up-btn2{
    width: 100%;
    height: 40px;
    margin: 5px 0;
    padding: 10px;
    border-radius: 20px;
    border: none;
    font-weight: 400px;
    background: #2851A3;
    color: #fff;
    letter-spacing: 1px;
    font-family: 'Montserrat', sans-serif;
}

.sign-up-btn2:hover{
    background: rgb(32, 55, 100);
}

.f1{
    font-weight: 100 !important;
    font-size: 10px;
    letter-spacing: 1px;
}

.f2{
    font-weight: 400 !important;
    font-size: 16px;
    letter-spacing: 1px;
} 

.signup-footer{
    text-align: center;
    margin: 20px 0 10px 0;
}
.sf-t{
    color: #2c98fb;
}
</style>
