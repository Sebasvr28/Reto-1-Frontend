# Reto-1-Frontend
<!DOCTYPE html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Reto 1 de Frontend</title>
</head>
<style type="text/css">

#global{
	width:80%;
	margin:0 auto;	
	background-color: white;
	height:auto;
}

#header{
	width:100%;
	margin:0 auto;
	background-color:#FF0;
	height:80px;	
}

#cuerpo{
	width:100%;
	margin:0 auto;
	margin-top:20px;
	background-color:white;
	height:1080px;	
}

#nav{
	width:15%;
	margin:20px;
	background-color:#F63;
	height:1050px;	
	position:relative;
	float:left;
}
#main{
	width:77%;
	margin:20px;
	background-color:#0F6;
	height:1050px;	
	position:relative;
	float:left;
}

#footer{
	width:100%;
	margin:0 auto;
	margin-top:20px;
	background-color:#EFBBF0;	
}

.titulos{
	font-weight:bolder;
	font:Verdana;
	font-size:16px;	
}

.subcuerpo{
	width:96%;
	background-color:#BBF0EE;
	height:31%;
	margin:0 auto;
	margin-top:20px;
	position:relative;	
}

.header_sub{
	width:95%;
	background-color:#EFC9F4;
	height:23%;
	margin:0 auto;
	float:left;
	position:relative;
	padding-left: 5%;	
	
}

.contenido_sub{
	width:85%;
	background-color:#BBF0EE;
	height:8%;
	margin:0 auto;
	float:right;
	position:relative;	

}

.footer_sub{
	width:100%;
	background-color:#F90;
	height:10%;
	float:left;
	position:relative;	
	
	
}

.articule_sub{
	width:80%;
	background-color:#6C6;
	height:20%;
	float:right;
	position:relative;
	padding-left: 5%;	
	
}
.article{
	width:85%;
	background-color:#6C6;
	height:10%;
	float:right;
	position:relative;	
	
}

.input_sub{
	width:100%;
	background-color:#FF0;
	height:10%;
	float:left;
	position:relative;	
	
}

.div_margin{
	width:96%;
	background-color:#BBF0EE;
	height:99%;
	margin:0 auto;
	z-index:-1;	
}
.titulo_sub{
	width:90%;
	background-color:#FF9900;
	height:30%;
	margin:0 auto;
	float:left;
	position:relative;	
}
.time1{
	width:90%;
	background-color:#B5F8F1;
	height:30%;
	margin:0 auto;
	float:left;
	position:relative;	
}
.time2{
	width:90%;
	background-color:#F6B5F8;
	height:30%;
	margin:0 auto;
	float:left;
	position:relative;	
}
.contenido_comentario{
	width:90%;
	background-color:#66CC66;
	height:30%;
	margin:0 auto;
	float:left;
	position:relative;	
}

/*general*/
div{
	border-radius:5px;
	text-align:center;	
}

.etiquetas_sub{
	margin-top:8px;
}
</style>

<body>

<div id="global">
    
<div id="header"><br><br>
<span class="titulos"><-HEADER-></span>
</div>
    
<div id="cuerpo">
    
<div id="nav">
<span class="titulos"><b><-NAV-></b></span>
</div>
        
<div id="main">
<span class="titulos"><b><-MAIN-></b></span>
<br />
			
<div id="sub_cuerpo1" class="subcuerpo etiquetas_sub">
            	
<div class="div_margin">
            
<div id="header_sub1" class="header_sub etiquetas_sub">
<div id="titulo_sub" class="titulo_sub etiquetas_sub">Titulo
</div>  
<div id="time1" class="time1 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Solo Fecha</time>
</div>              
</div>
                    
<div id="contenido_sub1" class="contenido_sub etiquetas_sub">                
</div>
                    
<div id="footer_sub1" class="footer_sub etiquetas_sub">(Etiquetas)                
</div>
                    
<div id="articule_sub1" class="articule_sub etiquetas_sub">
<div id="time1" class="time2 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Fecha + Hora</time>
</div> 
<div id="titulo_sub" class="contenido_comentario etiquetas_sub">Contenido del comnetario
</div>  
                    	 
</div>

<div id="articule_sub2" class="article etiquetas_sub">Otro Comentario

</div>
                    
<div id="input_sub1" class="input_sub etiquetas_sub"><input type="button" value="Comentar">                
</div>
                
</div>
                
</div>
            
<div id="sub_cuerpo2" class="subcuerpo">

<div class="div_margin">
            
<div id="header_sub1" class="header_sub etiquetas_sub">
<div id="titulo_sub" class="titulo_sub etiquetas_sub">Titulo
</div>  
<div id="time1" class="time1 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Solo Fecha</time>
</div>              
</div>
                    
<div id="contenido_sub1" class="contenido_sub etiquetas_sub">                
</div>
                    
<div id="footer_sub1" class="footer_sub etiquetas_sub">(Etiquetas)                
</div>
                    
<div id="articule_sub1" class="articule_sub etiquetas_sub">
<div id="time1" class="time2 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Fecha + Hora</time>
</div> 
<div id="titulo_sub" class="contenido_comentario etiquetas_sub">Contenido del comnetario
</div>  
                    	 

</div>

<div id="articule_sub2" class="article etiquetas_sub">Otro Comentario

</div>
                    
<div id="input_sub1" class="input_sub etiquetas_sub"><input type="button" value="Comentar">                
</div>
                
</div>
</div>
            
<div id="sub_cuerpo3" class="subcuerpo">

<div class="div_margin">
            
<div class="div_margin">
            
<div id="header_sub1" class="header_sub etiquetas_sub">
<div id="titulo_sub" class="titulo_sub etiquetas_sub">Titulo
</div>  
<div id="time1" class="time1 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Solo Fecha</time>
</div>              
</div>
                    
<div id="contenido_sub1" class="contenido_sub etiquetas_sub">                
</div>
                    
<div id="footer_sub1" class="footer_sub etiquetas_sub">(Etiquetas)                
</div>

<div id="articule_sub1" class="articule_sub etiquetas_sub">
<div id="time1" class="time2 etiquetas_sub"><datatime="2016-22-15T12:00-5:00">Fecha + Hora</time>
</div> 
<div id="titulo_sub" class="contenido_comentario etiquetas_sub">Contenido del comnetario
</div>  
                    	 

</div>

<div id="articule_sub2" class="article etiquetas_sub">Otro Comentario

</div>

<div id="input_sub1" class="input_sub etiquetas_sub"><input type="button" value="Comentar">                
</div>
                
</div>
                
</div>
                       
</div>
        
</div>
    
</div>

<div id="footer"><br><br>
    	<span class="titulos"><b><-FOOTER-></b></span>
    	</div>

</body>
</html>
