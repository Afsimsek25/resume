%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
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
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{3.0pt}
\setlength{\columnsep}{-1pt}
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
  \vspace{+4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{+5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{+2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{+2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{0pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{0pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{0pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-5pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
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
    {\Huge \scshape A. Furkan Şimşek} \\ \vspace{1pt}
    Ankara, Türkiye \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +90-543-738-7048 ~ \href{mailto:daloguz11@icloud.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{asimsekfurkan@yandex.com} ~ 
    \href{https://linkedin.com/in/moguzhandal/}{\raisebox{-0.2\height}\faLinkedin\ {afsimsek}}  ~
    \href{https://github.com/oguzhandal}{\raisebox{-0.2\height}\faGithub\ {}}
    \vspace{-10pt}
\end{center}


%-----------EDUCATION-----------
\section{Eğitim}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Anadolu Üniversitesi}{2017 -- 2021}
      {Yönetim Bilişim Sistemleri - Lisans}{}
  \resumeSubHeadingListEnd
  \resumeSubHeadingListStart
    \resumeSubheading
      {Necmettin Erbakan Üniversitesi}{2014 -- 2016}
      {Bilgisayar Programcılığı - Ön Lisans}{}
  \resumeSubHeadingListEnd
  

%-----------EXPERIENCE-----------
 \section{Deneyim}
   \resumeSubHeadingListStart
     \resumeSubheading
       {Quality Museum}{2021 – Halen}
       {Software Developer in Test}{İstanbul, Türkiye}
       \resumeItem{Quality Museum bünyesinde çalışırken, farklı firmalara dış kaynaklı Test Otomasyon Geliştiricisi olarak hizmet verdim. Bunun yanı sıra, Quality Museum’un UXER adlı yazılım ürününün geliştirilmesine React dili kullanarak Frontend Developer olarak katkıda bulundum.}
       \resumeItemListStart
         \resumeSubItem{Doğuş Teknoloji}
           \resumeItemListStart
             \resumeItem
               {Doğuş Teknoloji'nin Sensat.com projesinde çalıştım. Bu süreçte Java ve Selenium kullanarak web arayüzü (UI) test otomasyonları geliştirdim. JMeter kullanarak yük testleri gerçekleştirdim ve Rest-Assured kullanarak API testlerini yaptım. Mevcut manuel test kapsamını genişleterek süreçleri iyileştirdim.}
               \resumeItem{Manuel ve otomasyon testleri ile API testleri sayesinde hata oranını \%90 oranında düşürdük.}
               \resumeItem{Agile metodolojisine göre test planları oluşturdum ve test ekibine liderlik ettim. Proje kapsamında test süreçlerini Agile prensiplerine göre planladım ve uyguladım. Test ekibini yönlendirerek hem otomasyon hem de manuel testlerde verimliliği artırdım, süreç iyileştirmeleri gerçekleştirdim}
           \resumeItemListEnd
         \resumeSubItem{ParamTech}
           \resumeItemListStart
               \resumeItem{ParamTech bünyesinde Netahsilat ve Finrota projelerinde çalıştım. Java, Selenium ve TestNG kullanarak web otomasyon testleri geliştirdim. Bu süreçte, 3000'den fazla otomasyon senaryosu oluşturarak test kapsamını genişlettik ve düzenli olarak raporlama yaptım.}
               \resumeItem{JMeter kullanarak yük testleri gerçekleştirdim ve performans testlerini yönettim.}
               \resumeItem{UI otomasyonu sayesinde hata oranını \%90 oranında düşürdük.}
           \resumeItemListEnd
       \resumeItemListEnd

     \resumeSubheading
       {Verimor Telekominikasyon AŞ.}{Mart 2020 – Ağustos 2020}
       {Software Developer}{İstanbul, Türkiye}
       \resumeItemListStart
         \resumeItem{}
           {Ruby on Rails kullanarak bir web uygulamasının frontend ve backend geliştirmesine katkıda bulundum, ölçeklenebilir özellikler geliştirdim ve harici API'lerle sorunsuz entegrasyon sağladım.}
       \resumeItemListEnd
   \resumeSubHeadingListEnd


%-----------PROJECTS-----------
%\section{Projeler}
%    \vspace{-5pt}
%    \resumeSubHeadingListStart
%      \resumeProjectHeading
%          {\textbf{Evcil Haycan Bakıcı Bulma Uygulaması} $|$ \emph{Java, Google Firebase, XML}}%{Mayıs 2024}
%          \resumeItemListStart
%            \resumeItem{Verileri güvenli ve kolay bir şekilde depolamak için Firebase kullandım.}
%            \resumeItem{Bakıcılar ve evcil hayvan sahiplerini bir araya getiren, kullanıcı dostu bir arayüz oluşturdum.}
%            \resumeItem{Evcil hayvanların ihtiyaçlarına göre bakıcıları evcil hayvan sahipleriyle eşleştiren bir filtreleme sistemi oluşturdum.}
%          \resumeItemListEnd
 %         \vspace{-15pt}
%      \resumeProjectHeading
%          {\textbf{Ağaç Tanıma Uygulaması} $|$ \emph{Java, Image Recognition}}{Kasım 2021}
%          \resumeItemListStart
%            \resumeItem{Gerçek zamanlı olarak yapraklarından ağaçları tanımak için YOLO görüntü tanıma algoritması kullandım ve eğittim.}
%            \resumeItem{Bu projeyle Rise For The World'e başvurdum ve kazanan olarak seçildim.}
%          \resumeItemListEnd 
%          \vspace{-18pt}
%    \resumeSubHeadingListEnd
%\vspace{8pt}


%
%-----------PROGRAMMING SKILLS-----------
\section{Teknik Yetenekler}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Diller}{: Java, C++, React, HTML/CSS} \\
     \textbf{Test Otomasyon Araçları}{:  Selenium, TestNG, Rest-Assured, JMeter, Postman} \\
     \textbf{Teknolojiler/Platformlar}{: Agile Prensipler, Git, Jenkins, Java Spring} \\
     \textbf{Veritabanları}{: PostgreSQL} \\
     \textbf{Test Yönetim Araçları}{: Jira, TestRail, Azure DevOps} \\
    }}
 \end{itemize}
 \vspace{-10pt}


%
%-----------LANGUAGE SKILLS-----------
% \section{Diller}
% \begin{itemize}[leftmargin=0.15in, label={}]
%    \small{\item{
%     \textbf{Türkçe}{: Anadil} \\
%     \textbf{İngilizce}{: C1 Yetkinlik} \\
%    }}
% \end{itemize}
% \vspace{-10pt}
%------RELEVANT COURSEWORK-------
\section{Kurslar}
    \resumeSubHeadingListStart
        \begin{itemize}[itemsep=-5pt, parsep=3pt]
            \item Java Spring Full Stack Developer Eğitimi – İstanbul Eğitim Akademi
            
        \end{itemize}
    \resumeSubHeadingListEnd


%-----------INVOLVEMENT---------------
%\section{Ödüller \& Onurlar}
%    \resumeSubHeadingListStart
%        \resumeSubheading{TUBITAK Ulusal Bilgisayar Olimpiyatları}{Kasım 2019}{Gümüş Madalya}{}
%            \resumeItemListStart
%                \resumeItem{2019 yılında Ulusal Bilişim Olimpiyatları'nda gümüş madalyaya layık görüldüm.}
%            \resumeItemListEnd
%        \resumeSubheading{Rise For The World}{Eylül 2022}{Küresel Kazanan}{}
%            \resumeItemListStart
%                \resumeItem{Eğitim ve üniversite bursları veren küresel yetenek programı.}
%                \resumeItem{80.000 aday arasından 100 kazanan arasından seçildim.}
%                \resumeItem{Londra/Oxford'da tam fonlu, 2 haftalık bir zirvede diğer kazananlarla tanıştım.}
%            \resumeItemListEnd
%        
%    \resumeSubHeadingListEnd
\end{document}
