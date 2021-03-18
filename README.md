# travel_and-tourism-website
*{
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}
header{
    background-color: black;
    height: 100px;
    background-size: cover;
    background-position: center;
}
ul{
    float: right;
    list-style-type: none;
    margin-top: 25px;
    padding-bottom: 10px;
}
ul li{
    display: inline-block;
}
ul li a{
    text-decoration: none;
    color:gray;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.6s ease;
    height: 100px;
    padding-bottom: 10px;
}


ul li a:hover{
    background-color:yellow;
    color: black;
    height: 100px ;
}
ul li.active a{

    background-color:yellow;
    color: black;
}


    
.logo img{
    float: left;
    width: 150px;
    height: auto;
}
}
.main{
    max-width: 1200px;
    margin: auto;
}


.title
{ 
    width: 1350px;
    height: 700px;
    background: url(topdest.jpg);
    margin: 0px ;
    animation: slide 8s infinite ease;
    background-size: cover;
    padding: 0px;
}


@keyframes slide{ 

    

33%{
    background: url(topdest.jpg);
    background-size: cover ; 
}

66%{
 
    background: url(travelll.jpg);
    background-size: cover ; 
}



100%{

    background: url('wander.jpg');
    background-size: cover ; 
}
}
.p1{
    padding-left: 200px;
    padding-top: 120px;
    font-size: 80px;
    font-family: fantasy;
    color: whitesmoke;
    animation: float 15s infinite linear;
    letter-spacing: 20px;
    
}
.midpic{
    background-color: wheat;
    justify-content: space-evenly;
    display: flex;
}

.pic{
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";
    
}


.pic-image{
    
    background-image: url('tours-01.jpg');
    background-size: cover;
    display: flex;
    
}

.picbutton{

    cursor: pointer;
    grid-area: button;
    border: 0px;
    width:300px;
    height: 60px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: lawngreen;
    color: white;
    word-spacing: 60px;
    font-family: sans-serif;
    font-size: large;
    text-align: center;
}

.pic2{
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";

}
.pic3{
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";
}
.pic4{
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";
}

.pic-image1{
    
    background-image: url('paris.jpg');
    background-size: cover;
    position: relative;
    display: flex;
    
}

.pic-image3{
    background-image: url('myanmar.jpg');
    background-size: cover;
}

.pic-image4{
    background-image: url('taaaaaaj.jpg');
    background-size: cover;
}
.picbutton1{
    cursor: pointer;
    grid-area: button;
    border: 0px;
    width:300px;
    height: 60px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: tomato;
    color: white;
    word-spacing: 60px;
    font-family: sans-serif;
    font-size: large;
    text-align: center;
}
.picbutton3{
    cursor: pointer;
    grid-area: button;
    border: 0px;
    width:300px;
    height: 60px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: palevioletred;
    color: white;
    word-spacing: 60px;
    font-family: sans-serif;
    font-size: large;
    text-align: center;

}

.picbutton4{
    cursor: pointer;
    grid-area: button;
    border: 0px;
    width:300px;
    height: 60px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: royalblue;
    color: white;
    word-spacing: 60px;
    font-family: sans-serif;
    font-size: large;
    text-align: center;
}
.pic2{ 
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";


}

.pic1{
    justify-content: center;
    display: grid;
    padding: 20px;
    background-color: wheat;
    grid-template-columns: 300px;
    grid-template-rows: 400px;
    grid-template-areas: "image" "button";
}

 .pic-image2{
     background-image: url('nepal.jpg');
     background-size: cover;
 }
 
 .picbutton2{

    cursor: pointer;
    grid-area: button;
    border: 0px;
    width:300px;
    height: 60px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background-color: teal;
    color: white;
    word-spacing: 60px;
    font-family: sans-serif;
    font-size: large;
    text-align: center;
 }
 .divb{

width: 100%;
    height: 50px;
background-position: center;

    
    
}
 
 .p{
    font-size: x-large ;
    color: tomato;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: 200px;
    margin-left: 10px;
}
.p:hover{
    background-color: yellow;
    color: black;
    font-size: x-large;
    font-style: italic;
    letter-spacing: 10px;
}
    
#form-area{
    padding-top: 80px;
    padding-bottom: 80px;
    background-color: wheat;
    display: flex;
    justify-content: space-around;
}
.map{
    padding-left: 80px;
    width:50%;
    height:500px;
}
    


.form{
    width: 100%;
    padding-left: 50px;
}


#name{
    margin-left: 100px;
    border-radius: 15px;
    width: 300px;
    height: 50px;
    align-items: flex-end;
    justify-content: space-evenly;
    font-size: 18px;
    font-weight: 600px;
    padding-left: 10px;
}


#button2{
    margin-left: 100px;
    font-weight: 600px;
    background-color: yellow;
    width: 300px;
    height: 50px;
    text-transform: uppercase;
    font-size: 20px;
    border: none;
    border-radius: 8px;
    padding-right: 20px;
}
#email{
    margin-left: 100px;
    border-radius: 15px;
    width: 300px;
    height: 50px;
    align-items: center;
    justify-content: space-evenly;
    font-size: 18px;
    font-weight: 600px;
    padding-left: 10px;
}
#subject{
    margin-left: 100px;
    border-radius: 15px;
    width: 300px;
    height: 50px;
    align-items: center;
    justify-content: space-evenly;
    font-size: 18px;
    font-weight: 600px;
    padding-left: 10px;
}

#message{
    margin-left: 100px;
    border-radius: 15px;
    width: 300px;
    height: 100px;
    align-items: center;
    justify-content: space-evenly;
    font-size: 18px;
    font-weight: 600px;
    padding-left: 10px;

}
footer{
    
    padding: 40px 0px;
    width: 280%;
    background-color: black;

    padding-inline-start: 585px;
    margin-bottom: -100px;

    margin-left: -600px;
}
.foot{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: aliceblue;
}


























