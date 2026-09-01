- Course requirements:
- Data Outline (5% of total grade): Early in the semester, students will select and have a dataset approved for their class assignments. The dataset will be robust, detailed, and reliable. The data outline will be a short word document that provides a narrative and motivation for the project, research questions related to the narrative, and an overview of the selected data that focuses on the outcome variable(s) and the predictors that comprise the core of the research question.
- Class presentation (worth 5% of final grade): Each week, starting in week 7, students will be expected to apply what they learned in the previous class to their selected dataset. Students will select which week they want to present and there will be multiple presentations each week. Students will present their analyses in the form of an R Notebook that contains a brief overview of the research question(s) addressed, the motivation for the research question(s), the data used, data cleaning techniques, data analyses, and interpretation of the findings, and future directions. The presentation will be informal and will provide students with the opportunity to talk through a learning analytics pipeline they have developed and share ideas. The presentation should feed directly into a future data assignment and the final project. Students not presenting that week are expected to ask questions, raise concerns, and provide insights to presenters. Presentations will be no longer than five minutes.
- Analog Analytics (30% of total grade): There will be seven analog analytics assignments given throughout the semester. These are back to basics assignments where students will be provided with data and asked to answer a research question using best practices covered in class. Analog analytics will be paper-based, and students will not be allowed to use any assistance (i.e., internet, AI, books, etc…) unless specifically allowed. They will be relatively short and take about ten minutes of class time. Responses will be hand-written in either paragraph or bullet format. Six of the seven assignments will count toward course grading meaning students have a free pass on one assignment (due to absence or just having a bad day).
- Data assignments (60% in total): Starting in week 8, a series of data driven assignments (five in total) will be available. Students can only complete two of them. Each assignment will require students to conduct a data analysis on an independent data set (i.e., not using a data set from the course textbooks or the class data set). A scoring rubric for these assignments along with an example R markdown file is available in BrightSpace. The R Notebook should be heavily commented to demonstrate student knowledge of important lines of code along with the output of the R code. Short, written explanations of the motivation for the study, the background, and concise research questions are required. Findings should also be discussed along with implications and limitations.
- First assignment 10%
- Second assignment 20%
- All data assignments are to be uploaded to Brightspace by 11:59 PM on Sunday of the week due. Files should be labeled using the following: lastname_assignment (example: perez_assignment1). The assignments are to be submitted as a shared Colab Notebook as well as in .pdf format (so comments can be left). In addition, please include the dataframe/tibble that you use for the analyses if allowed.
- Final project (40% of final grade): Students will be responsible for conducting a final data analysis on an outside data set. The final project can include the solutions reported in the data assignments except the project will be a full analysis of the data set in manuscript form (i.e., a conference proceeding submission for Educational Data Mining). A good manuscript should have a well-defined research question, a strong literature review, a research methods section that allows replication, a clear and accurate presentation of the results, and a strong interpretation and explanation of the findings. Code and data (if shareable) will be made available in a GitHub repository. The manuscript should include a minimum of 10-15 references and be around 4,000 words long. A separate rubric to score the final project is available on BrightSpace along with example papers. Starting in week 8, a series of data driven assignments (five in total) will be available. Students can only complete three of them.
- Note: Students can work in pairs or individually on data assignments. Students can change decision and pairs by assignment as desired.
-
-
- ---
-
- Actual text
- EDUC, PSY-PC, SPED 7715
  
  Fundamentals
  of Learning Analytics 
  
  Fall
  2026
  
  *The
  course syllabus provides a general plan for the course; deviations
  may be necessary.*
- #
- # 1.
  Course  i nformation
  
  
  
  | 
   | 
  	Instructor: Scott Crossley
  	Instructor’s
  	Office: Hobbs 316a
  	Class: Monday, 4:15-7:05 pm, Sony Building
  	A2009
   | 
   | 
  	Office Hours: Tuesday, 2-3 PM
  	Virtual office
  	hours: By appointment
  	E-mail: scott.crossley@vanderbilt.edu
   | 
  |
  
  **2. Course description**
  
  This course will provide students with foundational skills and knowledge needed to understand learning analytics and to computationally analyze learner data. These skills will include sourcing educational datasets, developing appropriate analysis pipelines, communicating findings, and experimenting with data wrangling and cleaning, data visualization, and supervised and unsupervised machine learning.
  Specifically, students will be introduced to the R programming language and appropriate R packages (e.g., tidyverse, CARET), relational data, plotting and graphing data, linear and categorical modeling, data splitting and resampling, feature selection and overfitting, data reduction, reproducibility, principal component analysis and cluster analysis. Much of this course will be practice-based, with projects that ask students to analyze data of interest to their field of research, discuss the data from an analytics perspective, and model learning outcomes. No background knowledge in computer programming is necessary.
  
  **3****.
  Course objectives**
  
  In successfully
  completing this course you will:
	- Increase understanding of the basic theories and concepts used in learning analytics
	- Develop of an understanding of R tidy data and the tidyverse
	- Learn the basics of data wrangling and organization
	- Learn to select, compute and interpret predictive models
	- Understand and develop data visualizations
	- Create scalable
	  machine learning models
	- Understand and
	  measure potential machine learning biases
	- Reduce dimensions
	  in large datasets to derive components, factors, and clusters of
	  data
	- Communicate
	  knowledge to a learning analytics audience
	  
	  **4. Course expectations**
	- Complete any assigned readings before each class meeting.
	- Be prepared for analog analytics assignments.
	- Participate in class discussions and assignments.
	- Ask questions or seek guidance if confused or in need of help.
	- Take part in flipped classroom activities.
	- Complete all graded assignments on time.
	- Late assignments will result in an automatic 25% markdown in grade by
	  day.
	- **5. Attendance**
	  
	  Attendance at all class meetings is essential as is completing all readings and assignments so that you are prepared with questions and comments. However, if you feel sick, please do not come to class!
	- **6. Web resources**
	  
	  For this course we will be using BrightSpace. The BrightSpace site contains a copy of the syllabus, assignments, relevant links, and supplemental materials. An easy way to access BrightSpace is to go directly to https://brightspace.vanderbilt.edu/d2l/home and log in.
	- **7. Other resources**
	  
	  Vanderbilt library has a website for [R](https://heardlibrary.github.io/digital-scholarship/script/r/)
	  resources and offers free workshops on [R](https://www.library.vanderbilt.edu/gis-lab/events-workshops/).
	  
	  The Vanderbilt library provides access to the [O'Reilly for Higher Education](http://www.library.vanderbilt.edu/eres?id=1676), which is a multimedia collection of instruction and reference materials focused on computer programming and technology. We will use this extensively in the class (along with websites for the associated books), but there are additional resources available on the O’Reilly website that we will not access.
	  
	  R Studio offers [primer courses](https://rstudio.cloud/learn/primers) that may be of help. 
	  
	  The Software Carpentries offers free courses on [programming with R](http://swcarpentry.github.io/r-novice-inflammation/) and [R for reproducible scientific analysis](https://swcarpentry.github.io/r-novice-gapminder/).
	  
	  Any number of GPTs are quite good at providing in-time feedback and assistance with R programming.
	- **8. Course materials**
	  Required texts: freely available through [O'Reilly
	  for Higher Education](http://www.library.vanderbilt.edu/eres?id=1676) (Vanderbilt sign-in required) or
	  the internet
	  
	  Burger, S. (2018). [*Introduction
	  to Machine Learning with R*](https://learning.oreilly.com/library/view/introduction-to-machine/9781491976432/)*.* Sebastopol, CA:
	  O'Reilly Media, Inc.
	  
	  Kabacoff, R. (2022). [*R
	  in action*.](https://learning.oreilly.com/library/view/r-in-action/9781617296055/)
	  Shelter Island, NY: Manning Publications.
	  
	  Kuhn, M., & Silge, J. (2022). [*Tidy
	  modeling with R*](https://www.tmwr.org/)*.* Sebastopol, CA: O'Reilly
	  Media, Inc.
	  
	  Malik, A., & Tuckfield, B. (2019). [*Applied
	  unsupervised learning with R*](https://learning.oreilly.com/library/view/applied-unsupervised-learning/9781789956399/). Birmingham, UK:
	  Packt publishing
	  
	  Ren, K. (2016). [*Learning
	  R programming*](https://learning.oreilly.com/library/view/learning-r-programming/9781785889776/)*.* Birmingham, UK: Packt
	  publishing
	  
	  Saqr, M. & López-Pernas, S. (2024) [*Learning
	  analytics methods and tutorials*](https://lamethods.org/)
	  
	  [*A practical guide using R*](https://lamethods.org/). NYC: Springer Wickham, H., Çetinkaya-Rundel, M., & Grolemund, G. (2024). [*R for data science*](https://r4ds.hadley.nz/)*.* Sebastopol, CA: O'Reilly
	  Media, Inc.
	- Required on-line courses: freely available on [O'Reilly for Higher Education](http://www.library.vanderbilt.edu/eres?id=1676) (Vanderbilt sign-in required)
	  
	  Kabacoff, R. (2015). [*R in Action*](https://learning.oreilly.com/videos/r-in-action/9781617291388VE/). Shelter Island, NY: Manning Publications
	  
	  NA (2018). [*R Programming for Statistics and Data Science*](https://learning.oreilly.com/videos/r-programming-for/9781789950298/). Birmingham, UK: Packt publishing
	- Software
	  
	  We will be using the latest version of R [4.x](https://www.r-project.org/),
	  [RStudio](https://www.rstudio.com/)
	  and Google Colab. Students should download R and R studio onto their
	  computers and have a Google account. Note that students can get [Colab
	  Plus](https://blog.google/products-and-platforms/products/education/colab-higher-education/) for free for one year.
	  
	  R Core Team (2017). R: A language and environment for statistical
	  computing. R Foundation for Statistical Computing, Vienna, Austria.
	  URL [https://www.R-project.org/](https://www.R-project.org/).
	- Class data set
	  
	  There are a number of class data sets
	  available that we will be using for this class. The class data sets
	  comprise the [Tennessee
	  Department of Education 2018 report card](https://www.tn.gov/education/news/2019/11/25/tdoe-releases-state-report-card-for-2018-19.html), the
	  [Tennessee
	  Educator Survey](https://www.tn.gov/education/districts/federal-programs-and-oversight/data/educator-survey/2018-tennessee-educator-survey.html), [US
	  Education Unification Dataset](https://www.kaggle.com/datasets/noriuk/us-education-datasets-unification-project), and the [College
	  Scorecard](https://collegescorecard.ed.gov/data/) dataset. The data sets provide educational
	  statistics for the state of Tennessee and other states including
	  standardized test scores, teacher retention rates, dropout rates,
	  student discipline funding rates, teacher surveys, and college
	  enrollment, profiles, and earning statistics. Much of data can be
	  categorized by demographic, and individual differences to allow for a
	  number of sub-analyses to be conducted.
	  
	  **9. Course Requirements**
	  
	  **Ph.D. Students**
	  
	  Course requirements for Ph.D. students
	  are below.
	- Data Outline (5%
	  of total grade): Early in the semester, students will select and
	  have a dataset approved for their class assignments. The dataset
	  will be robust, detailed, and reliable. The data outline will be a
	  short word document that provides a narrative and motivation for the
	  project, research questions related to the narrative, and an
	  overview of the selected data that focuses on the outcome
	  variable(s) and the predictors that comprise the core of the
	  research question.
	- Class presentation
	  (worth 5% of final grade): Each week, starting in week 7, students
	  will be expected to apply what they learned in the previous class to
	  their selected dataset. Students will select which week they want to
	  present and there will be multiple presentations each week. Students
	  will present their analyses in the form of an R Notebook that
	  contains a brief overview of the research question(s) addressed, the
	  motivation for the research question(s), the data used, data
	  cleaning techniques, data analyses, and interpretation of the
	  findings, and future directions. The presentation will be informal
	  and will provide students with the opportunity to talk through a
	  learning analytics pipeline they have developed and share ideas. The
	  presentation should feed directly into a future data assignment and
	  the final project. Students not presenting that week are expected to
	  ask questions, raise concerns, and provide insights to presenters.
	  Presentations will be no longer than five minutes.
	- Analog Analytics
	  (20% of total grade): There will be seven analog analytics
	  assignments given throughout the semester. These are back to basics
	  assignments where students will be provided with data and asked to
	  answer a research question using best practices covered in class.
	  Analog analytics will be paper-based, and students will not be
	  allowed to use any assistance (i.e., internet, AI, books, etc…)
	  unless specifically allowed. They will be relatively short and take
	  about ten minutes of class time. Responses will be hand-written in
	  either paragraph or bullet format. Six of the seven assignments will
	  count toward course grading meaning students have a free pass on one
	  assignment (due to absence or just having a bad day).
	- Data assignments
	  (30% in total): Starting in week 8, a series of data driven
	  assignments (five in total) will be available. **Students can only
	  complete two of them**. Each assignment will require students to
	  conduct a data analysis on an independent data set (i.e., not using
	  a data set from the course textbooks or the class data set). A
	  scoring rubric for these assignments along with an example R
	  markdown file is available in BrightSpace. The R Notebook should be
	  heavily commented to demonstrate student knowledge of important
	  lines of code along with the output of the R code. Short, written
	  explanations of the motivation for the study, the background, and
	  concise research questions are required. Findings should also be
	  discussed along with implications and limitations. 
	  
	  
	  First
	  assignment			10%
	  
	  Second
	  assignment		20%
	  
	  All data
	  assignments are to be uploaded to Brightspace by 11:59 PM on Sunday
	  of the week due. Files should be labeled using the following:
	  lastname_assignment (example: perez_assignment1). The assignments are
	  to be submitted as a shared Colab Notebook as well as in .pdf format
	  (so comments can be left). In addition, please include the
	  dataframe/tibble that you use for the analyses if allowed.
	- Final project (40% of final
	  grade): Students will be responsible for conducting a final data
	  analysis on an outside data set. The final project can include the
	  solutions reported in the data assignments except the project will
	  be a full analysis of the data set in manuscript form (i.e., a
	  conference proceeding submission for Educational Data Mining). A
	  good manuscript should have a well-defined research question, a
	  strong literature review, a research methods section that allows
	  replication, a clear and accurate presentation of the results, and a
	  strong interpretation and explanation of the findings. Code and data
	  (if shareable) will be made available in a GitHub repository. The
	  manuscript should include a minimum of 10-15 references and be
	  around 4,000 words long. A separate rubric to score the final
	  project is available on BrightSpace along with example papers.
	  
	  **Non-Ph.D. Students**
	  
	  The course requirements for non-Ph.D.
	  students are similar to those for Ph.D. students and are as follows:
	- Data outline
	  (worth 5% of final grade): Same as Ph.D. requirement above.
	- Class presentation
	  (worth 5% of final grade): Same as Ph.D. requirement above.
	- Analog Analytics
	  (30% of total grade): Same as Ph.D. requirements above but
	  percentage is different.
	- Data assignments
	  (60% in total): Starting in week 8, a series of data driven
	  assignments (five in total) will be available. **Students can only
	  complete three of them**. The assignment parameters are the same
	  as the Ph.D. data assignments above.
	  
	  First
	  assignment			10%
	  
	  Second
	  assignment		20%
	  
	  Third
	  assignment		30%
	  
	  **Note:
	  **Students can work in pairs or individually on data assignments.
	  Students can change decision and pairs by assignment as desired. 
	  
	  **10. Course
	  grading**
	  
	  Grading scale (%)
	  
	  
	  
	  
	  
	  
	  | 
	  | 
	  A	94-100
	  | 
	  | 
	  B+	87-89
	  | 
	  | 
	  B-	80-82
	  | 
	  | 
	  C	73-76
	  | 
	  | 
	  D	60-69
	  | 
	  |
	  
	  | 
	  | 
	  A-	90-93
	  | 
	  | 
	  B	83-86
	  | 
	  | 
	  C+	77-79
	  | 
	  | 
	  C-	70-72
	  | 
	  | 
	  F	below 60
	  | 
	  |
	  
	  **11. Other course policies:  **
	- **E-mail.** I will use your
	  official university e-mail address if I need to contact you between
	  course meetings. You are responsible for checking your mail
	  regularly.
	- **Classroom accommodations:**
	  Vanderbilt is committed to equal opportunity
	  for students with disabilities, as am I. If you need course
	  accommodations due to a disability, please contact [VU
	  Student Access Services](https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Ft.e2ma.net%2Fclick%2F4htc4d%2Fs8xwf7%2F8k2sqp&data=04%7C01%7Ckim.paulsen%40vanderbilt.edu%7Ceb0a242281b84e879adb08d8bce85dba%7Cba5a7f39e3be4ab3b45067fa80faecad%7C0%7C0%7C637467053481110156%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=egsONWIfNYnj0y6oZkcU2OlnRL5gu6IIUVdqTn1GSSc%3D&reserved=0) to
	  initiate the process. After SAS has notified me of relevant
	  accommodations, we will discuss how these accommodations may best be
	  approached in this class, and I will facilitate the accommodations.
	- **Mental health and wellness:**
	  If you are experiencing undue stress that may
	  be interfering with your ability to perform academically,
	  Vanderbilt’s Student Care Network offers a range of support
	  services. The Office of Student Care Coordination (OSCC) is the
	  central and first point of contact to help you navigate and connect
	  to appropriate resources. You can schedule an appointment with the
	  [OSCC](https://www.vanderbilt.edu/carecoordination/)
	  or call 615-343-WELL. You can find a calendar of services at [here](https://www.vanderbilt.edu/studentcarenetwork/satellite-services/).
	  
	  
	  If you or someone you know needs to speak with a
	  professional counselor immediately, the University Counseling Center
	  offers Urgent Care Counseling. Students should call the UCC at (615)
	  322-2571 during office hours to speak with an urgent care clinician.
	  You can also reach an on-call counselor after hours or on the
	  weekends by calling (615) 322-2571 and pressing option 2 at any
	  time. You can find additional information [here](https://www.vanderbilt.edu/ucc/).
	- **Mandatory
	  reporter obligations**. All
	  University faculty and administrators are mandatory reporters. What
	  this means is that all faculty must report allegations of sexual
	  misconduct and intimate partner violence to the Title IX
	  Coordinator. In addition, all faculty are obligated to report any
	  allegations of discrimination to the Title IX Coordinator. If you
	  want to talk with someone in confidence, officials in the Student
	  Health Center, the University Counseling Center, and the Office of
	  the Chaplain and Religious Life (when acting as clergy) can maintain
	  confidentiality. In addition, officials in the [Project
	  Safe Center](https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Ft.e2ma.net%2Fclick%2F4htc4d%2Fs8xwf7%2F0q5sqp&data=04%7C01%7Ckim.paulsen%40vanderbilt.edu%7Ceb0a242281b84e879adb08d8bce85dba%7Cba5a7f39e3be4ab3b45067fa80faecad%7C0%7C0%7C637467053481135148%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=0s8deTqLevfgiuDNZuEQgyCk7Zro5OyvD1MOGr17T9o%3D&reserved=0) have limited
	  confidentiality, in that they must report the incidents but can do
	  so without providing identifying information. The Project Safe
	  Center serves as the central resource for those impacted by sexual
	  misconduct and intimate partner violence and can assist with
	  navigating all facets of the University’s resource and support
	  network and other processes.
	- **Names
	  and pronouns**. If you would like to
	  use a different name or pronouns than those provided through YES,
	  please let me know at any time prior to or during the semester.
	  Information is available through the [LGBTQI
	  Life offices](https://www.vanderbilt.edu/lgbtqi/) about how to
	  change either or both of these in YES.
	- **Cell-phones.** Cell-phone use
	  is prohibited during class or labs. If you are expecting a crucial
	  call during class, inform me ahead of time. Otherwise, you should
	  turn off your cell phone before each class.
	- **Office hours:** Please make
	  use of them. You don’t need to be having difficulties with the
	  material to come to office hours. Feel free to come in and discuss
	  issues that interest you, get feedback assignments, talk about how
	  the course is going, or share any suggestions you have. Also, take
	  advantage of virtual office hours.
	- **Honor code:**
	  All work submitted in this course is governed
	  by provisions of the Vanderbilt University [Honor
	  code](https://www.vanderbilt.edu/student_handbook/the-honor-system/) found in the student
	  handbook. If you have any doubts about how the Honor Code applies to
	  your work in this class, please ask for clarification. Uncertainty
	  about application of the Honor Code does not excuse a violation. 
	  
	  All
	  students will be required to complete the plagiarism tutorial at
	  [https://plagiarism.iu.edu/](https://plagiarism.iu.edu/)
	  by taking and passing the certificate test for Master’s students
	  using their Vanderbilt e-mail. The certificate will be turned in as a
	  homework assignment. If the certificate is not complete, students
	  will not be allowed to turn in data outlines and data assignment, but
	  penalties for late assignments will still apply.
	- **End-of-term
	  ****c****ourse ****e****valuations.**
	  Your constructive assessment of this course plays an indispensable
	  role in shaping education at Vanderbilt
	  University. Upon completing the course, please take the time to fill
	  out the online course evaluation. Comments and suggestions are
	  especially helpful.
	- **Incompletes.**
	  Incompletes are assigned only under extenuating circumstances and
	  only when a significant body of satisfactory work has been completed
	  in a course.
	- **Health
	  and ****s****afety****.**
	  Our mutual commitment to health
	  and safety is vital. Toward that end, all students are expected
	  to adhere to [Vanderbilt
	  Health and Safety Protocols](https://www.vanderbilt.edu/coronavirus/).
	  Guidance
	  may be updated throughout the semester**.**
	- **Generative
	  AI. **You are required to generate your
	  own analyses, ideas, and rough drafts of writing and code. You
	  can use generative AI models (ChatGPT, GPT, DALL-E, Claude, GitHub
	  Copilot, and anything after) as needed to help with coding, editing
	  and phrasing of written assignments, and learning at no penalty as
	  long as you recognize the model’s contribution. Failure to
	  acknowledge the use of AI models will be penalized as plagiarism.
	  Please note that AI models tend to produce incorrect information,
	  incorrect or inefficient code, fake citations, and inaccurate
	  outputs. You are responsible for any inaccurate, biased, offensive,
	  or otherwise unethical content submitted regardless of whether it
	  originally comes from you or an AI model.