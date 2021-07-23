---
layout: page
title: Resume
permalink: /resume/
feature-img: "assets/img/sample_feature_img_3.png"
---


\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \small#3 & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Aaron Brake} \\ \vspace{7pt}
    \small (330) 458-9422 $|$ \href{mailto:anbrake98@gmail.com}{\underline{anbrake98@gmail.com}} $|$ 
    \href{https://linkedin.com/in/anbrake}{\underline{linkedin.com/in/anbrake}} $|$
    \href{https://github.com/anbrake}{\underline{github.com/anbrake}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {North Carolina State University}{Graduated May 2021}
      {Master of Statistics}{Raleigh, NC}
    \resumeSubheading
      {West Virginia University}{Graduated Dec. 2018}
      {Bachelor of Science in Industrial Math and Statistics, Summa Cum Laude Honors}{Morgantown, WV}
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Graduate Teaching Assistant}{Aug. 2019 -- May 2021}
      {NC State University}{Raleigh, NC}
      \resumeItemListStart
        \resumeItem{Communicated statistical ideas and concepts to undergraduate and graduate students through teaching classes and holding office hours} 
        \resumeItem{Instructed basic and intermediate Python coding skills to undergraduate students}
        \resumeItem{Coordinated with other TA's and professors to manage course logistics and develop assignments}
        \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
%    \resumeSubSubheading
%     {Software Engineer I}{Oct 2014 - Sep 2016}
%     \resumeItemListStart
%        \resumeItem{Apache Beam}
%          {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
%     \resumeItemListEnd
%    \resumeSubHeadingListEnd
%-------------------------------------------

%%% WVU Alumni Data Analyst %%%
    \resumeSubheading
      {Data Analyst}{Oct. 2018 -- July 2019}
      {West Virginia University Alumni Association}{Morgantown, WV}
      \resumeItemListStart
        \resumeItem{Generated a system of statistical analysis to assess data trends and recommend data informed business practices to increase membership, endowments and Alumni Association profits}
        \resumeItem{Designed and implemented data visualizations to relay essential information concisely using both Tableau and Python}
        \resumeItem{Created SQL queries for Alumni and University data Snowflake database}
        \resumeItem{Collaborated with Digital Marketing Coordinator develop target marketing advertisements using Google Analytics using social media data and existing alumni data}
    \resumeItemListEnd

%%% WVU: MAFS Conference and SURE Research %%%
% \resumeSubheading
%   {Summer Undergraduate Research Experience}{Summer 2017}
%   {West Virginia University}{Morgantown, WV}
%   \resumeItemListStart
%     \resumeItem{Formulated methods to analyze forensic trace evidence on duct tape samples, and conducted relevant statistical analysis on collected data}
%     \resumeItem{Responsible for maintaining proper lab notebooks, and managing lab experimentation data}
%     \resumeItem{Research conducted was presented as both a poster and seminar at the MAFS conference in Cincinnati (Aug 2017) }
%   \resumeItemListEnd

  \resumeSubHeadingListEnd

%
%-----------Projects/Research-----------
\section{Projects and Research}
  \resumeSubHeadingListStart
 
%%% ST563: Machine Learning %%%
\resumeSubheading{Machine Learning}{Spring 2021}{Classification and Regression Analysis of Red Wine Quality}{NC State University}
\resumeItemListStart
\resumeItem{Developed predictive models, including the Tree Methods, random forests and bagging, to determine quality based on chemical factors of wines as opposed to arbitrary quality determined by professional tasters}
\resumeItem{Assembled interpretable models, including Logistic Regression methods including LASSO, RIDGE and Best Subsets for vineyards to better understand how to increase their wine quality}
\resumeItem{Tested model assumptions for the logistic models to verify model interpretability}
\resumeItemListEnd

%%% ST740: Bayesian Modeling %%%
\resumeSubheading{Bayesian Analysis}{Fall 2020}
{Prevalence of Childhood Lead Poisoning in Chicago Communities}{NC State University}
\resumeItemListStart
\resumeItem{Constructed Beta, Negative Binomial, and Poisson models in JAGS to determine the prevalence of lead poisoning in 77 Chicago communities}
\resumeItem{Applied the "Spike and Slab" method for variable selection}
\resumeItem{Exploited the geographic structure of the data to perform spatial analysis and modeling}
\resumeItem{Assembled a GitHub repository for code review and project management}
\resumeItemListEnd  

%%% ST758: R package and functions %%%
\resumeSubheading
      {Computational Statistics}{Fall 2020}{Implementing Big Data Bootstrap Methods in R}{NC State University}
\resumeItemListStart
\resumeItem{Established Big Data Bootstrap (BDB) methods, including Bag of Little Bootstraps and Subsampled Double Bootstrap into a R package, which is hosted on GitHub}
\resumeItem{Expanded the BDB algorithms for parallel computing, allowing the algorithms to run up to 10x faster}
\resumeItem{Programmed both the general and parallel implementations of the BDB algorithms into R functions}
\resumeItem{Tested code using one Terabyte of simulated data}
\resumeItem{Conducted Code Review processes during the creation of the code and package}

\resumeItemListEnd


%%% NCSU Datathon: Tableau and Data Visualizations %%%
\resumeSubheading
      {Data Visualizations}{Spring 2021}{Visualizing Raleigh Police Data using Tableau}{NC State University}
\resumeItemListStart
    \resumeItem{Conducted data cleaning and data mining on a Raleigh Police Database}
    \resumeItem{Developed Tableau Dashboards to visualize the complex data and assess trends}
    \resumeItem{Explained results and trends in the data, using the dashboards in a recorded presentation}
\resumeItemListEnd

%%% ST542 Project: Statistical Consulting %%% 
% \resumeSubheading
%       {Statistical Consulting}{Spring 2021}{Analysis of a Novel Statistical Method for Brick Dosimetry}{NC State University}
% \resumeItemListStart
%     \resumeItem{Analyzed the novel statistical method developed by Dr. Hayes at NC State}
%     \resumeItem{Conducted analysis of RSS variability based on parameter perturbations}
%     \resumeItem{Developed statistical theory to test the method}
%     \resumeItem{Investigated distributional fits over quadratic data using nls() function in R}
%     \resumeItem{Constructed plots in R using ggplot2 package}
% \resumeItemListEnd

%%% WVU Capstone %%%
%  \resumeSubheading{Statistical Research}{Spring 2017-Fall 2018}{Extending the Inverse Birthday Problem to Non-Equally Likely Calendars}{WVU}
%  \resumeItemListStart
%  \resumeItem{Conducted theoretical research to extend Inverse Birthday methods to non-uniform calendars}
%  \resumeItem{Used R code to run simulations on the MLE, Model Misspecification, Bootstrap methods developed and used the methods on real data}
%  \resumeItemListEnd
 
 \resumeSubHeadingListEnd

%
%-----------PROGRAMMING SKILLS-----------
\section{Programming and Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    \textbf{Models: }{GLM, Elastic Net, Tree Methods, SVM, PLS, PCR, GAM, Longitudinal Analysis, Bayesian Models} \\
    \textbf{Languages: }{R, Python, SQL, SAS, JAGS/OpenBUGS, LaTex, Java and C++ limited experience} \\
    \textbf{Tools: }{R Studio, R Markdown, Jupyter, Git/GitHub, Snowflake, PyCharm, IDLE} \\
    \textbf{R Libraries: }{tidyverse, ggplot2, caret, MASS, tree, leaps, rjags,  devtools, Parallel, } \\
    \textbf{Python Libraries: }{Pandas, NumPy, Matplotlib, scikit-learn, seaborn}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}



