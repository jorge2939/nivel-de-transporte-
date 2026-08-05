# nivel-de-transporte-

## Objetivo de la actividad

Investigar, analizar y sintetizar los fundamentos de la capa de transporte, contrastando los protocolos TCP y UDP, y evaluando los factores que afectan el desempeño de las redes de cómputo. El resultado debe presentarse como un artículo de investigación (*paper*) formal, simulando el envío a una conferencia académica.

## Instrucciones generales

Desarrollen un artículo de investigación original de exactamente 5 cuartillas (sin contar referencias, o incluyéndolas si el espacio lo permite) que abarque de manera integral la temática del Tema 1. El documento debe estar redactado bajo estrictos estándares académicos y técnicos.

## Estructura del repositorio

```
articulo_nivel_transporte/
├── main.tex              
└── images/
    ├── handshake.tex     
    ├── handshake.pdf
    ├── congestion.tex    
    └── congestion.pdf
```

## Comandos de LaTeX

- `\documentclass[conference]{IEEEtran}` -> define la clase de documento (formato de artículo IEEE a dos columnas)
- `\newcommand{\nombre}{...}` -> define un comando personalizado reutilizable
- `\usepackage{...}` -> carga paquetes adicionales (matemáticas, gráficos, colores, hipervínculos, listas)
- `\tableofcontents` -> genera automáticamente la tabla de contenidos
- `\begin{document} ... \end{document}` -> delimita el contenido visible del documento
- `\title{...}` -> establece el título del artículo
- `\footnote{...}` -> inserta una nota al pie de página
- `\author{...}` -> establece el bloque de autor(es)
- `\IEEEauthorblockN{...}` -> nombre del autor dentro del bloque IEEE
- `\appendix` -> marca el inicio de los apéndices, reinicia la numeración de secciones
- `\IEEEauthorblockA{...}` -> afiliación/dirección del autor dentro del bloque IEEE
- `\maketitle` -> genera e imprime el título, autor y encabezado en la página
- `\begin{enumerate} ... \end{enumerate}` -> crea una lista numerada
- `\begin{abstract} ... \end{abstract}` -> define el resumen del artículo
- `\begin{IEEEkeywords} ... \end{IEEEkeywords}` -> lista de palabras clave del artículo
- `\begin{description} ... \end{description}` -> crea una lista de términos con descripción
- `\section{...}` -> crea una sección numerada
- `\subsection{...}` -> crea una subsección numerada dentro de una sección
- `\begin{align} ... \end{align}` -> alinea múltiples ecuaciones (paquete `amsmath`)
- `\emph{...}` -> aplica énfasis (cursiva) al texto
- `\textit{...}` -> pone el texto en cursiva
- `\frac{a}{b}` -> escribe una fracción
- `\textbf{...}` -> pone el texto en negrita
- `\texttt{...}` -> pone el texto en fuente monoespaciada (tipo código)
- `\sum_{i=0}^{n}` -> escribe un sumatorio con límites
- `\cite{...}` -> inserta una cita bibliográfica referenciando una clave de `\bibitem`
- `\begin{itemize} ... \end{itemize}` -> crea una lista con viñetas
- `\int_{a}^{b}` -> escribe una integral con límites
- `\item` -> agrega un elemento dentro de una lista
- `\begin{table} ... \end{table}` -> crea un entorno flotante de tabla
- `\begin{matrix} ... \end{matrix}` -> escribe una matriz
- `\begin{tabular} ... \end{tabular}` -> define las columnas y filas de una tabla
- `\hline` -> dibuja una línea horizontal dentro de una tabla
- `\usepackage{algorithm}` -> habilita entornos flotantes para pseudocódigo
- `\caption{...}` -> asigna un título/leyenda a una tabla o figura
- `\label{...}` -> asigna una etiqueta para referenciar con `\ref`
- `\begin{algorithmic} ... \end{algorithmic}` -> escribe pseudocódigo estructurado
- `\ref{...}` -> inserta el número de la sección/tabla/figura referenciada por su `\label`
- `\centering` -> centra el contenido dentro de un entorno 
- `\usepackage{listings}` -> habilita el entorno para insertar código fuente resaltado
- `\begin{figure} ... \end{figure}` -> crea un entorno flotante de figura
- `\includegraphics[...]{...}` -> inserta una imagen (PDF, PNG, JPG) en el documento
- `\begin{lstlisting} ... \end{lstlisting}` -> inserta un bloque de código fuente
- `\begin{equation} ... \end{equation}` -> crea una ecuación numerada
- `\resizebox{...}{...}{...}` -> escala un bloque de contenido (usado para ajustar una ecuación larga al ancho de columna)
- `\newpage` -> fuerza un salto de página
- `\begin{thebibliography} ... \end{thebibliography}` -> define la lista de referencias bibliográficas
- `\bibitem{...}` -> define una entrada bibliográfica individual
- `\clearpage` -> fuerza un salto de página y vuelca todos los flotantes pendientes
- `\def\BibTeX{...}` -> define el logo estilizado de BibTeX
- `\hspace{...}` / `\vspace{...}` -> inserta espacio horizontal/vertical manual
- `\multicolumn{n}{formato}{texto}` -> fusiona celdas de una tabla en una sola columna
- `\renewcommand{...}{...}` -> redefine el comportamiento de un comando existente
- `\multirow{n}{ancho}{texto}` -> fusiona celdas de una tabla en varias filas (paquete `multirow`)
- `\usepackage{hyperref}` -> habilita hipervínculos internos y externos, y enlaces de referencias cruzadas
- `\url{...}` -> inserta una URL con formato de enlace
- `\part{...}` / `\chapter{...}` -> divisiones estructurales de nivel superior 
