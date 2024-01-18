---
title: Cambios en los patrones genéticos y epigenéticos en las etapas de progresión del cáncer
subtitle: José María Zamora Fuentes
comite: "Comité Tutoral: Dr. Jesús Espinal Enríquez <br>
Dra. Patricia García López <br>
Dr. Luis Mendoza Sierra"
fecha: Enero, 2023
institute: Universidad Nacional Autónoma de México
css: file.css
theme: white
slideNumber: h.v
---

### Tópicos
- Introducción
- Hipótesis
- Objetivo
- Metodología
- Resultados
- Resumen


### Agradecimientos iniciales
- Jurado
	- Dr. Felix Recillas Targa
	- Dra. Lorena Aguilar Arnal
	- Dr. Alejandro García Carranca
	- Dra. Patricia López 
- Tutor
	- Dr. Jesus Espinal Enriquez
- Presentes

### Descripción
Breve descripción del trabajo en el tiempo.


### Introducción

### Cáncer
<img src="img/Cancer.png">

### Progresión del Cáncer
<img src="img/Etapas.png" width="70%">
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a> Stephen B. Edge, et al. "The American Joint Committee on Cancer: the 7th Edition of the AJCC Cancer Staging Manual and the Future of TNM". Annals of Surgical Oncology 17. 6(2010): 1471–1474.</p>

### Regulación genética y epigenética 
<img src="img/Regulacion.png" width="90%">

### Fuentes de datos
- TCGA (The Cancer Genome Atlas)
	- 11,300 pacientes 
	- más de 30 tejidos de cáncer.
	- Secuenciación de RNA
		- mRNA 
		- miRNA
	- Secuenciación de 450K sitios CpG
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a>The Cancer Genome Atlas Research Network. "Before and After: Comparison of Legacy and Harmonized TCGA Genomic Data Commons Data". Cell Systems. 2019;9(1):24-34.e10.</p>

<aside class="notes">
Que es un experimento RNAseq?
Que es un experimento de miRNAs?
Como se hace la secuención de sitios CpG?
</aside>

### Biología de sistemas
<img src="img/BiologiaDeSistemas.png" width="95%">

### Planteamiento del problema
La **progresión del cáncer** es un fenómeno multi-factorial en el que los componentes genéticos y epigenéticos están fuertemente involucrados.
Actualmente, no se sabe con certeza cuál es la **conexión** entre estos dos factores durante la progresión del cáncer.



### Hipótesis
Con nuestra metodología podemos describir los **posibles mecanismos subyacentes** de control regulatorio llevados a cabo por miRNAs y por metilación sobre genes involucrados en la progresión del cáncer.



### Objetivo
Encontrar **genes clave** que son afectados por **miRNAs** o por **metilación**. Estos genes cambian su programa regulatorio, de expresión y de **co-expresión** durante <br> la progresión del cáncer.



### Metodología

### Flujo de trabajo
<img src="img/workflow-phd.png" width="90%">

### Caso de estudio: Carcinoma Renal
- Cáncer "silencioso" (ausencia de síntomas).
- 80% de los casos se diagnostican de manera incidental en imágenes solicitadas por otros motivos,
- de estos casos, el 20% son diagnosticados en etapas avanzadas,
- en este porcentaje la tasa de mortalidad es del 95% a los 5 años.
- Factores de riesgo:  fumar, hipertensión, obesidad, diabetes.
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[2]</a>James J. Hsieh, et al. "Renal cell carcinoma". Nature Reviews Disease Primers 3. 1(2017).</p>

### CRcc - Características Moleculares
- 85% se encuentran en células claras.
- Línea principal:  Mutaciones en VHL.
- Pérdida en VHL no induce ccRC.
- Biomarcadores de metilación no especificados.
- Histopatalogía con alta degradación de MEC (regado de estroma)
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[2]</a>James J. Hsieh, et al. "Renal cell carcinoma". Nature Reviews Disease Primers 3. 1(2017).</p>

### Muestras de ccRC
| Control | Etapa I  | Etapa II | Etapa III | Etapa IV |
|:-------:|:--------:|:--------:|:---------:|:--------:|
|  72     |  272     |   59     | 123       | 82       |

### Concepto de coexpresión

### Construcción inicial
<img src="img/correlacion.png" width="75%">

### Construcción de redes de coexpresión
<img src="img/redes-start.jpeg" width="75%">



### Resultados

### Coexpresión Gen-Gen (mRNA)

### Expresión en función de la progresión del CRcc
<img src="img/BoxPlot_genesProgression.png" width="70%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[3]</a>Jose Maria Zamora-Fuentes, et al. "Gene Expression and Co-expression Networks Are Strongly Altered Through Stages in Clear Cell Renal Carcinoma". Frontiers in Genetics 11. (2020).</p>

### Redes de coexpresión genética
<img src="img/mRNA-redes2.png" width="70%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[3]</a>Jose Maria Zamora-Fuentes, et al. "Gene Expression and Co-expression Networks Are Strongly Altered Through Stages in Clear Cell Renal Carcinoma". Frontiers in Genetics 11. (2020).</p>

### Enriquecimiento Biológico
<img src="img/mRNA-redesenrich.jpeg" width="70%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[3]</a>Jose Maria Zamora-Fuentes, et al. "Gene Expression and Co-expression Networks Are Strongly Altered Through Stages in Clear Cell Renal Carcinoma". Frontiers in Genetics 11. (2020).</p>


### Regulación genética por microRNAs

### Redes de coexpresión miRNA-gen
<img src="img/miRNAs-Networks.png" width="50%">

### mir217 en las transiciones de ccRC
<img src="img/miRNAs-Net-zoom.png" width="70%">

### mir217 - Modelo
<img src="img/miR-217.png" width="90%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[3]</a>Jose Maria Zamora-Fuentes, et al. "miR-217 regulates different oncogenes during clear cell renal carcinoma progression". Frontiers in Genetics (Revisión).</p>

### Regulación genética por Metilación

### Genes afectados por la metilación
<img src="img/meth-venns.png" width="100%">

### Criterio funcional (Hipometilados)
<img src="img/meth-overHipo.png" width="70%">

### Criterio funcional (Hipermetilados)
<img src="img/meth-underHyper.png" width="90%">

### Enriquecimiento funcional de las 4 etapas
| Metilación    | Gene núcleo   | Función Biológica  | 
|:------------- |:-------------:| -----:|
|  hypo         | ITK           | Activación de células T |
|  hyper        | RAB25         |   Supresor tumoral      |



### Resumen

### Conclusiones
<img src="img/resumen-final.png" width="75%">

### Implicaciones
- La identificación de factores genéticos y epigenéticos que son resultado de experimentos complejos, pueden proveer de nuevas hipótesis con este tipo de métodos computacionales (ingeniería reversa).
- Los resultados in-silico nos pueden proveer de evidencia para  biomarcadores con potencial aplicación clínica.
- Los resultados de estos experimentos computacionales destacan el impacto del caracter inmunológico del cáncer.
- El programa de expresión en cáncer tiene afectaciones debido a patrones regulares en genes particulares que se amplifican como un sistema biológico complejo.


### Trabajo futuro
- Usar esta metodología para evaluar los siguientes tejidos de cáncer.
- Explorar las diferencias en los genes para la metilación.
- Validar experimentalmente los resultados.
    - Experimentos usando sc-RNAseq
- Explorar otras bases de datos (GEO, ENCODE, etc)

### Agradecimientos
- Comité tutoral.
- Comité (exámen de candidatura)
- CONACYT (cvu 267236)
- UNAM, IE e INMEGEN

### Artículos publicados
- Gene Expression and Co-expression Networks Are Strongly Altered Through Stages in Clear Cell Renal Carcinoma. (F. Genetics, 2020)
- Gene co-expression in breast cancer: a matter of distance. (F. Oncology, 2021)
- Loss of long distance co-expression in lung cancer (F. Genetics, 2021)
- Oncogenic Role of miR-217 During Clear Cell Renal Carcinoma Progression. (F. Oncology, 2022)
- Methylation-related genes involved in renal carcinoma progression  (F. Genetics, 2023)



### Apendice

### Expresión diferencial (mRNA)
<img src="img/mRNA-diffexp.jpeg" width="75%">

### Expresión Diferencial (miRNA)
<img src="img/miRNAs-etapas_contiguas.png" width="90%">

### Microambiente
<img src="img/microambiente.png" width="80%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[1]</a>Yoshihara K, Inferring tumour purity and stromal and immune cell admixture from expression data. Nat Commun. 2013;4(1):2612.
</p>

### ccRC - CNVS (Amplificaciones)
<img src="img/CNVS-expr-amps-kirc.png" width="80%">

### mir-217 en Pubmed
<img src="img/pubmed-mir217.png" width="60%">

### Mutaciones en ccRC
<img src="img/mutaciones.png" width="60%">

### Cáncer en México
<img src="img/globocan-cancer-kidney-mex.png" width="80%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">Globocan  </a>https://gco.iarc.fr/today</p>

### Aumento de Cáncer de riñon en hombres
<img src="img/globocan-time-kidney-mex.png" width="50%">

### Base de datos TCGA - Tejidos
<img src="img/tcga-db1.png" width="100%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">TCGA  </a>https://portal.gdc.cancer.gov/</p>

### Datos de secuenciación TCGA
<img src="img/tcga-db2.png" width="100%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">TCGA  </a>https://portal.gdc.cancer.gov/</p>

### Método de selección de genes metilados
<img src="img/pipeline-meth.png" width="80%">

### Biogénesis de miRNAs (canónica)
<img src="img/microRNAs-biogenesis.png" width="90%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">Biorender  </a>https://biorender.com/</p>

