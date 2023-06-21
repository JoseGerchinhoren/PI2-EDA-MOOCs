![HenryLogo](https://assets.soyhenry.com/henry-landing/assets/Henry/logo-white.png)

# Proyecto Individual 2: MOOCs

## Alumno: Gerchinhoren José

## Introduccion

El proyecto individual 2 se trata de realizar un analisis exploratorio de los datos sobre los MOOCs. Los MOOCs (cursos masivos abiertos y online) han desempeñado un papel fundamental al revolucionar la forma en que las personas acceden a la educación. Estas plataformas, como Udemy, edX y Coursera, ofrecen acceso a contenido de calidad y específico, permitiendo a los estudiantes aprender de manera práctica y conveniente desde la comodidad de sus hogares. Con el tiempo, la popularidad de los MOOCs ha aumentado considerablemente, atrayendo tanto a plataformas privadas como a universidades y organizaciones sin fines de lucro que buscan incursionar en este mercado altamente competitivo.

En este contexto, es esencial para las plataformas ajustar sus modelos de negocio, cursos y contenido para captar y retener a la mayor cantidad de clientes. Es por eso que una startup de tecnología ha adquirido conjuntos de datos de posibles competidores con el objetivo de analizar y extraer conclusiones de los datos recopilados. El objetivo principal de este proyecto es segmentar el nivel de ventas según variables como el precio, idioma, nivel y calificación de cada curso, con el fin de evaluar su influencia en la demanda del producto vendido.

El proyecto cuenta con un EDA realizado con python y un dashboard realizado con powerBI.

Para monitorear la eficacia de los objetivos de la empresa, se propone un KPI clave (Indicador Clave de Desempeño) denominado "Tasa de conversión de inscriptos gratuitos a inscriptos pagados". Este KPI se calcula dividiendo el número de inscriptos en cursos pagados entre el número de inscriptos en cursos gratuitos y multiplicándolo por 100. La empresa tiene como objetivo lograr un incremento del 15% en esta tasa en comparación con el año anterior. Este KPI solo se pudo analizar en el dataset de Udemy.

## Requisitos previos

Tener instalado Python, un editor de texto como Visual Studio Code y powerBI para armar el dashboard.

Datasets previos necesarios para el proyecto:
* Coursera_courses.csv
* Coursera_reviews.csv
* edx_courses.csv
* udemy_courses.csv
* coursea_data.csv
* Comments.csv

## Repositorio github

Clonar el repositorio del link https://github.com/JoseGerchinhoren/PI1

El cual posee los archivos:
* README.md : Readme del proyecto.
* coursera_courses_final.csv : dataset de coursera para powerBI.
* edx_courses_final.csv : dataset de edx para powerBI.
* udemy_courses_final.csv : dataset de udemy para powerBI.
* Coursera_courses.csv : dataset de coursera.
* coursea_data.csv : dataset de coursera.
* edx_courses.csv : dataset de edx.
* udemy_courses.csv : dataset de udemy.
* PI02_EDA_José_final.ipynb : Analisis exploratorio de los datos realizado en notebook de python.
* moocs.pbix : dashboard en powerBI.

Links de descarga de datasets necesarios:

https://drive.google.com/drive/folders/1TS76ok6giW7D_l5vc-zu5-cBU_dH3P5H

https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset

https://www.kaggle.com/datasets/hossaingh/udemy-courses

Este dataset "Comments" es muy pesado por lo tanto no se lo puede subir a github.

## Conclusiones

En el contexto actual de la educación en línea, los MOOCs han transformado por completo el panorama educativo. Plataformas como Coursera, edX y Udemy han desempeñado un papel fundamental al proporcionar acceso a contenido de calidad y práctico desde la comodidad del hogar. Al analizar los datos recopilados de estas plataformas, se pueden extraer valiosas conclusiones sobre sus cursos y modelos de negocio.

Al examinar los cursos de Coursera, se observa que el tipo de certificado más popular entre los matriculados es el curso, y el nivel de dificultad más común es el principiante. Con un promedio de puntaje de 4.68, los cursos de Coursera gozan de una sólida reputación. Además, la plataforma ha logrado atraer a una impresionante cantidad de 81 millones de estudiantes y ofrece una amplia variedad de 891 cursos. Destaca el curso "Machine Learning", que cuenta con 3,200,000 matriculados, y la institución líder en matriculaciones es "Stanford University". Por otro lado, se encuentra el curso "El Abogado del Futuro: Legaltech y la Transformación Digital del Derecho" con una menor cantidad de inscritos, alcanzando solo 1,500.

Pasando a los cursos de edX, se evidencia que la orientación con mayor recaudación es "Computer Science", y la institución que más recaudación genera es "Harvard University". Los cursos introductorios son los más comunes en términos de recaudación, y el idioma predominante es el inglés. edX ha logrado atraer a 44,000 estudiantes en total, y su recaudación global alcanza los 5,000 millones. Es interesante destacar que los cursos con una duración semanal de 3 horas son los que generan la mayor recaudación, y aquellos con un solo instructor también tienen un rendimiento destacado. El curso "CS50's Introduction to Computer Science" es el que lidera en términos de recaudación, mientras que "e-Learning on Digital Agriculture" muestra una menor recaudación.

En cuanto a Udemy, la plataforma se destaca por su enfoque en el desarrollo web, siendo la orientación de "Web Development" la que genera más recaudación. Los cursos dirigidos a "All Levels" son los más populares en términos de recaudación, y el año con mayor recaudación fue 2015. Marzo es el mes más exitoso en términos de generación de ingresos. Con una base de 12 millones de estudiantes, Udemy ha logrado una recaudación total de 885 millones. La tasa de conversión de inscriptos gratuitos a inscriptos pagados es del 77.51%, lo que indica un sólido modelo de negocio. Además, los cursos pagados tienen una mayor cantidad de matriculados. El curso "The Web Developer Bootcamp" es el líder en recaudación, mientras que "Affinity Designer - tworzenie wzorków" se encuentra entre los de menor recaudación.

En resumen, el análisis de las tres plataformas revela que cada una tiene sus puntos fuertes y características distintivas. Coursera destaca por su amplia oferta de cursos, la reputación de sus instituciones asociadas y su alto nivel de satisfacción de los estudiantes. edX se posiciona como una plataforma con enfoque académico, colaboraciones destacadas y una sólida recaudación. Por otro lado, Udemy se destaca por su amplia variedad de cursos prácticos y una tasa de conversión de inscriptos gratuitos a inscriptos pagados notablemente alta.

Estos hallazgos resaltan la importancia de comprender las preferencias de los estudiantes y ajustar los modelos de negocio en consecuencia. Los datos recopilados brindan una visión valiosa para las decisiones estratégicas de las plataformas y permiten identificar oportunidades para mejorar la oferta de cursos y aumentar la participación de los estudiantes.

El análisis completo y las conclusiones detalladas se encuentran disponibles en el dashboard y los informes generados a partir de los datos recopilados. Estos hallazgos servirán como punto de partida para la toma de decisiones informadas y la mejora continua de las plataformas de cursos en línea en un mercado cada vez más competitivo.

## Créditos
El recurso externo que mayormente use para crear mi proyecto fue chatGPT.

## Contacto
Telefono celular: +543875990930

Email: josegerchinhoren97@gmail.com

Linkedin: José Gerchinhoren, link: https://www.linkedin.com/in/jos%C3%A9-gerchinhoren-102573249/

Instagram: josegerchinhoren