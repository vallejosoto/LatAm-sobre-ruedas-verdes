Resumen del Proyecto
El proyecto propone una solución basada en inteligencia artificial (IA), específicamente técnicas de clustering no supervisado (K-Means y DBSCAN), para identificar qué ciudades latinoamericanas presentan mejores condiciones para implementar sistemas de micro movilidad eléctrica como bicicletas, scooters y vehículos de baja velocidad. Esta propuesta se enmarca en una transición energética justa y busca promover la equidad territorial, la movilidad sostenible y la reducción de emisiones.
Datos Utilizados
Se construyó una base de datos multivariable con los siguientes indicadores:
PIB per cápita (Banco Mundial): mide la capacidad económica.
Emisiones de CO₂ per cápita (Kaggle): refleja el impacto ambiental.
Población total (Our World in Data): muestra el tamaño del mercado.
Densidad poblacional (Banco Mundial): indica concentración urbana.
Tráfico urbano (Kaggle): evalúa la congestión vial.
Los datos fueron limpiados, normalizados y utilizados para construir dos índices: uno de viabilidad por país y otro de tráfico urbano por ciudad.
Modelamiento y Resultados
Se aplicaron dos técnicas de clustering:
K-Means (k=3): dividió las ciudades en tres grupos con niveles alto, medio y bajo de potencial.
DBSCAN: identificó un clúster denso de ciudades prometedoras y trató otras como atípicas.
Resultados clave:
K-Means ofreció una clasificación escalonada clara, útil para orientar decisiones estratégicas.
DBSCAN fue eficaz para detectar agrupamientos naturales, aunque menos útil para clasificaciones jerárquicas.
El método de clustering que se consideró da mejores resultados es el de K-means, pues representa realidades territoriales más precisas. Esta técnica mostró que las ciudades con mayor potencial son:
Ciudad de México
Bogotá
Lima
Conclusiones
La micromovilidad eléctrica es una solución viable y deseable para América Latina en términos sociales, ambientales y económicos.
El enfoque de IA permite una clasificación objetiva de las ciudades, revelando patrones naturales sin necesidad de etiquetas predefinidas.
K-Means fue considerado el método más adecuado por su claridad interpretativa y aplicabilidad estratégica.
La falta de datos limitó la inclusión de más ciudades, pero los resultados permiten guiar políticas públicas e inversiones privadas hacia territorios con mayor potencial.
