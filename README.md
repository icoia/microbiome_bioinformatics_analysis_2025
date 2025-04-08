# Microbiome Bioinformatics Analysis

<h2 id="general">General Information</h2>

<img src="images/poster_BIOF-Mic101.png" width="250" align="right">

<p id="code">
  <strong>Code:</strong>
  <a>BIOF-Mic101</a>
</p>
<p id="teach">
  <strong>Instructor:</strong>
  <a href="https://github.com/memoll">Dr. Mona Parizadeh </a>(Ph.D., PDF)
</p>

<p id="by">
  <strong>Organized by:</strong>
  <a href="https://icoia.org">ICOIA </a>(International Community of Iranian Academics)
</p>

<p id="date">
  <strong>Start Date:</strong>
</p>
  - Esfand 15, 1403 - 7 PM IRAN

<p id="obj">
  <strong>Objective:</strong>
  Metabarcoding and 16S rRNA gene sequencing using R
</p>

<p id="requirements">
  <strong>Requirements:</strong> 
</p>

  - Laptop with a Mac, Linux, or Windows operating system 
    (not a tablet, Chromebook, etc.) with administrative privileges 
  - Access to Wifi 
  - R and Rstudio installed (instructions <a href="#setup">below</a>)
  - Excel or any text editor installed (e.g. TextWrangler, Notepad, BBEdit, etc.)

<p id="contact">
  <strong>Contact:</strong>
  <a href="mailto:{{icoia.onlineschool@gmail.com}}">icoia.onlineschool@gmail.com</a> 
</p>
  
<p id="register">
  <strong>Register:</strong>
  <a href="https://forms.gle/tdnDSKGJ491BBMU5A">here</a> 
</p>

<p id="telegram">
To ask questions about the course, communicate with the instructor and get informed about other free training courses, become a member of the ICOIA Online School 
  <a href="https://t.me/+jIfI2LibaBo2Yzc8?fbclid=PAZXh0bgNhZW0CMTEAAaZlAjc5hfp7mpqw7f8RxznZJ41NhZzFBl5LOjO07NjkorsvyXNDRH0pkNg_aem_l02uj-8pTJF5BiOA2yLSNQ">Telegram Group</a>.
</p>

<h2 id="audience">Audience</h2>
<p id="suit">
This course is suitable for:
</p>

 - Levels: Beginner & Intermediate
 - Fields: Biology, Medicine, Veterinary, and Agriculture & Natural Resources
 - Language: Farsi

<p id="cover">
This course covers the following material:
</p>

 - Introduction to metabarcoding and amplicon sequencing
 - Introduction to R
 - <a href="https://benjjneb.github.io/dada2/tutorial.html">DADA2 Tutorial</a>
 - Introduction to phyloseq package in R
 - Data exploration
 - Statistical analyses of 16S rRNA gene sequences:
   - Taxonomic composition
   - Alpha diversity
   - Beta diversity (ordination)
   - PERmutational Multivariate ANalysis Of VAriance (PERMANOVA)
   - Differential analysis
- Discussion
  - Wrap up of the results of 16S rRNA gene sequence analysis

<h2 id="setup">Setup</h2> 
To participate in this Workshop, please install the following <a href="#r">software</a>, 
complete the <a href="#r-course">R courses for beginners</a>, 
and let us know if you need any help before attending.

<div id="r">
  <h3>Install R and RStudio</h3>
  <p>
    <a href="http://www.r-project.org">R</a> is a free and open-source programming 
    language that is particularly powerful for data exploration, visualization, and 
    statistical analysis. We use <a href="https://posit.co/downloads/">RStudio</a> 
    to interact with R.
  </p>
 
 <div class="row">
   <div class="col-md-4">
     <h4 id="r-windows">Windows</h4>
    <p>
     Please download R for Windows
        from <a href="http://cran.r-project.org/index.html">CRAN</a> to install R, and 
        also install the <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>.
        If you have separate user and admin accounts, please run the installers as an 
        administrator by right-clicking on the .exe file and selecting "Run as administrator" 
        instead of double-clicking. Otherwise, problems may arise later when installing R packages.
    </p>
     <a href="https://www.youtube.com/watch?v=q0PjTAylwoU">Video Tutorial</a>
 </div> 
   
 <div class="col-md-4">
   <p> 
   <h4 id="r-macosx">Mac OS X</h4>
   </p>
   <p>
    Please download R for macOS
       from <a href="http://cran.r-project.org/index.html">CRAN</a> to install R, and also install 
       the <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>.
   </p>
    <a href="https://www.youtube.com/watch?v=5-ly3kyxwEg">Video Tutorial</a>
  </div> 
   
  <div class="col-md-4">
    <h4 id="r-linux">Linux (Debian, Fedora/Redhat, Ubuntu)</h4>
   <p>
    Please download the binary files for your distribution from
    <a href="http://cran.r-project.org/index.html">CRAN</a> to install R, or use a package manager 
     (e.g. run <code>sudo apt-get install r-base</code> for Debian/Ubuntu and run
        <code>sudo yum install R</code> for Fedora/Redhat). Additionally, please install the
        <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>.
   </p>
  </div> 
 </div>
</div>
   
<h3 id="r-course">R for beginners</h3>
To follow the workshop, you must have a basic understanding of R.
Before attending the workshop, please go through the following courses:

  - <a href="https://youtu.be/UGgxfzCoX9k?si=gSHIXaJOQ7CuGDkv">Introduction to R (1)</a>
  - <a href="https://youtu.be/eWa32WxJOnY?si=ZUxdMORnnQd68-GZ">Introduction to R (2)</a> 
  - <a href="http://swcarpentry.github.io/r-novice-inflammation/">Programming with R</a>


<h3 id="db">Download database for taxonomic assignment with DADA2</h3>

  - <a href="https://zenodo.org/records/14169026/files/silva_nr99_v138.2_toGenus_trainset.fa.gz?download=1">silva_nr99_v138.2_toGenus_trainset.fa.gz</a>  
  - <a href="https://zenodo.org/records/14169026/files/silva_nr99_v138.2_toSpecies_trainset.fa.gz?download=1">silva_nr99_v138.2_toSpecies_trainset.fa.gz</a> 

<h3 id="data">Download data for microbial analysis with DADA2</h3>

  - <a href="https://github.com/memoll/MicrobiomeBioinformaticsAnalysisWorkshop2023/tree/7930024179b2da0d86a5eaa9f3982f10494d2cf4/data/mouse_demultiplexed">mouse_demultiplexed</a>
  - <a href="https://github.com/icoia/microbiome_bioinformatics_analysis_2025/blob/main/data/mouse_metadata.csv">mouse_metadata</a>
 
