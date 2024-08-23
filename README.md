
*{
    padding: 0;
    margin: 0;
    text-decoration: none;
    font-family:'Times New Roman', Times, serif;
    /* color: #6e5858; */
    text-decoration: none;
}
body{
    /* width: 100vw; */
    height: 100vh;
    text-align: center;
    background-image: linear-gradient(120deg, #fdfbfb 0%, #ebedee 100%);
    padding: 0.1rem;
}
/* .header{
    border: solid red 1px;
} */
.esme-header-hai{
          max-width: 1000px;

    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    /* border: solid rgb(150, 49, 49) 1px; */
    margin: 0 auto;
    background-image: linear-gradient(135deg, #fdfcfb 0%, #716961 100%);
 /* border: black solid 2px; */
 animation: scaleAnimation 2s infinite;
}
@keyframes scaleAnimation {
    0% {
        transform: scale(1);
    }
    50% {
        transform: scale(1.1);
    }
    100% {
        transform: scale(1);
    }
}
.logokacontent{
    display: flex;
    gap: 0.5rem;
    font-size: 1.5rem;
    font-weight: 600;
    text-shadow: 2px 2px 20px rgb(70, 70, 65);
    max-width: 1280px;
}  



.logikiimage{
    width: 20px;
   /* height: 30px; */
}

.navigationbar{
    display: none;
    font-size: larger;
    gap: 1rem;
}
@media screen and (min-width:700px) {
    .navigationbar{
        display: flex;
    }
}
.navigationbar a:hover{
    color: rgb(25, 25, 218);
}
.contectbutton{
    display: none;
    font-size: large;
    font-weight: 600;
    color: rgb(211, 199, 199);
    /* border: solid black 2px; */
    border-radius: 20px;
    background-color: rgb(99, 99, 163);
    padding: 0.5rem;
    box-shadow: 1px 1px 20px black;
   
}
@media screen and (min-width:700px) {
    .contectbutton{
        display: flex; 
    }
    
}
.contectbutton:hover{
    background-color: rgb(37, 45, 37);
}
.menubutton{
    display: none;
    border: none;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgb(39, 38, 38); 
    margin-right: -2.55px;
    background-color: greenyellow;
}
.menubutton:hover{
    background-color: #1d0303;
}
@media screen and (max-width:700px) {
    .menubutton{
      display: block;
    }
 }
.buttonicon{
    width: 1.5rem;
    height: 1.5rem;
}
.mainsection{
    max-width: 1000px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 0 auto;
     gap: 90px;
}
.leftsection{
    text-align: center;
   animation: slideFromLeft 1s ease forwards;
   opacity: 0;
}
@keyframes slideFromLeft{
    0% {
        opacity: 0;
        transform: translateX(-100%);
    }
    100% {
        opacity: 1;
        transform: translateX(0);
    }
}
.sectionlabel{
    color: rgb(63, 63, 175);
    font-size:1.1rem;
    font-weight: 600;
}
.sectiontitle{
  font-size: 3.5rem;
}
.sectiondescription{
    font-weight: 400;
    color: rgb(100, 77, 77);
}
.buttonbox{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0.521rem;
    gap: 2rem;
}
.startnow{
    background-color: #382b6f;
    color: white;
    border-radius: 1rem;
    transform: all  0.1s;
    padding: 0.5rem 0.5rem;
}
.taketour{
    background-color: #4c4a57;
    color: white;
    border-radius: 1rem;
    transform: all  0.1s;
    padding: 0.5rem 0.5rem;
    
}
.startnow:hover{
    background-color: #16e543;
}
.taketour:hover{
    background-color: chartreuse;
}
.rightsection{
display: flex;
justify-content: center;
align-items: center;
/* margin-left: 2rem; */
}
.imagecontainer{
    border: none;
    border-radius: 1.2rem;
    margin-top: 6rem;
    overflow: hidden;
    box-shadow: 1px 1px 5px rgb(33, 31, 31);
}
.imagehaiye{
    width: 100%;
    height: 100%;
}
@media screen and (min-width:700px) {
    .mainsection{
     flex-direction: row;
    }
    .leftsection{
        margin-top:6rem;
        width: 50%;
        text-align: left;
        /* text-align: baseline left; */
    }
    .sectionlabel{
    /* text-align: left; */
    /* justify-content: start; */
     /* padding-left: 0; */
     font-size: 1rem;

    }
    .sectiontitle{
        /* text-align: left; */
        font-size: 3.8rem;
    }
    .sectiondescription{
        /* text-align: left; */
        font-size: 1.1rem;
        color: var(--gray);
        width: 78%;
    }
    .buttonbox{
      justify-content: start;
      padding-left: 0;
    }
    .imagecontainer{
        /* margin-top: 3rem;
        width: 69vh;
        height: 80vh; */
        height: 67vh;

    }

}
.littleherosection{
    margin: 3rem;
    display: flex;
    flex-direction: column;
  justify-content: center;
  align-items: center;
  animation: slideFromLeft 1s ease forwards;
  

  animation: scaleAnimaton 5s infinite;
}
@keyframes scaleAnimaton {
    0% {
        transform: scale(0.8);
    }
    50% {
        transform: scale(1);
    }
    100% {
        transform: scale(0.8);
    }
}

.herocontainer{
   display: grid;
    grid-template-columns: repeat(2,1fr);
    background-color: gainsboro;
    gap: 2rem;
    padding: 1rem;
    border: none;
  border-radius: 12px;
  margin-bottom: 1rem;
  box-shadow: #382b6f 2px 2px 20px;
}
.compnylogo{
    height: 2rem;
    margin-top: rem  
    /* display: flex; */
    
    
}
.textforlogo{
    padding: 0.2rem 0.1rem;
    font-size: 1.5rem;
    font-weight: 500;
    font-weight: bold;
}
.maintext{
    margin: 2rem;
    font-size: 2rem;
    font-weight: 600;
    text-shadow: #16e543 2px 2px 10px;
}
.logos{
    display: flex;
    justify-content: center;
    align-items: center;
    /* gap: 1rem; */
}
@media screen and (min-width:630px) {
             .herocontainer{
                display: grid;
                grid-template-columns: repeat(4,1fr);
             }
}
@media screen and (max-width:330px) {
    .herocontainer{
       display: grid;
       grid-template-columns: repeat(1,1fr);
    }
}
 .parentcontainer{
    width: 100vw;
    background-color: #d9e1e4;
    display: flex;
    justify-content: center;
    align-items: center;
}
  .featurecontainer{
    max-width: 1000px; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
       padding: 1rem 3rem;
    margin: 1rem auto;

}

.maindiv{
    display: flex;
    flex-direction: column;
    width: 71%;
    gap: 1rem;
    margin: 2rem;
    /* background-color: #16e543; */
}

.mainheading{
    font-size: 2.6rem;
    font-weight: 600;
}
.secondmaindiv{
    /* width: 71%; */
/* background-color: rgb(144, 132, 192); */
display: grid; 
grid-template-columns: repeat(2,1fr);
margin-top: 1rem;

box-shadow: 1px 1px 20px black;
}
.featureimage{
    width: 2rem;
    height: 2rem;
}
.icon{
    width: 2.8rem;
    height: 2.8rem;
    background-color: white;
    border-radius: 58px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    /* width: 300px;
    height: 160px; */
   
    margin: 2rem 2rem;
    gap: 1rem;
    border-radius: 10px;

} 
.box:hover{
   transform: scale(1.1);
   transition: all 1s linear 0s;
}
.downbox{
    display: flex;
    flex-direction: column;
    gap:1rem;
    padding-bottom: 1rem;
}
.featureofbox{
    color: white;
    font-size: 1rem;
}
.featurediscription{
    color: white;
    font-size: 1rem;
}
.box:nth-child(1){
    background-color: #4a90e2;
    box-shadow: 1px 1px 20px rgb(3, 7, 228);

    display: flex;
    padding-top: 1rem;
}
.box:nth-child(2){
    background-color: #e30b41;
    box-shadow: 1px 1px 20px rgb(158, 56, 56);

    display: flex;
    padding-top: 1rem;
}
.box:nth-child(3){
    background-color: #eb990c;
    box-shadow: 1px 1px 20px rgb(228, 160, 3);

    display: flex;
    padding-top: 1rem;
}
.box:nth-child(4){
    background-color: #09eecc;
    box-shadow: 1px 1px 20px rgb(3, 228, 217);

}
.box:nth-child(5){
    background-color: #09f33b;
    box-shadow: 1px 1px 20px rgb(3, 228, 14);

}
.box:nth-child(6){
    background-color: #cf07f2;
    box-shadow: 1px 1px 20px rgb(169, 52, 151);

    display: flex;
    padding-top: 1rem; 

}
@media screen and (max-width:600px) {
    .secondmaindiv{
        display: grid;
        grid-template-columns: repeat(1,1fr);
        margin: 0 -1rem;
    }
    
}
.testimonialcontainer{
   max-width: 1000px;
    /* height: 100%; */
    /* background-color: #b17777; */
padding: 2rem;
  margin: 0 auto;
}
.testimonial2{
 display: flex;
 flex-direction: column;
 align-items: center ;
 gap: 2rem;
}
.tetimonialtitle{
    font-size: 2.5rem;
    text-shadow: #09f33b 1px 1px 5px;
    transition: transform 1s ease,box-shadow 0s ease;
}
.tetimonialtitle:hover{
    transform: scale(1.1);
    transition: transform 1s ease delay 1s,box-shadow 1s ease;
}

.charactercontainer{
    display: grid;
    grid-template-columns: repeat(3,1fr);
    grid-gap: 2rem;
}
.indivisualcharatercontainer{
    
    display: flex;
    flex-direction: column;
    border:  1px 
    
    solid black;
    box-shadow: 0 2px 4px black;
    padding: 1rem;
    gap: 0.5rem;
    border-radius: 20px;
    transition: transform 1s ease,box-shadow 0s ease;

}
.indivisualcharatercontainer:hover{
    transform: scale(1.1);
    box-shadow: #09f33b 1px 1px 10px;
    border: #0961db solid 2px;

}
.qwe{
    width: 5rem;
    height: 5rem;
}
.parainsideindivisualcontainer{
    font-size: 0.8rem;
}
.testiimage{
    color: blue;
}
.testiinfo{
    font-weight: bold;
}
@media screen and (max-width:600px) {
    .charactercontainer{
        grid-template-columns: repeat(1,1fr);
    }
}
.newsletter{
    max-width: 1000px;
    height: 50vh;
    background-color: #6c635b;
margin: 0  auto;
border-radius: 15px;

}
.chotanewscontainer{
    /* max-width: 1000px; */
    display: flex;
    flex-direction: row;
    /* align-items: center; */
    background-color: #d4d4df;
    border-radius: 15px;
    height: 100%;
    overflow: hidden;
    /* padding-left: 2rem; */

}
.leftportioncontainer{
    height: 100%;
    width: 50%;
    display: none;
    position: relative;
    /* padding-left: 2rem; */
}
.leftportioncontainer img{
    position: absolute;
    inset: 0;
height: 100%;
width: 100%;
object-fit: cover;
object-position: center;
/* border-radius: 15px; */
/* border-top-left-radius: 15px; */
/* margin-bottom: -0.3rem; */
}
.rightportioncontainer{
    display: flex;
    flex-direction: column;
    gap: 1rem;
    padding: 0.5rem;
    justify-content: center;
    text-align: flex-start;
   width: 98%;
   
  
}
@media screen and (min-width:600px) {
    .leftportioncontainer{
        display: block;
        /* padding-left: 2rem; */
        width: 50%;
    }
        .news-right{
            width: 50%;
            padding: 2rem;
        }
        .newsletter-container{
            padding: 2rem;
        }
    }
    


.newstittle{
    font-size:2rem;
    color: rgb(41, 41, 159);
}
.newsparadiscription{
    font-size: 1.5rem;
}
.newshedingcontainer{
    display: flex;
    flex-direction: column;
    gap: 0.1rem;
}
.email{
    height: 1rem;
    width: 10rem;
    outline: none;
    /* outline: none; */
    font-size: 1rem;
    border: none;
    /* box-shadow: none; */
    border-radius: 3px;
    padding: 0.5rem 1rem;
    background-color: #fdfcfb;
}
.email::placeholder {
    font-size: 1rem;
    font-weight: bold;
  }
.email:hover{
    border: solid rgb(55, 216, 15) 2px;
    box-shadow: #521a4e 1px 2px 10px;
}
.email:focus{
    border: solid rgb(216, 15, 119) 2px;
    box-shadow: #a2930b 1px 2px 10px;
}
.fr{
    font-size: 1rem;
}
.newssendbuttoon{
    border-color: #423cbd;
    width: 4rem;
    height: 2rem;
    border-radius: 10px; 
    /* border: solid blue 2px; */
}
.newssendbuttoon:hover{
    border: solid blue 2px;
    box-shadow: #0961db 1px 2px 10px;
}
.endnewssection{
    font-size: 0.9rem;
}
.news-link{
    text-decoration: underline;
}
.newssendbuttoon{
    background-color: blue;
    color: white;
}
@media screen and (min-width:640px) {
    .news-title{
        font-size: 2.5rem;
    }
}
.projectfootersection{
    max-width: 1000px;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    padding: 3rem 0rem;
    /* background-color: #e6d2e4; */

}
.chotafootersection{
    max-width: 1000px;
        text-align: left;
   display: flex;
    justify-content: space-between;
padding-bottom: 1rem;
}
.leftchotasection{
    width: 39%;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    padding-left: 2rem;
    margin-top: 1rem
    
}
.firselogo{
    height: 1rem;
    width: 1rem;
}
.iconheagingsection{
display: flex;
justify-content: flex-start;
}
.lokelia {
    font-size: 1rem;
    display: flex;
    justify-content: center;
    align-items: center; 
    gap: 0.8rem;
    font-weight: bold;
  }
  .filler-text{
    font-size: 0.8rem;
    color: #4b4846;
  }
  .allleftboxicons{
    display: flex;
    justify-content: flex-start;
    gap: 1rem;
  }
 .rightfootersection{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 4rem;
    padding-right: 4rem;
 }
 .foote-link{
    font-size: 0.8rem;
    /* color: black; */
 }
.unoderedproductkiclass{
    display: flex;
    flex-direction: column;
    gap: 1rem;
    list-style-type: none;
    color: blue;
}

.productfooter{
    display: flex;
    flex-direction: column;
   padding-bottom: 2rem;
}
.footergridheading{
    font-weight: bold;
    color: black;
    margin-bottom: 0.5rem;
    text-shadow: 1px 1px 23px black
    
}
.footer-copyright{
        /* display: flex;
        flex-direction: column; */
    padding-top: 3rem; 
    border-top: 0.0001rem solid #7b7e83;
    padding-bottom: 0.1rem;
  
}
.iconheagingsection:hover{
    transform: scaleY(1.2);
    text-shadow: 2px 2px 10px blue;
    transition: all 1s linear ease 1s;
}
@media screen and (max-width:700px) {
    .chotafootersection{
        flex-direction: column ;
      align-items: center;
    }
    .leftchotasection{
        /* padding-left: 9rem; */
        margin-bottom: 2rem;
    }
    .rightfootersection{
        padding-left: 3rem;
        gap: 0.5rem;;
    }
}
@media screen and (max-width:500px) {
    .rightfootersection{
        display: grid;
        grid-template-columns: repeat(2,1fr);
        padding-left: 7rem;
    
    }
    
}
