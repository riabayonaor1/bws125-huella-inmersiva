# BWS 125 · La innovación deja huella

Recorrido educativo inmersivo del proyecto de mantenimiento mecánico e identificación por huella digital. Maqueta propia interactiva en Three.js, con 14 capítulos en el orden de la presentación suministrada, cámara alrededor del vehículo, acercamientos a módulos, espejo, tablero y mesa de presupuesto, movimiento opcional, fotografías y guion descargable.

## Equipo
Sandra Bohada, Tatiana Remolina, Paola Gómez, Linda Alsina y Néstor Peñaranda. Técnica en mantenimiento de motos y motocarros. I. E. Carlos Julio Torrado Peñaranda, SENA y TecnoParque Colombia.

## Ejecutar
Sitio estático, sin instalación ni compilación. Servir `dist/` con un servidor HTTP. Todos los recursos de ejecución son locales. Se navega con scroll, flechas y puntos laterales. En celular la moto se mantiene arriba. El modo de movimiento reducido se respeta y hay controles para pausar y girar libremente.

## Fuentes y alcance
Contenido y fotografías: presentación `2. PROPUESTA TECNICA DEL APRENDIZ 1.pptx`. El total declarado es COP497500; los13 renglones suman COP501500. Se muestran ambos y la diferencia pendiente de revisión. El sistema electrónico debió reiniciarse tras un cortocircuito; la web muestra el funcionamiento propuesto, no una validación final no documentada. No se recogen datos biométricos.

La moto y los componentes son geometrías propias aproximadas para explicar el proyecto; no son CAD oficiales. Referencias anatómicas: Yamaha BWS125; dimensiones y funciones ArduinoNano oficiales; funcionamiento de lectores ópticos Adafruit; convertidor LM2596 Texas Instruments. Enlaces completos en el diálogo Fuentes y modelo.

Three.js r169 (MIT, licencia en assets). GSAP3.13. Fuente DMSans. Secuencia del permiso compuesta con HyperFrames y timeline determinista pausada; player.js es el adaptador de reproducción de la web. El guion PDF se incluye en assets.
