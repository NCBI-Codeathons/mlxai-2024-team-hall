# Team Hall - Visualizations of Nucleotide Sequences in 3-Dimensional Space using Ziro Studio and Entrez

List of participants and affiliations:
John Hall (PASTEM.ORG) <john.hall@pastem.org>
Raja Jasti CEO, Ziro Studio) <raja@zeroui.com>
Hari Parthasarathy  (UC Berkeley)<hari.a.parthasarathy@gmail.com>
Christopher Fluta (Drexel U.) <FlutaC@gmail.com>
Dimple Amitha Garuadapuri (UC Berkeley) <dimple.a.g@berkeley.edu>
Daniel Chen  (UC Berkeley) <danielchen1009@berkeley.edu>

## Project Goals

### High-Level Overview:

Building human genome visualizations for the next generation of CRISPR enthusiasts, genome sequencers, and bioinformatics engineers.

We live in a day and age where genetic editing is becoming more prevalent - the pivotal 2012 CRISPR paper by Dr. Doudna and Dr. Charpentier has led to the creation of several applications to the initial CAS-9 System, especially around the cures to common somatic cell autoimmune diseases. Leveraging our knowledge of CRISPR, alongside the NLM NCBI libraries, we look to visualize the Hemoglobin Beta B genes associated with Sickle Cell Anemia as a stepping stone to better visualizing how CRISPR CAS-9 systems can affect the mutated regions. In doing so, we can better communicate the efficacy of treatments such as CASGEVY to a younger audience of students within the K-12 system, and inspire students to learn more about genome sequencing and editing. 

### Specific Questions We Considered: 

1) How can we work to integrate Ziro Studio with the NCBI Database to create animated 3D immersion images of genomic information to demonstrate CRISPR editing

2) How might we implement ML/AI to showcase more complicated visualizations, including the folding of mRNA and the folding of CRISPR molecules. 

3) Is it possible to import Entrez packages directly into Ziro Studio and access the NCBI database to create animated 3D immersion images of genomic information to demonstrate CRISPR editing?

   A. Are there visualizations that Ziro Studio can generate from the preliminary molecules?
   B. Do we need any additional libraries or URLs to run open-sourced NumPy Pandas to run stats on large data sets?
   C. To import the library into Ziro Studios, what are the steps we need to take? What commands should we enter? What type of data do we need to import?

4) Do you think it is possible to develop an end-to-end integration of Ziro Studio 3D genomic visualization?  Could we integrate that entire configuration where we add maybe a layer of machine learning in the middle and then use the query tool with machine learning in a way that is more integrated and well-versed?



## Approach
Every character in the target nucleotide sequence array will be compared against a healthy baseline. We have to find a good baseline so that there isn't too much differentiation between them. We will identify mutations, which will be represented in purple, and other mutations represented in other colors sho. 


To get a healthy example, we will use the NCBI database, specifically the Gene & Nucleotide Databases to identify genome sequence.

We will do data mining to find the unhealthy data within their whole array of libraries, looking at variance on specific genomes.  

We will create a model by writing a Python function that takes that as input and generates it with the correct shell.   

We will also make some changes on the query side to ensure that the output is properly formatted. Finally, we can make some minor edits to the output to ensure that it is accurate and useful for further analysis.

We will also use AI to engineer prompts with the query in the entrance packages and get all the nucleotide sequences. From there, we'll copy and paste the nucleoside sequences into Ziro Studio, and then run our code for the visualization.


## Results
We were able to develop two silos: the first is the query tool where we used the Entrez database to identify and analyze genome sequences, and the second is the actual Ziro Studio Visualization. We were able to develop these in parallel, but given the scope and timing of the project, we are still under development to build the AI capabilities to integrate the two silos. 

## Future Work
Younger and untrained audiences can learn about genomic biology through a visual representation of CRISPR.

GitHub can prove that Ziro Studio is capable of so much more than K through 12 education with documentation of the entire platform that was created using Ziro Studio. The import statements into GitHub will be beneficial to the entirety of not just this project.

IGI (Innovative Genomics Institute) projects can use this for visualizations of NCBI data and for experimenting with CRISPR in the lab. In addition, the project can be used to track the progress of other IGI projects. In addition to allowing data to be shared and collaborated, import statements can also be used for data-sharing.

By making browser-based Python with NumPy is possible. We can show that the NCBI platform can have new capabilities. This will likely involve generative AI development

## NCBI Codeathon Disclaimer
This software was created as part of an NCBI codeathon, a hackathon-style event focused on rapid innovation. While we encourage you to explore and adapt this code, please be aware that NCBI does not provide ongoing support for it.

For general questions about NCBI software and tools, please visit: [NCBI Contact Page](https://www.ncbi.nlm.nih.gov/home/about/contact/)

