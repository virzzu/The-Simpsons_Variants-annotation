---
title: "Introducción"
output: 
  html_document: 
    toc: false
    highlight: tango
    css: style.css
---
##

La obesidad es un trastorno metabólico multifactorial influenciado tanto por factores genéticos como ambientales. Para profundizar en los mecanismos genéticos que contribuyen a esta condición, en este proyecto se ha llevado a cabo un análisis de variantes genómicas mediante la anotación e interpretación de datos de exoma. Se ha trabajado con archivos .vcf simulados, pertenecientes a miembros de la familia de Los Simpson, agrupados según su fenotipo metabólico en tres perfiles: Grupo Obeso 1 (Abraham y Homer Simpson), Grupo Obeso 2 (Marge, Patty y Selma Bouvier) y Grupo Normopeso (Bart, Lisa y Maggie Simpson). Esta organización permite identificar variantes asociadas con la obesidad y evaluar su posible impacto funcional, molecular y clínico en cada individuo. Sin embargo, en este trabajo solo se evalúan los archivos de Bart y Patty.

La metodología aplicada en este proyecto abarca el procesamiento y anotación de archivos .vcf derivados de exomas, utilizando como referencia el genoma humano hg38 (Ensembl). Se ha realizado la identificación de transcritos, localización cromosómica, frecuencias alélicas poblacionales (gnomAD) y análisis de proteínas afectadas. Posteriormente, se han evaluado diferentes tipos de variantes: SNPs, mediante predicciones de patogenicidad (SIFT, PolyPhen), alineamientos de secuencias ortólogas (Clustal Omega) y dominios proteicos afectados (UniProt, AlphaFold); deleciones, mediante evaluación de la secuencia resultante (BioModel) y predicción de funcionalidad; y variantes intrónicas, mediante análisis de posibles efectos sobre el splicing (BDGP Splicing, ESE Finder, Cryp-Skip). Para aportar un contexto clínico y funcional, se han consultado bases de datos de referencia como OMIM para correlacionar las variantes con patologías conocidas y patrones de herencia, así como KEGG Pathways y Reactome para explorar rutas moleculares implicadas en la obesidad.

Este proyecto presenta un flujo de trabajo bioinformático completo para la anotación e interpretación funcional de variantes genómicas. El objetivo principal es identificar posibles variantes genéticas asociadas con la obesidad, comparando sujetos con Normopeso (Bart Simpson) frente a sujetos con Sobrepeso/Obesidad Tipo 2 (Patty Bouvier).

❗️ Todos los datos utilizados son simulados con fines académicos y didácticos. No obstante, los resultados muestran coherencia con la literatura científica sobre genética de la obesidad y metabolismo. El propósito de este repositorio es demostrar competencias técnicas en el análisis de variantes genómicas y su interpretación funcional.

**Objetivos de aprendizaje**

* Anotación de variantes genéticas

* Interpretación funcional de las variantes

* Consulta en bases de datos y correlación clínica

* Análisis de rutas y mecanismos moleculares
