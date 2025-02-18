%%%%%%%%%%%%%%%%%
% This is an example CV created using altacv.cls (v1.6.4, 13 Nov 2021) written by
% LianTze Lim (liantze@gmail.com), based on the
% Cv created by BusinessInsider at http://www.businessinsider.my/a-sample-resume-for-marissa-mayer-2016-7/?r=US&IR=T
%
%% It may be distributed and/or modified under the
%% conditions of the LaTeX Project Public License, either version 1.3
%% of this license or (at your option) any later version.
%% The latest version of this license is in
%%    http://www.latex-project.org/lppl.txt
%% and version 1.3 or later is part of all distributions of LaTeX
%% version 2003/12/01 or later.
%%%%%%%%%%%%%%%%

%% Use the "normalphoto" option if you want a normal photo instead of cropped to a circle
% \documentclass[10pt,a4paper,normalphoto]{altacv}

\documentclass[10pt,a4paper,ragged2e,withhyper]{altacv}

%% AltaCV uses the fontawesome5 package.
%% See http://texdoc.net/pkg/fontawesome5 for full list of symbols.

% Change the page layout if you need to
\geometry{left=1.25cm,right=1.25cm,top=1.5cm,bottom=1.5cm,columnsep=1.2cm}

% The paracol package lets you typeset columns of text in parallel
\usepackage{paracol}


% Change the font if you want to, depending on whether
% you're using pdflatex or xelatex/lualatex
\ifxetexorluatex
  % If using xelatex or lualatex:
  \setmainfont{Lato}
\else
  % If using pdflatex:
  \usepackage[default]{lato}
\fi

% Change the colours if you want to
\definecolor{VividPurple}{HTML}{3E0097}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
% \colorlet{name}{black}
% \colorlet{tagline}{PastelRed}
\colorlet{heading}{VividPurple}
\colorlet{headingrule}{VividPurple}
% \colorlet{subheading}{PastelRed}
\colorlet{accent}{VividPurple}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

% Change some fonts, if necessary
% \renewcommand{\namefont}{\Huge\rmfamily\bfseries}
% \renewcommand{\personalinfofont}{\footnotesize}
% \renewcommand{\cvsectionfont}{\LARGE\rmfamily\bfseries}
% \renewcommand{\cvsubsectionfont}{\large\bfseries}

% Change the bullets for itemize and rating marker
% for \cvskill if you want to
\renewcommand{\itemmarker}{{\small\textbullet}}
\renewcommand{\ratingmarker}{\faCircle}

%% Use (and optionally edit if necessary) this .tex if you
%% want to use an author-year reference style like APA(6)
%% for your publication list
\input{pubs-authoryear}

%% Use (and optionally edit if necessary) this .tex if you
%% want an originally numerical reference style like IEEE
%% for your publication list
% \input{pubs-num}

%% sample.bib contains your publications
\addbibresource{sample.bib}

\begin{document}
\name{Sebastián Zaragoza}
\tagline{Estudiante de Ingeniería Industrial \& Técnico Electricista}
% Cropped to square from https://en.wikipedia.org/wiki/Marissa_Mayer#/media/File:Marissa_Mayer_May_2014_(cropped).jpg, CC-BY 2.0
%% You can add multiple photos on the left or right
\photoR{2.5cm}{CV-fotito}
% \photoL{2cm}{Yacht_High,Suitcase_High}
\personalinfo{%
  % Not all of these are required!
  % You can add your own with \printinfo{symbol}{detail}
  \email{sebaema2050@gmail.com}
%   \phone{000-00-0000}
  \mailaddress{Manuel A. Saez 2050, 5519}
  \location{Mendoza, AR}
  \phone{2615199946}
  \twitter{@seba_zaragoza}
  \linkedin{sebastián-zaragoza-946216216}
%   \github{github.com/mmayer} % I'm just making this up though.
%   \orcid{0000-0000-0000-0000} % Obviously making this up too.
  %% You can add your own arbitrary detail with
  %% \printinfo{symbol}{detail}[optional hyperlink prefix]
  % \printinfo{\faPaw}{Hey ho!}
  %% Or you can declare your own field with
  %% \NewInfoFiled{fieldname}{symbol}[optional hyperlink prefix] and use it:
  % \NewInfoField{gitlab}{\faGitlab}[https://gitlab.com/]
  % \gitlab{your_id}
	%%
  %% For services and platforms like Mastodon where there isn't a
  %% straightforward relation between the user ID/nickname and the hyperlink,
  %% you can use \printinfo directly e.g.
  % \printinfo{\faMastodon}{@username@instace}[https://instance.url/@username]
  %% But if you absolutely want to create new dedicated info fields for
  %% such platforms, then use \NewInfoField* with a star:
  % \NewInfoField*{mastodon}{\faMastodon}
  %% then you can use \mastodon, with TWO arguments where the 2nd argument is
  %% the full hyperlink.
  % \mastodon{@username@instance}{https://instance.url/@username}
}

\makecvheader

%% Depending on your tastes, you may want to make fonts of itemize environments slightly smaller
\AtBeginEnvironment{itemize}{\small}

%% Set the left/right column width ratio to 6:4.
\columnratio{0.6}

% Start a 2-column paracol. Both the left and right columns will automatically
% break across pages if things get too long.
\begin{paracol}{2}

\cvsection{Experiencia}

\cvevent{Data Analytics}{Corpora}{Octubre 2021 -- Actualidad}{Mendoza, AR}
\begin{itemize}
\item Colaborador desde la fundación y los principios de la Startup
\item Análisis de datos a empresas y emprendimientos

\end{itemize}

\divider

\cvevent{Técnico Electricista}{Particular}{Oct 2018 -- Actualidad}{Mendoza, AR}
\begin{itemize}
\item Realización de instalaciones domiciliarias
\item Identificación y reparación de problemas
\end{itemize}

\divider

\cvevent{Auspicios \& Sales}{AArEII}{2021 --  Actualidad}{Mendoza, AR}
\begin{itemize}
\item Parte del equipo organizador de la JOSEII 2022
\item Parte del equipo organizador del CAEII MENDOZA 2022
\end{itemize}

\divider

\cvsection{Un Día de mi Vida}

% Adapted from @Jake's answer from http://tex.stackexchange.com/a/82729/226
% \wheelchart{outer radius}{inner radius}{
% comma-separated list of value/text width/color/detail}
% Some ad-hoc tweaking to adjust the labels so that they don't overlap
\hspace*{-1em}  %% quick hack to move the wheelchart a bit left
\wheelchart{1.5cm}{0.5cm}{%
  10/13em/accent!30/Dormir,
  25/9em/accent!60/ Facultad,
  5/11em/accent!10/\footnotesize\\[1ex]Gym,
  20/11em/accent!40/Pasar tiempo con familia y amigos,
  5/8em/accent!20/\footnotesize Redes sociales,
  30/9em/accent/CORPORA \& AArEII,
  5/8em/accent!20/Cursos
}

% use ONLY \newpage if you want to force a page break for
% ONLY the currentc column
% ACA PUSE TODO COMO COMENTARIO PARA NO METER OTRA PAGINA MAS
% \newpage

% \cvsection{Publications}

% \nocite{*}

% \printbibliography[heading=pubtype,title={\printinfo{\faBook}{Books}},type=book]

% \divider

% \printbibliography[heading=pubtype,title={\printinfo{\faFile*[regular]}{Journal Articles}}, type=article]

% \divider

% \printbibliography[heading=pubtype,title={\printinfo{\faUsers}{Conference Proceedings}},type=inproceedings]

%% Switch to the right column. This will now automatically move to the second
%% page if the content is too long.
\cvsection{Educación}

\cvevent{Ingeniería Industril}{Universidad Nacional de Cuyo}{2019 -- Actualidad}{}

\divider

\cvevent{Técnico Electricista}{4-111 Ing. Pablo Nogués}{2012 -- 2018}{}
\divider
\switchcolumn

\cvsection{Filosofía de Vida}
\begin{quote}
``¿Si no vas a por todo, a qué vas?''
\end{quote}

\cvsection{Competencias Clave}

\cvachievement{\faMale}{Sociabilidad y Compañerismo}{Para ayudar a todo el que lo necesite}

\divider

\cvachievement{\faUsers}{Uso de herramientas informáticas}{Para sintonizar con las nuevas tendencias tecnológicas}

\divider

\cvachievement{\faChartLine}{Resolución de problemas}{Gran uso del sentido comun para entender problemas y encontrar la solución}

\divider

\cvachievement{\faCircle}{Organización}{Gran capacidad para segmentar mis días y poder afrontar todos mis objetivos}

\cvsection{Fortalezas}

\cvtag{Trabajo Duro}
\cvtag{Persuasivo}\\
\cvtag{Motivador \& Líder}
\cvtag{Responsable}

\divider\smallskip

\cvtag{Paquete Office (intermedio)}
\cvtag{AutoCAD 2D}
\cvtag{Manejo de Redes Sociales}
\cvtag{Latex \& .dot }

\cvsection{Idiomas}

\cvskill{Español}{5}
% \divider

\cvskill{Inglés}{4}
% \divider

\cvsection{Formación Complementaria}

\cvevent{Design Thinking}{INSTITUTO EUROPEO DE POSGRADO}{Junio 2021 }{}

\divider

\cvevent{Diplomatura en Economía Circular}{UNC}{Julio 2021 }{}
\divider
%TODO LO DE ACA LO PONGO CON % PARA NO HACER DOS PAGINAS
%\newpage

%\cvsection{Referees}

% \cvref{name}{email}{mailing address}
%\cvref{Prof.\ Alpha Beta}{Institute}{a.beta@university.edu}
%{Address Line 1\\Address line 2}

%\divider

%\cvref{Prof.\ Gamma Delta}{Institute}{g.delta@university.edu}
%{Address Line 1\\Address line 2}

\end{paracol}

\end{document}
