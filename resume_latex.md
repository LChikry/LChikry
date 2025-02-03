```latex
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
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubheadingWithFive}[5]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
      \multicolumn{2}{l}{\textit{\small #5}} \\
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
    \textbf{\Huge \scshape Lahoucine Chikry} \\ \vspace{1pt}
    \small (+212) 06 04 24 48 24 $|$ \href{mailto:x@x.com}{\underline{L.Chikry@gmail.com}} $|$ 
    \href{https://linkedin.com/in/LChikry}{\underline{linkedin.com/in/LChikry}} $|$
    \href{https://github.com/LChikry}{\underline{github.com/LChikry}}
\end{center}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheadingWithFive
      {Al Akhawayn University}{Expected Graduation in 2026}
      {Bachelor of Science in Computer Science, Minor in Communication Studies}{Ifrane, MA}
      {Dual Specialization in Computer Systems and Artificial Intelligence}
    
      \resumeItemListStart
        \resumeItem{\textit{Relevant Coursework}: Technical Writing | Data Structures | Algorithm Analysis | Database Systems | Object-Oriented Programming}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
  
%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Robotics \& Software Engineer}{Nov. 2023 -- Present}
      {AUI Mechatronics Team}{Ifrane, MA}
      \resumeItemListStart
        \resumeItem{Collaborated on designing, building, and coding winning robots in the 2024 National Vex Robotics Championship, securing the team’s 3rd consecutive victory and earning a spot on the international stage in the USA}
        \resumeItem{Conducted robotics and Computer Vision workshops under the AUI Mechatronics Club, teaching students about concepts and technologies that can be used in real-world applications}
        \resumeItem{Currently leading a team to participate in the ROV underwater robotics competition}
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
   % \resumeSubSubheading
   %  {Software Engineer I}{Oct 2014 - Sep 2016}
   %  \resumeItemListStart
   %     \resumeItem{Apache Beam}
   %       {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
   %  \resumeItemListEnd
   % \resumeSubHeadingListEnd
%-------------------------------------------

    \resumeSubheading
      {Teacher Lab Assistant}{Sep 2024 -- Present}
      {Al Akhawayn University}{Ifrane, MA}
      \resumeItemListStart
        \resumeItem{Assisted more than 50 students in understanding Python programming concepts by providing real-time guidance and improving their problem-solving skills and algorithmic thinking}
        \resumeItem{Developed various Python scripts to automate the grading of student submissions, reducing manual effort and saving hours of work per week for professors and fellow lab assistants}
        \resumeItem{Collaborated with professors to develop assignments and quizzes while also ensuring timely and fair grading}
      \resumeItemListEnd

    \resumeSubheading
      {Head of IT and Digital Committee}{April 2021 -- August 2023}
      {Reading for All Initiative - Dakhla Association}{Dakhla, MA}
      \resumeItemListStart
        \resumeItem{Led the association's digitization project, creating a centralized system that optimized workflow and operations}
        \resumeItem{Managed a team responsible for creating engaging digital content, boosting the association’s online presence}
        \resumeItem{Recognized for exceptional contributions, dedication, teamwork, and impactful results in advancing the association’s mission}
    \resumeItemListEnd


  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{QuickBite} $|$ \emph{Java, Telegram Bot API, PostgreSQL, Docker}}{Dec. 2024 -- Present}
          \resumeItemListStart
            \resumeItem{An extensible Telegram bot template for restaurants that enables customers to pre-order meals for pickup or dine-in, achieving a line-free ordering experience during peak hours and improving customer satisfaction}
            \resumeItem{Implemented various design pattern concepts such as Singleton and a layered architecture}
            \resumeItem{Used PostgreSQL for data persistence and Docker for project portability and a seamless production experience}
          \resumeItemListEnd
          
      \resumeProjectHeading
          {\textbf{Computer Vision Workshop} $|$ \emph{Python, MediaPipe, OpenCV}}{November 2024}
          \resumeItemListStart
            \resumeItem{Co-led a hands-on Computer Vision workshop using Python for students at Al Akhawayn University, teaching image processing with OpenCV and face/hand detection with MediaPipe under the AUI Mechatronics Club}
            \resumeItem{Guided participants in building a Rock, Paper, Scissors game using hand detection, reinforcing practical applications of computer vision concepts in real life}
          \resumeItemListEnd

        \resumeProjectHeading
          {\textbf{Unbeatable Tic-Tac-Toe} $|$ \emph{C, GitHub Workflows}}{Feb. 2024 -- Oct. 2024}
          \resumeItemListStart
            \resumeItem{A CLI game with an unbeatable mode, support for multiple players, and a gameplay saving feature}
            \resumeItem{Implemented GitHub Workflows to automatically trigger unit tests, ensuring code quality and reducing errors}

          \resumeItemListEnd
    \resumeSubHeadingListEnd


%-----------PROGRAMMING SKILLS-----------
\section{Skills \& Certifications}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Programming Skills}{: C, Java, Python, SQL, Unit Testing, Design Patterns} \\
     \textbf{Developer Tools}{: Git, Docker, Vim Motions, VS Code, IntelliJ IDEA} \\
     \textbf{Libraries \& APIs}{: VEX Robotics API, Telegram Bot API, MediaPipe, OpenCV, OpenPyXL} \\
     \textbf{Databases}{: PostgreSQL, Coursera Certificate in NoSQL Systems} \\
     % \textbf{Coursera}{: NoSQL Systems} \\
     \textbf{Soft Skills}{: Teamwork, Peer Tutoring, Technical Writing, Project Management} \\
     \textbf{Languages}{: English, Arabic -- \textit{All professional proficiency or above}}
    }}
 \end{itemize}

%-------------------------------------------
\end{document}
```
