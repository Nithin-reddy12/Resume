This code may help you to do the same template

%-------------------------
% Resume in Latex
% Author : Abey George
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}



%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
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

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
      
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
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}


\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------


\begin{center}
    {\Huge \scshape Sai Nithin Reddy} \\ \vspace{1pt}
    Andhra Pradesh,Guntur \\ \vspace{1pt}
    \small \href{tel:#}{ \raisebox{-0.1\height}\faPhone\ \underline{+91-9963785581} ~} \href{mailto:yourname@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{gsainithinreddy2002@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/sai-nithin-692856218/}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{Linkedin}}  ~
    \href{https://github.com/Nithin-reddy12}{\raisebox{-0.2\height}\faGithub\ \underline{Github}} ~
    \vspace{-8pt}
    
    
\end{center}
 \vspace{0.5mm}


%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Vellore Institute of Technology, Amaravati}{2020 – 2024}
      {B.Tech - Computer Science and Engineering - \textbf{CGPA} - \textbf{7.98}}{Amaravati, Andhra Pradesh}
      \resumeSubHeadingListEnd
      
      \resumeSubheading
      {Sastra Junior College, Vijayawada}{2018-2020}
      {Intermediate - \textbf{CGPA} - 
      \textbf{8.79}}{Vijayawada, Andhra Pradeah}
  \resumeSubHeadingListEnd
  
      \resumeSubheading
      {Dr.KKR'S Gowtham School, Guntur}{2017-2018}
      {10th class - \textbf{CGPA} - 
      \textbf{9.3}}{Guntur, Andhra Pradesh}
      \resumeSubHeadingListEnd
  
%   \resumeSubHeadingListStart
%     \resumeSubheading
%       {College Name}{MM YYYY -- MM YYYY}
%       {Exam Name - Course Name  - \textbf{Percentage} - \textbf{xx\%}}{city, country}
%   \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{COURSEWORK / SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item Java
                \item HTML5,CSS
                \item Java Script, react JS
                \item Oops Concepts
                \item basic Python
                % \item System Design
                \item Software Engineering
                \item MySQL
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{EXPERIENCE}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Intern at Softzant Technologies Pvt Ltd  \href{https://drive.google.com/file/d/181VDWtsFK-Uv1-HVwl3wM0kQvcwCTNRR/view?usp=sharing}{\raisebox{-0.1\height}\faExternalLink }}{Nov 2024 - March 2025} 
      {\underline{Role - Frontend Developer}}{Hyderabad, Telangana}
      \resumeItemListStart
        \resumeItem{\normalsize{Collaborated on designing and developing user-friendly web interfaces using modern frontend technologies.}}
        \resumeItem{\normalsize{Contributed to backend development tasks, including API integrations and server-side logic.}}
        \resumeItem{\normalsize{Develop a User-friendly question and answer platform with essential features.}}
        \resumeItem{\normalsize{Enhanced application performance and usability through efficient coding practices.}}
        \resumeItem{\normalsize{Handle the Database and created a responsive front-end using \textbf{HTML, CSS and JavaScript, react JS.}}}
        
  
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
\vspace{-12pt}

%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
     \resumeProjectHeading
          {\href{#}{\textbf{\large{\underline{Electricity Billing System}}} {\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Java, Spring Boot, MySQL}}}{2023 - 24}\\
          \resumeItemListStart
            \resumeItem {\normalsize{Utilized object-oriented programming principles to ensure modular and scalable code design.}}
            \resumeItem{\normalsize{Implemented functionalities for bill generation, customer record management, and payment tracking.}}
            \resumeItem{\normalsize{Secure RESTful APIs using Spring Security}}
            \resumeItem{\normalsize{JWT Structure: Header (token type & signing algorithm), Payload (user claims), Signature (verifies integrity)}}
            \resumeItem{\normalsize{Database integration with PostgreSQL/MySQL}}
            
            
          \resumeItemListEnd 
          \vspace{-13pt}
    \resumeProjectHeading
          {\href{#}{\textbf{\large{\underline{Interview Creation Portal }}}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{React, JavaScript, Database - mongoDB(development),
         VS Code}}}{2024}\\
          \resumeItemListStart
            \resumeItem {\normalsize {An interview page where the admin can create an interview by selecting participants, start and end time.}}
            \resumeItem{\normalsize{Implemented an interviews list page where admin can see all the upcoming interviews.}}
            \resumeItem{\normalsize{An interview edit page where admin can edit the created interview with the same validations as on the creation page.}}
            
            
          \resumeItemListEnd 
          \vspace{-13pt}
          
         
          
          
      
          
        % \resumeProjectHeading
        %   {\href{https://github.com/FusionIIIT/Fusion/tree/main/FusionIIIT/applications/counselling_cell}{\textbf{\large{\underline{Counselling Cell - \textbf{Fusion IIIT}}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{HTML, CSS, Django, PostgreSQL}}}{2021-22}
        %   \resumeItemListStart
        %      \resumeItem{\normalsize{Develop the \textbf{front-end} of Counselling Cell module in Fusion IIIT.}}
        %     \resumeItem{\normalsize{Module Consists of 4-5 different types of users with different functionalities.}}
        %     \resumeItem{\normalsize{Added \textbf{10-12 new features} like organize the user interface of the Module's \textbf{Home Page}}}
        %     \resumeItem{\normalsize{Handle the database and integrated the module with other existing modules.}}
        %   \resumeItemListEnd
        % \vspace{-13pt}
          
    \resumeSubHeadingListEnd
% \vspace{-12pt}

%


%-----------EXPERIENCE-----------
% \section{INTERNSHIP}
%   \resumeSubHeadingListStart

%     \resumeSubheading
%       {Company Name \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{MM YYYY -- MM YYYY} 
%       {\underline{Role Name}}{city, country}
%       \resumeItemListStart
%         \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
  
%       \resumeItemListEnd  
%   \resumeSubHeadingListEnd
% \vspace{-12pt}
%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Languages:}}{  \normalsize{Java, C++, JavaScript, SQL, basic Python}} \\
     \textbf{\normalsize{Technologies/Frameworks:}}{  \normalsize{HTML5, CSS3, React, MongoDB, Express, Javascript, NodeJS, Bootstrap}} \\
     \textbf{\normalsize{Developer Tools:}}{  \normalsize{VS Code, IntelliJ}} \\
    }}
 \end{itemize}
 \vspace{-15pt}


%-----------INVOLVEMENT---------------

 
  %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}

$\sbullet[.75] \hspace{0.1cm}$ {\href{https://drive.google.com/file/d/1BYS3e8RbTqaf1nptMYktN0fiXJSd5Zub/view?usp=sharing}{Basic to Advanced SQL - Udemy}} \hspace{2.59cm}\\
$\sbullet[.75] \hspace{0.1cm}$ {\href{https://drive.google.com/file/d/17re0NLUOpG3Wo52Z3ih2GUeWEEfyZAqO/view?usp=sharing}{Azure AI Fundamentals}} \hspace{1.6cm}\\
$\sbullet[.75] \hspace{0.2cm}${\href{https://drive.google.com/file/d/1r3s7v9NffQQ2dFPFFVcW_Mx053dGTeiA/view?usp=sharing}{Basic to Advanced HTML and CSS - Udemy}} \hspace{1cm}\\




 \section{EXTRACURRICULAR}
    \resumeSubHeadingListStart
        % \resumeSubheading{Organization Name \href{Certificate Proof link}{\raisebox{-0.1\height}\faExternalLink } }{05-2021 -- 12-2021}{\underline{Role}}{Location}
        
            \resumeItemListStart
                \resumeItem{\normalsize{Passionate and eager to learn, Problem Solving Skills, Creative and adaptable}}
                \resumeItem{\normalsize{Participated in IEEE STUDENT CHAPTER Event Management Lead, Member of CSI-VITAP CHAPTER}}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
 \vspace{-11pt}
 
 \end{document}
 
