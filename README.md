 <body>
    
     <div ><img class="img1" src="C:\Users\Pro.Moscote\Desktop\SUBLIME TEXT\2. PROYECTO\IMG\formulario11.png"></div>
      
      <div class="formulario">
          <form>
            <h3 class="descrip">Deja aqui tu comentario</h3>            
                        
           <p class="tex">Nombre:
            <input type="text" placeholder="escribe tu nombre.."></input></p>

           <p>Correo:
            <input type="email" placeholder="digita el email del contacto"></input></p>
            
             <p>Comentario:
             <textarea class="text"></textarea></p><br>
            
            <button>Clic Aqui</button>

         </form>
     </div>
    
    </body>

******** stilos css   *********

@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap');
body{
	background:#CCFFE5;
}


.formulario{
	
	padding:30px 30px; /* posicion de la informacion */
	width:440px;
	height:550px;
	background:white;
	color: #123;
	border-radius:5px;
	box-shadow:0 0 40px -10px #000; /*marco sombra */
	box-sizing:border-box;
	font-family:sans-serif;
	position: absolute;
	left: 45%;
	top: 7%;
	
}

.img1{
 	 width: 950px;
 	 height: 580px;
 	 border-radius: 22px;
 	 position: relative;
    top:45px ;
    left:100px;
    
   }

 

p{
	margin:10px 15px;
	padding-bottom:15px;
	width:320px;
	color:blue;
	/*border-bottom:2px solid #78788c*/
}

input{
	width:100%;
	height: 0px;
	/*border-radius: 19px;*/
	border: 10px;
	padding:18px;
  	background:#E0E0E0;
	font-family:sans-serif;
   outline: none;

	}

input:focus{
	border-bottom:8px 
}


textarea{
	width:90%;
	height: 100px;
	background:#E0E0E0;
	outline: none;
	
}


h3{
text-align: center;
font-size: 35px;
font-family: 'Oswald', sans-serif;
 }

button{
	width:320px;
	padding:18px 124px;
	/*margin:100px 0 ;*/
	/*float: left;*/
	font-family:'Montserrat',sans-serif;
	background: #33FF33;
	color:#5a5a6e;
	border: 0;


}

button:hover{
	background:#78788c;
	color:#fff
		transition:all .5s
	  

}

