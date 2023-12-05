## ESTILOS DE TEXTO

  

1. TAMAÑOS DE FUENTE
 
   
    1.1 pixel es la unidad minima (tamaño absoluto)

    1.2 EM (tamaño del contexto) em=16px por defecto

  

        <body>

            <header>

                <h1>ESTILOS DE TEXTO</h1>

            </header>

        </body>

  

        En este caso h1 es el hijo de body, body nos da el contexto, entonces si body es font size 10px, em es ahora 10px.

  

        Si colocaramos header otra cantidad de pixeles, este prima sobre el body por especificidad, por lo que al ir variando se tiene que tomar siempre en cuenta el padre y la herencia.

  
  

    1.3 REM (Tamaño del <html></html>), en vez de dar un contexto, respecta el estilo del html, a diferencia del EM que hereda del padre inmediato superior.

  
  

2. PROPIEDADES DE FUENTE

  

    2.1 line-height(espaciado entre lineas de texto - interlineado), se coloca sin unidades para tomar el valor del font-size

    2.2 text-transform(modifica las palabras): uppercase, capitalize, lowercase.

    2.3 text-align(centrado de palabras):left,center,rigth - se aplican solo a labels de bloque

    2.4 font-weight (peso de la palabra): default es 400, se usa de 300 a 900 usualmente, siendo 700 bold

    2.5 font-style (curvado de palabras):italic

    2.6 text-decoration (subrayados): underline; no se hereda, para quitarlo a una lista de navegación quitaselo a <a>

    2.7 font-family :https://fonts.google.com/

  

    Para agregar los fonts hay maneras,

  

    1. copiar los links al meta del html

    2. importar al archivo css

    3. descargar la fuente y cargarla

