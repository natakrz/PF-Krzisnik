# PF-Krzisnik

Hola Lau! Hola Maca! Cómo están?
Antes que nada les hago un resumen sobre mi proyecto y mi experiencia:

Mi idea (y la razón por la que me inscribí al curso) era armar un Portfolio personal. Obviamente para cumplir con todas las consignas del curso se fue transformando.
El día de mañana seguramente me arme uno un poco más minimalista. 
El punto fuerte son la fotografía y una serie de Mapas donde tengo marcados Sitios Patrimoniales.

- Link a wireframes entregados al principio: https://drive.google.com/drive/folders/1Bop4R2x5YRCl_HY-uUerBlRVyeau8lXa?usp=sharing

Con respecto a cómo se fue armando con las primeras entregas:

- nav usando BS. 
- Saqué el link a "Home" ya que en las clases se comentó que esto ya es anticuado. 
- Usé el botón hamburguesa.
- carousel, también usé BS, pero van a ver que en el html hay dos: esto es porque mi idea es tener un carousel en la Home únicamente pero que en mobile ocupe toda la pantalla, es un carousel vertical.
- Cuando estoy en Home en mobile oculté todos los textos y dejé un carousel ocupando pantalla completa.
- Los otros html tienen headers fijos porque me parecía muy repetitivo sino.

Quise usar bs + flex + grid y todo lo que vimos, así que el resto de los html están más mezclados:
- La page Mapas está acomodada con flex (aprovecho para mencionar que completé el juego de las ranitas) y es responsive con porcentajes.
No sé si es lo ideal pero quería probar todas las formas.
Las versiones de tablet y mobile van reubicando las columnas y además desaparecen textos para que sea más simple.
- La page Fotografía es un grid, me pareció más cómodo este método a la hora del responsive.  
Las versiones de tablet y mobile también van reubicando las columnas y además desaparecen textos para que sea más simple.
(El responsive fue hecho con Responsive Web Design, no con Mobile First).
(Las Fotografías de MDQ y Mendoza llevan a error404, no tengo fotos de esos lugares pero quería hacer una grilla más grande. Son de relleno.)

Con respecto a la Optimización SEO:
- html:5
- Sections en lugar de divs, mejor.
- Titles.
- Headings correctos h1 sin repetir el uso de h1.
- alt "..." completos.
- Nombres descriptivos en imágenes.
- Ya son hay Lorems.
- No figura código comentado que se dejó de usar.
- Meta description.
- Meta author, por ser mi portfolio.
- Keywords, se menciona en clase que ya no tienen tanto sentido como antes, que es preferible usar palabras clave en los h1, h2, p, etc.
- Links llevan a álbumes de Behance, salvo Mar del Plata y Mendoza. Llevan a error404 porque en realidad son de relleno, no tengo fotos de esos lugares.
- A los links externos de Behance les puse "no follow".
- Página de error404.
- Las imágenes son propias, por lo que están optimizadas y llevadas a 72dpi con Psd.

Otros temas:
Usé Animaciones en la nav y el footer, no sé si son lindos pero para probar.
Parches de @media no quise hacer, esta todo en _breakpoints, me parece más fácil de encontrar.
Usé extends, mixins y nesting.

Espero que anden bien :)
Saludos!
