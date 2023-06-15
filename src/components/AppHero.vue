<script >
   import image from '../assets/logo.svg'


export default{
    data(){
        return{
            image :image,
            
            
        }
    },
    mounted(){

    }
}
</script>
<template >
    <header class=" mb-5">
        <div class="upper  d-flex justify-content-around">
            <div class="logo">
                <img class="img" :src="image" style="color: aqua;">
            </div>
            <nav class="barra-nav">
                <ul class="opzioni-nav d-flex ">
                    <li>Scopri</li>
                    <li>Scarica</li>
                    <li>prova</li>
                    <li>Saperne di più</li>
                    <li> Assistenza</li>
                </ul>

            </nav>
            <div>
                <button class="btn btn-primary" href="#">Accedi</button>
            </div>
        </div>
    </header>
    <div class="jumbotron mb-5 text-white" >
        <h2>
           Jumbotron Example
        </h2>

        <h5 >
           This is a simple jumbotron example component that i create to learn more Vue.js with Node.js
        </h5>

        <h5>
           It is not easy but i do that!!
        </h5>
    </div>
    <div>
        <button class="btn btn-primary mx-2" href="#">Do Something</button>
        <button class="btn btn-success" href="#">Do Something Else</button>
    </div>

</template>



   

<style>
div.jumbotron{
    background-image: url(https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-4/gifts.jpg);
    height: 300px;
    object-fit: cover;
    padding: 5rem ;
}


.opzioni-nav{
    color: rgb(110, 110, 235);
    font-size: 13px;
    justify-content: space-around;  
}
.upper{
   align-items: center;
   justify-content: space-around;
   padding-top: 11px;
}
ul{
    list-style-type: none;
}
div.logo{
    width: 10%;
   

}
nav.barra-nav{
    width: 50%;
}
 ul li{
    margin-right: .1rem;
 }
 .img{
    width: 90px;

 }
</style>