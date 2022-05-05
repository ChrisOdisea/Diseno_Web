## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets

          
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)

         
          b) <link rel="stylesheet" type="text/css" href="style.css">
       
          
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
        
          
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
          c) <style>
          
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

         
          b) styles
     
          
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

          
          c) body:color=black;
    
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
        
          
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

         
          b) background-color
      
          
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
  
         
          b) h1 {background-color:#FFFFFF;}
      
  
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
         
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25
  
         
          c) font-size
        
  
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
  
         
          c) p {font-weight:bold;}
  
  
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
  
         
          d) text-style:capitalize
  
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
  
         
          b) font-family         
  
15. ¿Cómo pones el texto en negrita? (valor 0.25)
  
         
          b) font:bold;
      
  
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
          a) border-width:10px 1px 5px 20px;
          (valor 0.25)
          
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

         
          b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            a) No
           
            
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
 
           
            b) #demo
      
            
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

          
            b) .test
           
            
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)


            b) div p
         
            
22.¿Cómo se agrupan los selectores? (valor 0.25)

           
            c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

          
           d) static
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
 
            a) list-type: square;
            
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![maquetaCR](https://user-images.githubusercontent.com/101351242/167007562-8c0a3831-fc0c-4a08-a81a-752935b4662c.png)


● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


          INGRESA AQUI EL CÓDIGO HTML
          
                                                            <!docktype html>
                    <html>

                              <body>

                                        <head>

                                                  <link rel="stylesheet" href="estilofinal.css">
                                                  <link rel="preconnect" href="https://fonts.googleapis.com">
                                                  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
                                                  <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap" rel="stylesheet">
                                        </head>



                                        <header>

                                                  <div>

                                                    <a href="@"><img src="logo.png" width="300px"></a>

                                                  </div>
                    <hr>
                                                  <nav>

                                                            <ul>
                                                                <a href="@"><li>Residentes</li></a>
                                                              <a href="@"><li>Negocios</li></a>
                                                                <a href="@"><li>Visitantes</li></a>
                                                              <a href="@"><li>Gobierno</li></a>
                                                            </ul>

                                                  </nav>

                                        </header>

                                        <main>
                                                  <article>

                                                            <div>

                                                                      <div class="si">  	<h1> 	<span> > </span> APRENDE A PROGRAMAR    </h1>	</div>
                                                                      <div class="no">   	<h1> 	EN LAS <span> ESCUELAS </span>		</h1>	</div>
                                                                      <div class="aja"> 	<h1> 	<span> DECODIGO </span>                 </h1>	</div>
                                                                      <div class="ok">   	<h1>     DE LA CDMX 			        </h1>	</div>

                                                            </div>

                                                  </article>

                                        </main>


                                        <footer>

                                                  <h2> ¿Quién se puede inscribir? </h2><br>

                                                   Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles a la semana. 
                                                            <p>*Menores de edad deberan entrar a las inslaciones acompañados de un adulto.</p>

                                        </footer>



                              </body>
                    </html>

          
          
          INGRESA AQUI EL CSS
          
                               /*cuerpo*/

                    *{

                              margin:0;
                              padding:0;
                    }
                     body{
                              font-family: 'Ubuntu', sans-serif;
                    }


                                                                            /*header*/


                     img{
                              padding-left:2em;
                              padding-top:1em;
                    }

                     ul{
                              display: flex;
                              list-style-type:none;
                              text-decoration:none;

                    }
                     li{
                              padding-left: 3em;
                    }
                     nav{
                              align-items: flex-end;
                              justify-content: end;
                              display: flex;
                              padding-right: 3em;
                              padding:1.5em;
                    }
                     a{
                         text-decoration:none ;
                         color:green;
                    }


                                                                                /*main*/

                     main{
                              padding:5%;
                              background: url("hero.jpg");
                              background-size: center;
                              background-size: cover;
                              background-repeat:no-repeat;
                    }
                    .si{

                    }
                    .no{
                              padding-left:4.7em;
                    }
                     .aja{
                              padding-left:9.1em;
                    }	


                     .ok{
                              padding-left:9.1em;
                    }

                     div{

                              font-size: 1.6em;
                              color:white;
                              fond-spacing: 10px;
                              font-weight: bold;
                    }
                    span{
                              font-weight: bold;
                              font-size: 1.3em;

                    }
                                                                                /*footer*/

                     footer{
                              padding:1.5em;
                              text-align:center;
                              font-size: 1em;
                              font-weight: bold;


                    }

                     h2{	
                              color:#926C15

                    }
                    footer p{
                              color:gray;
                    {



 Ingresa el link a tu página del proyecto final
 
           https://chrisodisea.github.io/Ejercicio_final/
