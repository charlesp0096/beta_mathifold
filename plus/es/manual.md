---
layout: default
ident: manual
lang: es
title: Manual
---

<div style="position: relative;" align="center">
<p style="font-size: 40px;">Manual</p>
</div>

<div class="plus">

	He aquí un pequeño manual para usuarios y colaboradores <br><br>

	<b>Navegación</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Estructura de la página
		</div>

		<div class="dissap">
		La página tiene una estructura arbórea de cuatro niveles: 

		<ul style="list-style-type: none;">
		<li>-Temas (ej. Geometría)</li>
		<li>-Asignaturas (ej. Geometría Clásica)</li> 
		<li>-Capítulos (ej. Triángulos)</li>
		<li>-Posts (ej. Definición Baricentro)</li>
		</ul>

		Los <b>posts</b> contienen los pequeños paquetes de conocimiento.
		</div>
	</div>

	<div>
		<div class="bcgreen boxdissap">
		Tipos de posts
		</div>

		<div class="dissap">
		Los <b>posts</b> pueden ser de los siguientes tipos

		<table style="width:90%">
  			<tr>
    			<td><img src="/images/symb/exposition.svg"></td>
    			<td><b>exposition</b> (exposición)</td>
    			<td>Son los primeros contactos con un tema y recogen la motivación, los conceptos intuitivos, las definiciones informales y el significado de los teoremas</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/definition.svg"></td>
    			<td><b>definition</b> (definición)</td>
    			<td>Definen los conceptos de modo formal</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/theorem.svg"></td>
    			<td><b>theorem</b> (teorema)</td>
    			<td>Expresan y prueba los resultados importantes sobre los que se construye la matemática</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/lemma.svg"></td>
    			<td><b>lemma</b> (lema)</td>
    			<td>Son resultados auxiliares que, sin tener tanto peso como un teorema, anteceden a estos</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/corollary.svg"></td>
    			<td><b>corollary</b> (corolario)</td>
    			<td>Son consecuencias lógicas de un teorema</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/example.svg"></td>
    			<td><b>example</b> (ejemplo)</td>
    			<td>Llevan a casos concretos toda la teoría, proporcionando bagaje, afianzando el conocimiento y construyendo objetos sobre los que seguir trabajando</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/visualisation.svg"></td>
    			<td><b>visualisation</b> (visualización)</td>
    			<td>Apoyan la teoría con un elemento visual (imagen o vídeo)</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/applet.svg"></td>
    			<td><b>applet</b> (interactivo)</td>
    			<td>Apoyan la teoría con un elemento interactivo</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/remark.svg"></td>
    			<td><b>remark</b> (comentario)</td>
    			<td>Matizan la teoría en puntos concretos que pueden dar lugar a confusión</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/counterexample.svg"></td>
    			<td><b>counterexample</b> (contraejemplo)</td>
    			<td>Prueban que una implicación no es válida al establecer un caso en que ésta no ocurre</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/problem.svg"></td>
    			<td><b>problem</b> (problema)</td>
    			<td>Ponen a prueba el conocimiento adquirido y refuerzan todo el aprendizaje</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/biography.svg"></td>
    			<td><b>biography</b> (biografía)</td>
    			<td>Esquematizan el impacto que una persona ha tenido en la historia y el pensamiento de las matemáticas</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/quotation.svg"></td>
    			<td><b>quotation</b> (cita)</td>
    			<td>Recogen frases o textos históricos que capten el espíritu de las matemáticas</td> 
  			</tr>
  			<tr>
    			<td><img src="/images/symb/unfinished.svg"></td>
    			<td><b>unfinished</b> (inacabado)</td>
    			<td>Son los posts que no se han acabado, pero cuya existencia es necesaria para el entramado de enlaces</td> 
  			</tr>
		</table>

		</div>
	</div><br>

	<b>Construcción</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		GitHub
		</div>

		<div class="dissap">
		El material con el que se construye la página web está alojado en el repositorio <b>beta_mathifold</b> en GitHub: <a href="https://github.com/jxm-math/beta_mathifold" target="_blank">https://github.com/jxm-math/beta_mathifold</a>. De este modo, todo el contenido es de libre acceso. GitHub también ofrece una apropiada plataforma gestionar las distintas contribuciones.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Jekyll
		</div>

		<div class="dissap">
		Mathifold se construye con el generador de páginas web estáticas <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>. Las personas que quieran colaborar en la parte informática deberían tener cierto conocimiento de esta herramienta.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Hoja de navegación
		</div>

		<div class="dissap">
		La Hoja de navegación describe todo el árbol de contenidos en los tres primeros niveles de la jerarquía: temas, asignaturas y capítulos. Se encuentra en el archivo <a href="https://github.com/jxm-math/beta_mathifold/blob/master/_data/nav.yml" target="_blank">/data/nav.yml</a>. Cada capítulo tiene un identificador 'ident' que servirá para añadir posteriormente los posts.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Posts
		</div>

		<div class="dissap">
		Los posts están alojados en la carpeta <a href="https://github.com/jxm-math/beta_mathifold/tree/master/_posts" target="_blank">/_posts</a> y están separados por idiomas. Cada post es un archivo <b>.md (markdown)</b> con nombre 'aaaa-mm-dd-nobre-del-archivo.md'. Este archivo tiene una cabecera, que es como la 'ficha técnica' del post, y después tiene el contenido. En la ficha técnica hay que rellenar los siguientes apartados:

		<ul style="list-style-type: none;">
		<li>-<b>title</b>: Título del post</li>
		<li>-<b>lang</b> y <b>category</b>: en ambos el código del idioma del post</li> 
		<li>-<b>permalink</b>: código-de-idioma/ident</li>
		<li>-<b>ident</b>: un identificador que debe ser distinto para cada post y que intente sintetizar el contenido de éste. Suele comenzar con el tipo de post.</li>
		<li>-<b>parent</b>: el identificador del capítulo al cual pertenece, según la Hoja de navegación.</li>
		<li>-<b>kind</b>: el código de tipo de post.</li>
		<li>-<b>mathjax</b>: 'true' o 'false' según si la página necesita utilizar mathjax (LaTeX para HTML).</li>
		<li>-<b>layout</b> y <b>type</b>: se dejan con 'post'.</li>
		</ul>

		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Material multimedia
		</div>

		<div class="dissap">
		Material multimedia
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Enlaces
		</div>

		<div class="dissap">
		Enlaces
		</div>
	</div><br>

	<b>Programas utilizados</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Geogebra
		</div>

		<div class="dissap">
		Geogebra
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		IPE Drawing Editor
		</div>

		<div class="dissap">
		IPE Drawing Editor
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Blender
		</div>

		<div class="dissap">
		Blender
		</div>
	</div><br>

	<b>Cómo colaborar</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Tareas
		</div>

		<div class="dissap">
		Tareas
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Construir desde GitHub
		</div>

		<div class="dissap">
		Construir desde GitHub
		</div>
	</div><br>
	

</div>