# MY-CV-


\documentclass[a4paper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome}
\usepackage{xcolor}

% change color hyperlinks
\hypersetup{%
    colorlinks=true,% hyperlinks will be black
    urlcolor=[rgb]{0.04,0,0.5},
    urlbordercolor=[rgb]{0.7,0.7,0.7},% hyperlink borders will be gray
    pdfborderstyle={/S/U/W 0.5}% border style will be underline of width 1pt
}

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

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
    \item\small{
        \textbf{#1}{: #2 \vspace{-2pt}}
    }
}

\newcommand{\resumeItemPaper}[1]{
    \item\small{
            {#1}
    }
}


\newcommand{\resumeSubheading}[4]{
    \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
        \textbf{#1}       & #2                 \\
        \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
\textbf{\href{}{\Large Dr Federico Tartarini - CV}} & Email: \href{mailto:email@gmail.com}{email@gmail.com} \\
\href{https://www.scopus.com/authid/detail.uri?authorId=57194517775}{Scopus}        \href{https://www.linkedin.com/in/federico-tartarini-3991995b/}{\faLinkedin}
\href{https://github.com/FedericoTartarini?tab=repositories}{\faGithub}
\href{https://scholar.google.com/citations?user=QcamSPwAAAAJ&hl=en}{\faGraduationCap} & \today \\
\end{tabular*}

%-----------EXPERIENCE-----------------
\section{Work and Research Experience}
\resumeSubHeadingListStart

\resumeSubheading
{Berkeley Education Alliance for Research in Singapore (BEARS)}{Singapore, SG}
{Postdoctoral Scholar - SinBerBEST 2}{06/2019 – present}
\resumeItemListStart
\resumeItem{Open source software}{Maintainer and main developer of the CBE Thermal Comfort Tool v2.0 -- web tool for thermal comfort calculations and visualizations; pythermalcomfort -- thermal comfort Python package; CBE Clima Tool -- web tool to analyze climate data; Cozie for iOS and Fitbit -- application for IEQ and physiological data collection.}
\resumeItem{Research}{Conducted a longitudinal thermal comfort study and developed personalized thermal comfort models using wearable and IoT devices. Performed data analysis, and carried out test experiments involving human subjects. Determined under which environmental conditions electric fans can safely cool people.}
\resumeItem{Industrial research projects}{Collaborated in the construction and commissioning of the BCA ZEB+ Building, the first retrofitted Zero Energy Building in Singapore for the Singaporean Building and Construction Authority (BCA). Helped with the development of the BCA Green Mark compliance path.}
\resumeItemListEnd

\resumeSubheading
{ASHRAE 55 committee member}{Atlanta, US}
{SSPC 55 "Thermal Environmental Conditions for Human Occupancy" committee}{11/2020 – present}
\resumeItemListStart
\resumeItem{Addenda}{I wrote 7 addenda for the ASHRAE 55--2017 which are now included in the ASHRAE 55--2020.}
\resumeItemListEnd

\resumeSubheading
{University of Wollongong - Sustainable Buildings Research Centre (SBRC)}{Wollongong, AU}
{Honorary Fellow - Faculty of Engineering}{06/2019 – present}

\resumeSubheading
{University of Wollongong - Sustainable Buildings Research Centre (SBRC)}{Wollongong, AU}
{Associate Research Fellow - Faculty of Engineering}{06/2017 – 06/2019}
\resumeItemListStart
\resumeItem{Industrial research projects}
{Company: Daikin Australia. Developed smart controllers and IoT sensors.}
\resumeItem{Research Grants}
{Project title: LLS1 -- iHUB -- Education (Schools) Living Laboratories. Total grant value AU\$480,570.}
\resumeItem{International Energy Agency Energy in Buildings and Communities (IEA EBC) Annex 69}
{Represented the UOW in the IEA EBC Annex 69 “Strategy and practice of adaptive thermal comfort in low energy buildings”.}
\resumeItem{Data Scientist}{Helped colleagues analyzing data in several research projects and assisted the SBRC in the development of research facilities concerning data acquisition, storage, and analysis.}
\resumeItem{Application developer}{Developed two Android applications.}
\resumeItem{Advantages SME grant}
{Company: Enviro Buildings Services. Developed learning algorithms using Python and Matlab for self-commissioning of HVAC components and models for performance prediction.}
\resumeItemListEnd

\resumeSubheading
{Nier Ing}{Bologna, IT}
{Consultant for an Italian engineering consulting firm}{03/2013 - 02/2014}
\resumeItemListStart
\resumeItem{Activities}
{Conducted feasibility studies for private and public clients. Modeled building energy consumption using EnergyPlus and TRNSYS.}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-----------Teaching experience-----------------
\section{Teaching Experience}
\resumeSubHeadingListStart

\resumeSubheading
{National University of Singapore (NUS)}{Singapore, SG}
{Teaching assistant}{Aug/2020 – present}
\resumeItemListStart
\resumeItem{Course BPS5223 - Data Science for the Built Environment}{Prepared and delivered guest lectures and reviewed students mid-term and final exams.}
\resumeItem{Course BPS5229 - Building Energy Performance - Passive Systems}{Reviewed students mid-term and final presentations.}
\resumeItemListEnd

\resumeSubheading
{University of Sydney}{Sydney, AU}
{Guest lecturer}{Oct/2018}
\resumeItemListStart
\resumeItem{BAEN2002 - Design Integration Lab: Energy}{Prepared and delivered a guest lecture on the Solar Decathlon Competition.}
\resumeItemListEnd

\resumeSubheading
{University of Wollongong}{Wollongong, AU}
{Teaching assistant}{Jul/2016 - Nov/2017}
\resumeItemListStart
\resumeItem{ENG 442/918 - Sustainable Energy in Buildings}{Co-taught the subject, prepared the course material and the exam.}
\resumeItemListEnd

\resumeSubHeadingListEnd


%-----------EDUCATION-----------------
\section{Education}
\resumeSubHeadingListStart
\resumeSubheading
{University of Wollongong - Faculty of Engineering}{Wollongong, AU}
{PhD in Engineering and Information Sciences}{03/2014 - 12/2017}
\resumeSubheading
{University of Bologna - Faculty of Engineering}{Bologna, IT}
{Master of Science Degree in Energy Engineering; Final grade 110/110 cum laude}{09/2010 - 03/2013}
\resumeSubheading
{University of Wollongong - Faculty of Engineering}{Wollongong, AU}
{Exchange program}{09/2012 - 02/2013}
\resumeSubheading
{Technical University of Copenhagen, Denmark - Faculty of Engineering}{Copenhagen, DK}
{Exchange program}{01/2011 - 06/2011}
\resumeSubheading
{University of Bologna, Italy - Faculty of Engineering}{Bologna, IT}
{Bachelor in Energy Engineering; Final grade 108/110}{09/2007 - 07/2010}
\resumeSubHeadingListEnd


%-----------PUBLICATIONS-----------------
\section{Main Peer-reviewed Publications}
\resumeSubHeadingListStart
\item{
\textbf{Journal publications}
\resumeItemListStart
\resumeItemPaper{Földváry Ličina, et al., 2018. Development of the ASHRAE Global Thermal Comfort Database II. Build. Environ. 142, 502–512. https://doi.org/10.1016/j.buildenv.2018.06.022}
\resumeItemPaper{Schweiker, M., et al., 2020. Evaluating assumptions of scales for subjective assessment of thermal environments – Do laypersons perceive them the way, we researchers believe? Energy Build. 211, 109761. https://doi.org/10.1016/j.enbuild.2020.109761}
\resumeItemPaper{Kim, J., Tartarini, F., Parkinson, T., Cooper, P., de Dear, R., 2019. Thermal comfort in a mixed-mode building: Are occupants more adaptive? Energy Build. 203, 109436. https://doi.org/10.1016/j.enbuild.2019.109436}
\resumeItemPaper{Tartarini, F., Cooper, P., Fleming, R., 2018. Thermal perceptions, preferences and adaptive behaviours of occupants of nursing homes. Build. Environ. 132. https://doi.org/10.1016/j.buildenv.2018.01.018}
\resumeItemPaper{Tartarini, F., Cooper, P., Fleming, R., Batterham, M., 2017. Indoor Air Temperature and Agitation of Nursing Home Residents with Dementia. Am. J. Alzheimers. Dis. Other Demen. 32. https://doi.org/10.1177/1533317517704898}
\resumeItemPaper{Tartarini, F., Cooper, P., Fleming, R., 2017. Thermal Environment and Thermal Sensations of Occupants of Nursing Homes: A Field Study, Procedia Engineering. https://doi.org/10.1016/j.proeng.2017.04.196}
\resumeItemPaper{Please visit my \href{https://scholar.google.com/citations?user=QcamSPwAAAAJ&hl=en}{Google Scholar} or \href{https://www.scopus.com/authid/detail.uri?authorId=57194517775}{Scopus} profile for the complete list of publications.}
\resumeItemListEnd
}
\resumeSubHeadingListEnd

%-----------Review activities-----------------
\section{Professional Affiliations and Review Activities}
\resumeSubHeadingListStart
\item{
\textbf{Professional Affiliations}: Australian Institute of Refrigeration, Air conditioning and Heating (AIRAH), and ASHRAE 55 committee member.
}
\item{
\textbf{Journal reviews}: reviewed papers for the journals Building and Environment and Energy and Buildings.
}
\item{
\textbf{Overleaf advisor}
}
\resumeSubHeadingListEnd

%-----------CONFERENCES-----------------
\section{Conferences Attended}
\resumeSubHeadingListStart
\item{
\textbf{Oral presentations}
\resumeItemListStart
\resumeItemPaper{Indoor Air 2020: 16th Conference of the International Society of Indoor Air Quality and Climate, Seoul, Korea.}
\resumeItemPaper{IAQVEC: 10th International Conference on Indoor Air Quality, Ventilation and Energy Conservation in Buildings (2019), Bari, IT.}
\resumeItemPaper{SBE16 Sydney: International High-Performance Built Environments Conference (2016), Sydney, AU.}
\resumeItemPaper{AAG National Conference (2016), Canberra, AU.}
\resumeItemPaper{Oral presentation at the 15th National Conference of Emerging Researchers in Aging (2016), Canberra, AU.}
\resumeItemPaper{IPA-International Congress (2016), San Francisco, CA, USA.}
%          \resumeItemPaper{Hammond Care – International Dementia Conference (2016), Sydney, AU.}
%          \resumeItemPaper{AAG and ACS Regional Conference – Embracing the Future (2015), Batemans Bay, AU.}
\resumeItemPaper{13th National Conference of Emerging Researchers in Aging (2014), Adelaide, AU.}
\resumeItemListEnd
}
\resumeSubHeadingListEnd

%-----------AWARDS-----------------
\section{Awards}
\resumeSubHeadingListStart

\resumeSubheading
{Experienced Researcher}{}
{IAQVEC conference}{2019}

\resumeSubheading
{Best Paper Award}{}
{journal Building and Environment}{2018}

\resumeSubheading
{Student of the year}{}
{AIRAH (Australian Institute of Refrigeration, Air Conditioning and Heating)}{2017}

\resumeSubheading
{Best presentation}{}
{15th National Conference of Emerging Researchers in Ageing}{2016}

\resumeSubheading
{Innovation in ageing research}{}
{13th National Conference of Emerging Researchers in Ageing}{2014}

\resumeSubHeadingListEnd

%--------PROGRAMMING SKILLS------------
\section{Skills}
\resumeSubHeadingListStart
\item{ \textbf{Languages}{: Italian, English} }
\item{ \textbf{Programming languages}{: Python, \LaTeX, Javascript, SQL, Matlab, HTML, CSS} }
\item{ \textbf{Softwares}{: JetBrains IDEs, Matlab, Microsoft Office Suite} }
\resumeSubHeadingListEnd

%--------REFERENCES------------
\section{References}
\resumeSubHeadingListStart

\resumeSubheading
{Name Surname}{Email : \href{gmail@gmail.edu}{gmail@gmail.edu}}
{Institute}{}

\resumeSubHeadingListEnd

%-------------------------------------------
\end{document}
