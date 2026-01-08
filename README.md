# 🧬 Anotación e interpretación de variantes

Este repositorio es una actividad académica grupal del máster de bioinformática de la UNIR para la asignatura de genética clínica y de poblaciones. Consiste en la **anotación e interpretación de variantes genómicas** relacionadas con la obesidad entre los personajes de la familia de *Los Simpsons*.

👉🏼 Puedes ver todo el trabajo redactado y detallado en el siguiente enlace de GitHub Pages: https://virzzu.github.io/The-Simpsons_análisis-RNAseq/

## 🎯 Objetivos

El objetivo principal de esta actividad es **anotar e interpretar variantes genómicas** relacionadas con la obesidad en los miembros de la familia de *Los Simpsons*, utilizando datos de exoma y diversas herramientas bioinformáticas. Los objetivos específicos son:

1. **Anotación de variantes genéticas**  
   - Procesar archivos `.vcf` mediante *Variant Effect Predictor*, utilizando *hg38* como referencia (*Ensembl*).  

2. **Interpretación funcional de las variantes**  
   - Determinar información general: identificación de transcritos, localización cromosómica, frecuencias alélicas poblacionales (*gnomAD*, *1000 Genomes*) y proteínas afectadas.  
   - Analizar **SNPs**: predicción de patogenicidad (*SIFT*, *PolyPhen*), alineamiento de secuencias ortólogas (*Clustal Omega*) y dominios afectados (*UniProt*, *AlphaFold*).  
   - Analizar **deleciones**: evaluación de la nueva secuencia (*BioModel*) y predicción de funcionalidad.  
   - Analizar **variantes intrónicas**: puntuaciones de *splice sites* (*BDGP Splicing*) y efectos sobre *splicing* (*ESE Finder*, *Cryp-Skip*).  

3. **Consulta en bases de datos y correlación clínica**  
   - Verificar la presencia de variantes en *OMIM* y su relación con patologías conocidas, considerando patrones de herencia.  

4. **Análisis de rutas y mecanismos moleculares**  
   - Explorar rutas moleculares implicadas mediante *KEGG Pathways* y *Reactome*.  
   - Revisar bibliografía relevante sobre los mecanismos moleculares asociados a la obesidad.

## 🍩 Datos y Diseño Experimental

Se han proporcionado archivos `.vcf` de un raspado bucal de miembros de la familia de *Los Simpson* y se ha realizado un análisis de exoma completo en busca de las patologías hereditarias que pudieran padecer. Se han considerado tres fenotipos metabólicos en la familia:

| Grupo | Fenotipo | Muestras (Personajes) |
| :--- | :--- | :--- |
| **Obeso 1** | Obesidad Mórbida | Homer, Abraham |
| **Obeso 2** | Sobrepeso/Obesidad | Marge, Patty, Selma |
| **Normopeso** | Control | Bart, Lisa, Maggie |

*Sin embargo, por la organización de la actividad docente, en este repositorio solo se evalúan los archivos de Bart (Normopeso) y Patty (Obeso 2).

A continuación se muestra el pedigrí de los miembros de la familia de *Los Simpson* a los cuales se les ha realizado el raspado bucal:

<img width="325" height="175" alt="image" src="https://github.com/user-attachments/assets/96f21912-acf5-4f39-a4a1-e88c3430f178" />


## 📂 Estructura del Repositorio

A continuación se detalla la organización de los archivos:





Autores: Rita Pellissa Valera, Samuel Pintos González, Tamara Noya Mosquera, Vanesa de las Heras Hermosilla, Virginia García-Loygorri Arias y Yannis Avlonitis Egea.
