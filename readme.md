## Graficamos tu corazon ##
Para usar manim primero deben instalarlo, ya sea con:
*     pip install manim
     o
*     uv tool install manim

En este caso se uso MathTex para imprimir el codigo matematico, por lo cual es necesario instalar el paquete LaTeX
desde su URL https://miktex.org/download puedes verificar que quedo correctamente instalado con: "pdflatex --version"
Tambien puedes validar que no falte ninguna dependencia adicional con pip install manim[all]

Para ejecutarlo usar: manim -pqm .\Heart_In_Python.py Corazon
-pqm significa que sera en calidad media el video generado