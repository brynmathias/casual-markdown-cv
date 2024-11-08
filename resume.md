<!DOCTYPE html>
<title>Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.css">
<script src="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.js"></script>
<style>  
  body { line-height:1.5; margin:auto; padding:3px; max-width:1024px; display:none; FONT-FAMILY:"Segoe UI",ARIAL; }
  h1  { font-size:200%; padding:16px; border:1px solid lightgrey; BACKGROUND:#f0f0f0; }
  h2  { border-bottom:1px solid grey; padding:2px }
</style>
<body onload="document.body.innerHTML=md.html(document.body.innerHTML); document.body.style.display='block';">
<!--======= COPY ABOVE CODE AS HEADER, THEN FOLLOW WITH RESUME CONTENT IN MARKDOWN FORMAT =========-->

<img style="float:right;border-radius:50%;width:70px;padding:6px" src="avatar-man.jpg" />

<span style="float:right;padding:6px"> 
  brynmathias@gmail.com <br> mobile: +44 7783161176 <br> Nationality: British
</span>

# Bryn Mathias 

## Executive Summary

* 12+ years of commercial software engineering experience in a variety of languages
* Track record of delivering under extremely demanding conditions
* Track record of building and leading strong engineering teams
* Proficient in python as my daily driver language, rust out of interest and previous C and C++ commercial experience
* DevOps experience in cloud and data center environments


## Work Experience

### Faculty (Various Roles Currently Principal Engineer, 2019 - present) 

During my time at faculty I have been responsible for the delivery and technical work on a variety of consultancy projects which range from system builds to strategy, some highlights of projects are included below.
I was the first hire for the client facing engineer role as such I
  * Grew the customer facing engineering team to approx 30 engineers before the team was reorganised to business unit reporting lines
  * Responsible for creating the engineering progression framework, and have mentored and managed several engineers from L1 to Lead

### Notable projects:
#### NHS Covid response
I was seconded along with our CTO to NHS HQ during covid, faculty lead the data response to covid. Predicting disease transmission at a national level. During this time I was responsible for:
    1. Designing the central data store for holding all covid information, and preserving patient privacy whilst enabling data analysis at a national scale
    2. Agent based modelling of disease transmission, we worked with the oxford big data institute who were the team responsible for suggesting the covid tracking app. They had generated an agent based model in C which was capable of simulating a few hundred thousand interactions, we scaled this to be able to simulate the entire country and ensure correct regional calibration in terms of the transmission rate and population categorisation as well as providing confidence limits in terms of the stochastic nature of the agent based model and the initial conditions. This required creating a python interface for the C program, the ability to define experiments to run for a team of data scientists and creating a highly scalable (up to order 10k compute cores) cluster to perform these experiments in, in Azure.
    3. Liaising with various government departments to collect relevant data, ensure data quality and data security.
    4. Scaling out the users for the compute cluster to other long running experimental groups
    5. Scoping requirements of supporting systems
    6. Communicating results to senior stakeholders and preparing briefs to downing street

#### MOD StratCom
The nature of this work means that I can't go into much detail however during my with them I have:
    1. Deployed overseas to an operational theatre in support of counter-terrorism operations
    2. Been responsible for deploying applications to OFFICIAL-SECRET classification systems
    3. Been responsible for generating application deployment processes to OFFICIAL-SECRET systems
    4. Built along side analysts applications for data search and retrieval tailored to their specific needs
    5. Deployed ML to edge base systems in a variety of harsh environments for real time processing and alerting
    6. Been responsible for a team of military and civilian software engineers, and delegated senior responsible person for the employment of software capabilities including AI enabled systems.
    7. Been responsible for hardware and software integration
    8. Managing the client relationship between Faculty and MOD
    9. Mentoring MOD staff

#### Non project related work:
  * Developed Faculty's engineering deployment principles
  * Developed Faculty's software sign off process for deployment into risky environments
  * Various business development and pitching contributing to securing millions of pounds worth of projects
  * Hiring, including at director level


### Five.ai (DevOps Engineer, Sept 2018 - Apr 2019) 

* DevOps and systems engineering for self driving car research and development

### Various short term contacts (July 2017 - Mar 2018)

* Various short term positions after COHEAT

### CoHeat (Software Engineer, Dec 2015 - July 2017) 
* Second Technical hire
* Migrated a monolithic software application to a microservices architecture, using rest, GRPC and KAFKA
* Some hardware engineering, including reverse engineering of power line and wireless serial heat and water flow metres
* DevOps and testing pipeline creation, hardware maintenance
* Many other duties as it was an early stage startup

### Velocix (Software Engineer Dec 2013 - Dec 2015) 
* Product design and research, evaluating large (multi PB) scale storage solutions, for cost efficiency, feature set and performance. Designed and implemented automated provisioning and roll out of a ~2pb test cluster for storage and video serving applications
* Systematic testing of the cluster in various hardware and software configurations
* Joint research with Intel on the CEPH storage platform.
* Creating test plans and writing stories for the development of the project.
* Designing and running manual performance tests against the Velocix CDN and the Velocix Enhanced Video Origin.
* Writing automated performance tests.
* Debugging errors though the entire network chain, from end user to test hardware to the CDN appliances.


## Education & Qualifications

PhD High Energy Physics - Imperial College London 2009 - 2013
Developed triggering algorithms to filter particle collision events, reducing the data rate from 40 million events per second to approximately 10 events per second for prompt analysis. This required optimizing software for real-time data handling under tight performance constraints. Responsible for measuring data-taking efficiency, managing both software and hardware uptime for the calorimeter trigger system, and conducting data analysis to search for new physics, such as dark matter, using large-scale computing.
Research published in Physical Review Letters: [PhysRevLett.107.221804](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.107.221804)

MSci Theoretical Physics - Royal Holloway University of London 2005 - 2009


## Relevant Skills
* High-Performance Computing: Experience with optimizing real-time data pipelines for efficient processing, applicable to financial data analysis and trading systems.
* Scalable Cloud Infrastructure: Designed and deployed scalable compute clusters on AWS and Azure, capable of handling national-level data requirements.
* Data Security: Experience deploying applications with OFFICIAL-SECRET classification, ensuring data protection and regulatory compliance.

## Proficient Technologies:
AWS, Azure, C, Git, gRPC, High-Performance Computing, Kafka, Linux, Low Latency Systems, macOS, PostgreSQL, Python, Real-Time Data Processing, REST, Rust, Terraform.
  
## Misc. Information

* Availability: Three months' notice.
