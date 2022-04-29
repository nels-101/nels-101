*{margin: 0;padding: 0;}
.header{justify-content: space-between;display: flex;background: black;flex-wrap: wrap;}
.logo{margin: 20px;display: flex;flex-wrap: wrap;}
.logo img{width: 200px;height: 100px;border-radius: 7px;}
.logo .logo-text{display: none;}
.div-contact{margin: 30px;color: gray;font-size: 44px;font-weight: 700;}
a{text-decoration: none;}
nav .fa {display: none;}

#bar{color: black;font-size: 30px;margin:10px;position: sticky;top: 0;display: none;background: white;padding: 2px;}
#about{color: gray;}
#about:hover{color: green;}
nav{justify-content: space-between;align-items: center;padding: 1px;position: sticky;top: 0;background: white;border: 1px solid black;z-index: 2;}
.div-nav{display: flex;padding: 10px 0;}
.nav-links{flex: 1; text-align: center;justify-content: space-between;display: flex;padding-top: 0%;}
.nav-links ul li{ list-style: none;display: inline-block;position: relative;padding:8px 10px;}

.nav-links ul li:hover {background: orangered;}
.nav-links ul li a{color: black;text-align: center;font-weight: 500;}
.nav-links ul li a:hover{color: green;text-align: center;}
.divlog{text-align: center;margin: auto;width: 50px;padding: 5px 20px;border: 1px solid black;border-radius: 3px;background: lightgray;}
.div-covid{width: 50%;margin: auto;border-radius: 45px;background: rgba(0,0,0,0.7);color: white;padding: 0.6rem 2rem;text-align: center;}
.div-covid h1{font-size:27px ;}
.div-covid a h1 {color: white;}
.div-covid a h1:hover{color: rgb(34, 13, 228);}
.div-covid:hover{background-color: rgba(200,0,0,0.7)}
.body-head{min-height: 70vh;width: 98%; background-image: linear-gradient(rgba(85, 86, 90, 0.7),rgba(4,9,30,0.7)),url(../assets/1.jpg);background-position: center;background-size: 100% 100%;margin: auto;margin-bottom: 5%;}
@media all and (max-width: 790px) {.menu ul{flex-direction: column;}
#bar{display: initial;}
.row{flex-direction: column;}
.row1{flex-direction: column;}
.div-home{margin-top:0%;}
.div-col{margin-top: 5%;}
.logo img{margin-left: 100px;}
.logo .logo-text{font-size: 10px;}
.div-contact{font-size: 10px;margin-top: -80%;letter-spacing: 3px;}
.nav-links{width: 100%;height: 92vh;background: red;z-index: 2;position: absolute;top: 0;right: -200;text-align: left;transition: 1s;flex-direction: column;display:inline-block;}
.nav-links ul{padding: 3px;text-decoration: none;}
.nav-links ul li{padding: 8px;display: block;} 
.nav-links ul li a{color: black;font-size: 15px;letter-spacing: 3px;margin:5%;padding: 10px;} 
nav .fa {display: block;margin:10px;cursor: pointer;color: bisque;font-size: 22px;}
#copyright {font-size: 11px;}
.social1{display: none;}
.profile p{font-size: 13px;}
.profile h1{font-size: 15px;}
.patners{flex-direction: column;}
.div-container{flex-direction: column;}
}
@media(max-width:300px){.div-heading{font-size: 10px;width: 300px;position: absolute;padding: 1px;text-align: left;}
.div-serv{font-size: 5px;width: 100px;padding: 1px;text-align: left;}
.div-serv1{font-size: 5px;width: 200px;padding: 1px;text-align: left;}
ul ul li{width: 300px;height: 300px;}}
/*end*/
.row{display: flex;width: 80%;margin: auto;padding-top: 5%;justify-content: space-between;}
.div-col{box-sizing: border-box;background: #f1ebeb;padding: 5px;flex-basis: 32%;margin-bottom: 5%;transition: 0.5s;}
.div-col img{width: 100%;height: 180px;}
.div-text h1{font-size: 23px;margin-top: 5%;margin-bottom: 5%;text-align: center;font-weight: 600;}
.div-text p{font-size: 14px;line-height: 22px;padding: 10px;}
.div-text{ background: transparent;height: 100%;}
    .div-col:hover{background: rgba(255,255,255,0.1);box-shadow: 1px 1px 5px 1px black;}
    #div1 {width: 100%;height: 300px;}
.div1-col {width: 100%;height: 53%;}
#strategy{width: 100%;height: 200px;}
.col-text h1{margin-top: 5%;font-size: 20px;text-align: center;}
.col-text p{text-align: left;padding-top:5%; padding-right: 5%;}
#shades{text-align: center;color: gray;}
.div2-col{box-sizing: border-box;background: #f1ebeb;padding: 5px;flex-basis: 32%;margin-bottom: 5%;width: 100%;}
.div2-col img{width:100% ;}
.div2-col h1{font-size: 23px;margin-top: 5%;margin-bottom: 5%;text-align: center;font-weight: 600;}
.div2-col p{font-size: 14px;line-height: 22px;padding: 10px;}
footer{width: 100%;height: 30%;background: rgb(6, 63, 80);}
.footer-col{width: 100%;}
.footer-col h2{color: white;padding-bottom: 10%;text-align: center;font-size: 30px;}
.footer-col p{line-height: 26px;color: ghostwhite;color: lightgray;}
.footer-col img{width: 80px;height: 100px;border-radius: 50%;padding: 10px 35%;}
.social{margin-top: 10%;}
.social ul{display: flex;list-style: none;}
.social ul li{width: 30px;height: 30px;margin: 1%;}
.social ul li img{width: 80%;height: 80%;padding: 10%;}
.social ul li:hover{background: lightblue;}
.social1{margin: 0px 40px;}
.social1 ul{display: flex;list-style: none;}
.social1 ul li{width: 30px;height: 30px;margin: 1%;}
.social1 ul li img{width: 80%;height: 80%;}
.social1 ul li:hover{background: lightblue;}
#copyright {font-size: 21px;padding: 2% 5%;color: gray;}
