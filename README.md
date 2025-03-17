@import url('https://fonts.googleapis.com/css2?family=Anybody:ital,wght@0,100..900;1,100..900&family=Heebo:wght@100..900&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Manrope:wght@200..800&family=Playwrite+NZ+Guides&family=Poppins:wght@300&family=Roboto+Serif:ital,opsz,wght@0,8..144,100..900;1,8..144,100..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;

    h1,h2,h3,h4,h5,h6 {
        color: #fff;
    }
    span {
        color: #7444fd;
    }
    span i {
        color: #fff;
    }

    p {
        color: #9da3b4;
    }
    button {
        color: #fff;
    }

    a {
        text-decoration: none;
    }
}

body {
    background-color: #0f0a2b;
    font-family: "Manrope", sans-serif;
}

img {
    max-width: 100%;
    height: auto;
}


.burger{
    display: none;
}

.burger{
    display: none;
    width: 22px;
    height: 4px;
    
}

.burger span {
    display: none;
    margin-bottom: 3px;
    height: 3px;
    color: #940000;
    width: 100%;
    background-color: rgb(0, 0, 0);
}

.navigation-bar.active {
    display: flex;
}

#top1-btn{
    display: none;
}

/* .light-effect {
    position: absolute;
    width: 700px;
    height: 300px;
    background: linear-gradient(120deg, rgba(255, 255, 255, 1), rgba(33, 83, 255, 0.5), transparent);
    filter: blur(40px);
    mix-blend-mode: overlay;
    animation: moveLight 7s infinite linear alternate;
}

@keyframes moveLight {
    0% {
        transform: translate(-50%, -50%) rotate(0deg);
    }

    100% {
        transform: translate(50%, 50%) rotate(20deg);
    }
} */


/* .light-effec2 {
    position: absolute;
    width: 900px;
    height: 600px;
    left: 0; */
    /* right: 100px; */
    /* background: linear-gradient(120deg, rgba(255, 255, 255, 1), rgba(33, 83, 255, 1), transparent);
    filter: blur(40px);
    mix-blend-mode: overlay;
    animation: moveLight 7s infinite linear alternate;
    margin-left: -40rem;
    top: -30rem;
} */

.box-container {
    /* width: 1360px; */
    margin: 0 auto;
 } 


.top-menu {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 80px;
}


.logo img {
    width: 200px;
    height: 100%;

}

.menu-list {
    display: flex;
    flex-direction: row;
    gap: 2rem;
}

.menu-list li {
    list-style: none;
}

.menu-list a {
    text-decoration: none;
    font-size: 1.2rem;
    color: #FFFFFF;
    font-weight: 600;
}

.menu-list a:hover {
    border-bottom: 2px solid #2153FF;
}

#top-btn {
    padding: 0.7rem 1.5rem;
    font-size: 1rem;
    color: #FFFFFF;
    background-color: #2153FF;
    border: none;
    border-radius: 0.2rem;
}

#top-btn:hover {
    background-color: #0F0A2B;
    border: 1px solid #2153FF;
}


/* ========about ushero-tittle styele======= */
h1{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20%;
    font-size: 4rem;
    text-transform: uppercase;
    box-shadow: 0 10px 5px rgba(0, 0, 0, 0.5);
}

/* ========about us grid======= */
.about-us-grid,
.section5-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
    margin-block: 3rem;
}

/* ========about us content======= */

.aboutUs-content .pic img {
    width: 500px;
    height: 650px;

}

.aboutUs-content .pic {
    position: relative;
    padding-left: 1.5rem;
    z-index: -1;
}
.img-overlay {   
    width: 250px;
    height: 150px;
    background-color: white;
    position: absolute;
    left: 8%;
    margin-top: -9rem;
    padding: 1rem;
    border-radius: 1rem;
    animation: back-and-forth 3s infinite;
}

@keyframes back-and-forth {
    
    50% {
         translate:  8%;
    }
}


/* ========about us content2,3======= */

.aboutUs-content2,
.aboutUs-content3,
.section5-content  {
    display: flex;
    flex-direction: column;
    align-items: self-start;
    gap: 2rem;
    margin-top: 4rem;
}
.aboutUs-content2 #tittle, 
.aboutUs-content3 #tittle,
.aboutUs-section4 #tittle,
.section5-content #tittle,
.our-team #tittle,
.team-banner #tittle,
.Testimonial #tittle,
.why-choseUs #tittle,
.our-values #tittle {
    background-color: #e6ddff;
    border-radius: 2rem;
    padding: .4rem 1rem;
}

.aboutUs-content2 #tittle img,
.aboutUs-content3 #tittle img,
.aboutUs-section4 #tittle img,
.section5-content #tittle img,
.our-team #tittle img,
.team-banner #tittle img,
.Testimonial #tittle img,
.why-choseUs #tittle img {
    width: 15px;
    margin-left: .5rem;
}

.aboutUs-content2 h2,
.aboutUs-content3 h2,
.aboutUs-section4 h2,
.section5-content h2,
.our-team h2,
.team-banner h2,
.Testimonial h2,
.why-choseUs h2,
.our-values h2 {
    font-size: 2.7rem;
    font-weight: 700;
}   


.aboutUs-content2 #check-boxes {
    display: flex;
    flex-direction: column;
    gap: .5rem;
    font-size: 1rem;
}

.aboutUs-content2 #check-boxes i {
    background-color: #1cd07a;
    border-radius: 50%;
    padding: 5px;
    margin-right: .5rem;
    margin-block: .5rem;
}


.btn {
    background-color: transparent;
   padding: 1rem 3rem;
   border-radius: 2rem;
   border: none;
   font-size: 1rem; 
   transition:  2s all ease-in-out;
   overflow: hidden;
   position: relative;
}

.btn:hover{
    background-color: black;
    color: #fff;
 
    
}
.btn::before {
    content: "";
    position: absolute;
    width: 400px;
    height: 400px;
    left: -120px;
    top: -270px;
    border-radius: 45%;
    background-color: #7444fd;
    transition: .9s all ease-in-out;
    z-index: -1;
}


.btn:hover::before{
    top: -450px; 
}


/* =========more on section3========= */

.aboutUs-content .pic-2 img {
    width: 500px;
    border-radius: 1rem;
}

.aboutUs-content .pic-2 {
    margin-top: 10rem;
    position: relative;
}

.img-overlay-1 {   
    width: 200px;
    background-color: white;
    position: absolute;
    right: 14%;
    top: 9px;
    margin-top: 1rem;
    padding: 1rem;
    border-radius: 1rem;
    animation: back-and-forth 3s infinite alternate;
}


.img-overlay-2 {   
    width: 200px;
    background-color: white;
    position: absolute;
    left: -5%;
    bottom: 0;
    margin-top: 1rem;
    padding: 1rem;
    border-radius: 1rem;
    animation: floatUpDown 3s infinite alternate;
}

@keyframes floatUpDown {
    50% {
        transform:  translateY(15%);
    }
}
   
.aboutUs-dis #icons {
    width: 100px;
}


.aboutUs-dis {
    display: flex;
    align-items: center;
    gap: 1rem;

    
}
.aboutUs-info {
    display: flex;
    flex-direction: column;
    gap: .5rem;
}

/* ============section4================= */

.aboutUs-section4,
.our-team,
.team-banner,
.Testimonial,
.why-choseUs,
.our-values {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
    margin-top: 5rem;
}

#section4-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    margin-block: 3rem;
}


.aboutUs-section4 h2,
.our-team h2,
.team-banner h2,
.Testimonial h2,
.why-choseUs h2,
.our-values h2 {
    text-align: center;
    margin-bottom: 2rem;
    font-family: "roboto", sans-serif;
}

.box {
    display: flex;
    /* flex-direction: column; */
    align-items: center;
    text-align: center;
    gap: 1rem;
}
/* 
.boxes span {
    background-color: #e6ddff;
    border-radius: 2rem;
    padding: 0 1rem;
    text-transform: uppercase;
    font-weight: 700;
}

.section-4 .section4-info {
    /* position: relative; */
}



/* .section4-info .section4-bg {
    margin-top: 5rem;
    position: absolute;
    bottom: 0;
    right: 0;
    
} */

.section4-boxes {
    display: flex;
    /* justify-content: space-around; */
}

.box span {
    text-transform: uppercase;
}


.box {
    display: flex;
    flex-direction: column;
    gap: .5rem;
    text-align: center;
    margin-top: -12rem;
}

.box1 {
    margin-left: .5rem;
}
.box2 {
    margin-top: -8rem;
    margin-left: 4.5rem;
}

.box3 {
    margin-left: 3rem;
}  */

/* ============section5================= */

.counter  {
   display: flex;
   gap: 2rem;
}

.counter .counter-box {
    display: flex;
    flex-direction: column;
}

.counter #counter-number {
    font-size: 2rem;
    font-weight: 700;
    color: #fff;
}
.counter #counter-info{
    font-size: 1rem;
    color: #9da3b4;
}

.section5-content1 .pic3 img {
    width: 450px;
    height: 560px;
    margin-left: 5rem;
    position: relative;
}

.section5-content1 .img-overlay-3 {
    margin-top: -36rem;
    margin-left: 2rem;
    position: absolute;
    background: linear-gradient(rgba(58, 25, 109, 0.5), rgba(77, 174, 58, 0.5));
    width: 180px;
    padding: 4rem 2rem 1rem;
    border-radius: 1rem;
    animation: floatUpDown 3s infinite;
}
.overlay-content {
    display: flex;
    flex-direction: column;
    text-align: center;
    position: absolute;
    top: 50%;
    left: 33%;
}

.overlay-tittle {
    display: flex;
    flex-direction: column;
    text-align: center;
    position: absolute;
    top: 6%;
    margin-inline: -5%;
}

#overlay-heading {
    font-size: .7rem;
    color: #fff;
}
#overlay-counter {
    font-size: 1rem;
    color: #fff;
}



/* ==========ourteam section6========= */

.card {
    position: relative;
    padding-block: 5rem;
}

.card--bg,
.card--blur {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.card--blur {
    backdrop-filter: blur(24px);
}

.card--container {
    position: relative;
    display: grid;
    grid-template-columns: 330px;
    justify-content: center;
    gap: 2rem;
}

.card--article {
    position: relative;
    border-radius: 2rem;
    overflow: hidden;
}

.card--img {
    border-radius: 2rem;
    transition: transform .4s;
}

.card--shadow {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.card--data  {
    position: absolute;
    left: 1.5rem;
    bottom: 2rem;
}

.card--name {
    font-weight: bolder;
    font-size: 1.7rem;
    margin-bottom: .25rem;
}

.card--profession {
    font-weight: bolder;
    font-size: 1rem;
    color: #2153FF;
}

.card--clip {
    position: absolute;
    top: 1rem;
    right: 1rem;
    color: #fff;
    background-color: #2153FF;
    box-shadow: 0 0 16px 4px #2153FF;
    width: 2rem;
    height: 2rem;
    border-radius: 50%;
    display: grid;
    place-items: center;
    font-size: 1.3rem;
    cursor: pointer;
    transition: transform .4s;
    z-index: 1;
}

.card--article:hover .card--img {
    transform: scale(1.1);
}

.info {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(104,114,46,0.4),rgba(18,169,186,.5));
    backdrop-filter: blur(12px);
    padding: 3rem 1.5rem 1.5rem;
    clip-path: circle(8px at 88% 10%);
    transition: clip-path .5s ease-in-out;
}

.info--name {
    font-size: 2rem;
    margin-bottom: .5rem
}

.info--data p {
    font-size: 1rem;
    margin-bottom: 1rem;
    color: #fff;
}

.info--btn {
    display: inline-flex;
    background-color: #2153FF;
    box-shadow: #1d0fe4;
    padding: .5rem .75rem;
    border-radius: .5rem;
    color: #fff;
    transition: box-shadow .4s;
}

.info--btn:hover {
    box-shadow: 0 0 20px #2153FF;
}

.info--social {
    position: absolute;
    left: 1.5rem;
    bottom: 1.5rem;
    display: flex;
    gap: .5rem;
}

.info--link {
    background-color: #fff;
    width: 2rem;
    height: 2rem;
    border-radius: .75rem;
    display: grid;
    place-items: center;
    font-size: 1.5rem;
    color: #2153FF;
    transition: transform .4s;
}

.info--link:hover {
    transform: translateY(-.25rem);
    color: #fff;
    background-color: #2153FF;
}

.card--article:hover .card--clip {
    transform: rotate(-45deg);
}

.info:hover,
.card--clip:hover ~ .info {
    clip-path: circle(100%);
}


/* ===============section7 team details============== */
.team-details {
    display: flex;
    gap: 2rem;
    margin-block: 5rem
}

.team-details #img {
   max-width: 350px; 
   border-radius: 2rem;                                               
}

.team-dis {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.signature img {
    background-color: #c9bbbb;
    width: 91px;
    height: 51px;
} 

.personal-info {
    display: flex;
    justify-content: space-between;
}

.personal-tittle {
    font-size: 1.3rem;
    text-align: center;
}

.personal-links {
    display: flex;
    gap: 1.5rem;
}

.team-dis p {
    line-height: 2.5rem;
}

.personal-contact {
    display: flex;
    gap: 1rem;
    margin-top: 2rem;
    cursor: pointer;
}

.personal-contact span {
    color: #fff;
}

.personal-contact i,
.personal-tittle i  {
    margin-right: 1rem;
    color: #2153FF;
}

.personal-tittle span {
    font-size: .8rem;
    font-family: "Playwrite NZ Guides", cursive;
}

/* ===========section8 personal dis======== */
.personal-dis {
    display: flex;
    flex-direction: column;
    gap: 4rem;
    margin-block: 4rem;
}
.personal-dis h2 {
    margin-bottom: 1rem;
}


.personalSkills li {
  list-style: none;
  padding: 1rem;
}

.personalSkills span {
    color: #fff;
    font-size: 1rem;
}

.personalSkills #skill-tittle {
    display: flex;
    justify-content: space-between;
}



.bar {
    display: block;
    background-color: #3c507c;
    height: 1.2rem;
    margin-top: .5rem;
    border: 1px solid rgba(0, 0, 0, 0.3);
    border-radius: 2rem;
    box-shadow: 0 1px 3px rgba(12, 35, 183, 0.8), 0 1px 3px rgba(11, 95, 206, 0.24);
    transition: all cubic-bezier(25, 8, 25, 1);
}

.bar:hover {
    box-shadow: 0 14px 28px rgba(9, 15, 195, 0.9), 0 10px 10px rgba(3, 109, 154, 0.22);
}    
.bar span {
    height: 20px;
    float:left ;
    background: #2153FF;
    border-radius: 1rem;
}

.Html {
    width: 90%;
    animation: Html 3s;
    animation-iteration-count: infinite;
}

.Css {
    width: 70%;
    animation: Css 3s;
    animation-iteration-count: infinite;
}

.javascript {
    width: 40%;
    animation: javascript 3s;
    animation-iteration-count: infinite;
}

.React {
    width: 60%;
    animation: React 3s;
    animation-iteration-count: infinite;
}

@keyframes Html {
    0% {
        width: 0;
    }

    100% {
        width: 90%;
    }
}

@keyframes Css {
    0% {
        width: 0;
    }

    100% {
        width: 70%;
    }
}

@keyframes javascript {
    0% {
        width: 0;
    }

    100% {
        width: 40%;
    }
}


@keyframes React {
    0% {
        width: 0;
    }

    100% {
        width: 60%;
    }
}


/* ==========FAQ============== */
.faq {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    margin-block: 5rem;
}

.faq-dis h3,p {
    margin-bottom: .5rem;
}

.faq-dis i {
    margin-left: .5rem;
}


/* ===============Testimonial============ */
.Testimonials {
    display: flex;
    gap: 3rem;
    animation: slide 20s  infinite;
}

@keyframes slide {
    from {
        transform: translateX(20%);
    }

    to {
        transform: translateX(-25%);
    }
}


.client-1 {
    background: linear-gradient(rgba(65, 47, 227, 0.4), rgba(40, 74, 227, 0.3));
    padding: 2rem;
    border-radius: 2rem;
    width: 320px;
}

.client-1:hover,
.our-mission:hover,
.our-vision:hover,
.education:hover,
.community:hover,
.innovation:hover {
    box-shadow: 0 14px 28px rgba(9, 15, 195, 0.9), 0 10px 10px rgba(3, 109, 154, 0.22);
}


.client-1 .client-info img {
    width: 100px;
    border-radius: 2rem;
}

.client-info {
    display: flex;
    gap: 1rem;
}

.Testimonials {
    margin-block: 4rem;
}

.client-tittle {
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.client-tittle span {
    font-size: .8rem;
    color: #2153FF;
    font-family: "Playwrite NZ Guides", cursive;
}

.client-dis .stars  {
    color: #f27625;
    font-size: .8rem;
    padding-left: .5rem;
}

.client-dis #comma img {
    width: 25px;
}

.client-dis #comma {
    display: flex;
    justify-content: end;

}

/* ===============Why choose Us============ */

.why-chooseUs {
    display: grid;
    grid-template-columns: repeat(2,1fr);
    gap: 3rem;
    margin-block: 3rem;
}

.our-mission,
.our-vision,
.education,
.community,
.innovation {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: .5rem;
    background: linear-gradient(rgba(65, 47, 227, 0.4), rgba(40, 74, 227, 0.3));
    padding: 2rem;
    width: 450px;
    height: 300px;
    border-radius: 2rem;
}

.mission-info,
.vision-info,
.education-info,
.community-info,
.innovation-info {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.mission-info i,
.vision-info i,
.education i,
.community i,
.innovation i {
    color: #2153FF;
    font-size: 1.5rem;
    background-color: #cacdd4;
    padding: .5rem;
    border-radius: 1rem;
}

.mission-info i:hover,
.vision-info i:hover,
.education i:hover,
.community i:hover,
.innovation i:hover {
    background-color: #2153FF;
    color: #fff;
    cursor: pointer;
}


.mission-info h3,
.vision-info h3,
.education h3,
.community h3,
.innovation h3 {
    font-size: 1.3rem;
}
.mission-info span,
.vision-info span {
    font-size: .8rem;
    font-family: "anybody", cursive;
}
.mission-rate,
.vision-rate {
    display: flex;
    justify-content: space-between;
}

.mission-rate h4,
.vision-rate h4 {
    font-size: 1.5rem;
    font-family: "anybody", cursive;
    text-align: center;
}

.mission-rate span,
.vision-rate span {
    font-size: 1rem;
    font-family: "poppins", cursive;
}

/* ===============Our Values============ */
.our-values i#award {
    color: #2153FF;
    margin-right: .5rem;
    font-size: 1rem;
}

.our-value {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 3rem;
}


@media  (min-width: 981px)  {


    .card {
        display: grid;
        place-content: center;
    }
    .card--container {
        grid-template-columns: repeat(3,290px);
    }

    .info--data :nth-child(1){
        margin-top: -2rem;
    }

    .info--btn {
        margin-top: -2rem
    }

    .info--social {
        margin-bottom: -1rem;
    }
    



@media (min-width: 851px) and (max-width: 980px)   {

    .card {
        display: grid;
        place-content: center;
    }
    .card--container {
        grid-template-columns: repeat(2,340px);
    }

    .team-details {
        flex-direction: column;
    }

    .faq {
        grid-template-columns: 1fr;
    }
}



/* ========tablet media query======== */

@media  (max-width: 850px) {

          .burger{
            display: block;
            position: absolute;
            right: 20px;
            top: 23px;
        } 
        .burger span{
            display: block;
            margin-bottom: 3px;
            height: 3px;
            color: #940000;
            width: 100%;
            background-color: rgb(255, 255, 255);
        }
        #top-btn{
            display:none;
        }

        #top1-btn {
            padding: 0.7rem 1.5rem;
            font-size: 1rem;
            color: #FFFFFF;
            background-color: #2153FF;
            border: none;
            border-radius: 0.2rem;
        }
        
        #top1-btn:hover {
            background-color: #0F0A2B;
            border: 1px solid #2153FF;
        }

        .navigation-bar{
            display:none;
            position: fixed;
            left:0;
            right:0;
            top: 70px;
            width: 100%;
            background-color: #130080;
            justify-content: center;
            align-items: flex-start;
            padding-block: 10px;
            text-align: center;
            z-index: 1;
            height: 100vh;
           
        }
        
        .navigation-bar .menu-list a{
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        .navigation-bar .menu-list {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        .navigation-bar .menu-list .top-btn{
            margin-right: 60px;
            padding: 0.5rem 6rem;
            border: none;
            border-radius: 0.5rem;
            text-wrap: nowrap;
            background-color: #ffffff;
            color: #000000;
            font-size: 2rem;
        }
           
        
        .navigation-bar .menu-list .top-btn:hover{
            background-color: rgb(0, 18, 218);
            color: #ffffff;
        }


    /* =========about-page========== */

.aboutus-tittle h1 {
    font-size: 3rem;
}

.aboutUs-content .pic img {
    margin: 0;
}
.about-us-grid,
.section5-grid,
.our-team-grid,
.faq,
.why-chooseUs,
.our-value {
    grid-template-columns: 1fr;
}

/* ===========aboutUs-content2 pic========== */
.img-overlay-1 {   
    width: 200px;
    background-color: white;
    position: absolute;
    right: 20%;
    top: 5px;
    margin-top: 1rem;
    padding: 1rem;
    border-radius: 1rem;
    animation: back-and-forth 3s infinite alternate;
}
/* =============aboutUs-content3 pic2 */

@keyframes back-and-forth {
    
    50% {
        translate:  40%;
    }   
}
/* ===========section4======= */
.aboutUs-section4 h2 {
    font-size: 2.2rem;
}

#section4-bg img {
    display: none;
}


.section4-grid {
    grid-template-columns: 1fr;
    margin-top: -5rem;
}

/* ===========section5 ourteam=========== */

.boxes,
.teams,
.teams img,
.team-info,
.team-smlinks {
    margin:  0;
}

.counter {
    display: flex;
    flex-direction: column;
    gap: 3rem;
    margin: auto;
}

.section5-content1 .pic3 {
    margin-right: 4rem;
}

/* ==============team details============= */

.team-details {
    display: flex;
    flex-direction: column;
}

.team-details #img {
    margin: auto;
}
.personal-links {
    margin: 1rem;
}


.personal-contact {
    flex-direction: column;
    font-size: 1.3rem;
}


.card--container {
    grid-template-columns: 400px;
}

.card--data {
    margin-bottom: 1.5rem;
}
.info .info--data {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.info .info--data p {
    margin-block: 1rem;
}

.info--btn {
    margin-top: .5rem;
}

.info--social {
    margin-bottom: 3rem;
    margin-left: 6.3rem;
}

}







@media  (max-width: 480px) {

    /* =========about-page========== */

    .aboutus-tittle h1 {
        font-size: 2rem;
    }
    .about-us-grid {
        grid-template-columns: 1fr;
    }
/* =============aboutUs-content3 pic2 */
    .img-overlay-1, 
    .img-overlay-2 {   
        width: 150px;   
    }
/* ===========section4=======  */
    .aboutUs-section4 h2 {
        font-size: 1.7rem;
    }


    /* ==========section5 our team =============== */

    .section5-content1 .img-overlay-3  {
        margin-left: 0;
    }
/* ==============our team section======== */
    .card--container {
        grid-template-columns: 350px;
    }
    
    .card--data {
        margin: 0;
    }
    .info .info--data {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    
    .info .info--data p {
        margin-block: 1rem;
    }
    
    
    .info--social {
        margin-bottom: -1rem;
        margin-left: 5rem;
    }
    

    /* ==========team details======== */
    .personal-contact {
        font-size: 1rem;
    }




}
    

# Nova-Serve