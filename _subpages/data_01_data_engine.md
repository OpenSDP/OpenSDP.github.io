---
tags: [data]
no_formatting: true
---

### Synthetic Data Engine

OpenSDPsynthR is not actually a dataset; it is a data simulation package written
in R. There are advantages to using simulation to generate synthetic data. The
data can become richer and more complex over time as the simulation code is
tuned and extended. Eventually, it's possible that simulation could leverage
publicly available data to generate synthetic versions of any school district on
demand.

{% include link_box.html
  heading = "OpenSDPsynthR"
  author = "Strategic Data Project"
  programming_language = "R"
  content = "This simulation package generates fully synthetic data with inputs that can be varied to make an infinite number of simulated student populations with different sizes and characteristics. It is used to generate sample data for OpenSDP's College-Going Pathways analysis guides and for our R and Stata analysis template repositories."
  repository = "https://github.com/opensdp/OpenSDPsynthR"
  %}

{% include link_box.html
  heading = "OpenSDPsynthR Templates"
  author = "Strategic Data Project"
  programming_language = "R and Stata"
  content = "These R and Stata template repositories contain files, folders, and sample web guide templates to make it easier to get started with analyses using the OpenSDPsynthR data. Clone or download the repositories to begin."
  rrepository = "https://github.com/opensdp/template-r"
  statarepository = "https://github.com/opensdp/template-stata"
  %}

### Static Synthetic Data
Using machine learning routines to mimic real data is an approach that could work well for analysts who want to demonstrate code on OpenSDP that they have written for their own school systems. For example, SDP's "Faketucky" is a synthetic dataset based on real student data. It was developed as an offshoot of the Strategic Data Project's [college-going diagnostic for Kentucky](https://sdp.cepr.harvard.edu/kentucky-college-going), using the R machine learning routine [synthpop](https://cran.r-project.org/web/packages/synthpop/index.html). "Fake County" is a
synthetic teacher dataset resulting from SDP's human capital diagnostic work.

{% include link_box.html
  heading = "Faketucky"
  author = "Strategic Data Project"
  programming_language = "Stata and R"
  content =  "The Faketucky synthetic college-going analysis file contains high school and college outcome data for two graduating cohorts of approximately 40,000 students. There are no real children in the dataset, but it mirrors the relationships between variables present in real data."
	repository = "https://github.com/opensdp/faketucky"
	%}

  {% include link_box.html
    heading = "Fake County"
    author = "Strategic Data Project"
    programming_language = "Stata"
    content =  "Fake County is a synthetic panel dataset comprising four years
    of teacher data with roughly 10,000 teachers per year. It
    includes information about teacher demographics, assignments,
    salary, credentials, experience, evaluation scores, and hiring and retention
    status, as well as school characteristics.  There are no real teachers in
    the dataset, but it is based on real data."
  	repository = "https://github.com/opensdp/fake-county"
  	%}

### Publicly Available Data
OpenSDP encourages community members to use publicly available data sets and
share the results (as well as guidance for replicating the work). For
example, the Nevada Report Card package from Data Insight Partners extracts and
prepares Nevada school- and district-level data, as well as providing
analysis-ready datasets.

{% include link_box.html
  heading = "nevadaReportCardR"
  author = "Data Insight Partners"
  programming_language = "R"
  content =  "nevadaReportCardr is an open-source R package that provides
  functions to connect to the publicly available API for NevadaReportCard.com.
  Additionally, this package contains already formatted datasets of
  most data available on Nevada Report Card."
  repository = "https://github.com/opensdp/nevadaReportCardR"
  %}

#### Some useful public data sets include:

  [College Scorecard Data](https://collegescorecard.ed.gov/data/): These data provide insights into the performance of colleges eligible to receive federal financial aid, and offer a look at the outcomes of students at those schools.

  [The Ed Data Inventory](https://datainventory.ed.gov/InventoryList) describes data reported to the Department of Education as part of grant activities, along with administrative and statistical data assembled and maintained by the Department.

  [Stanford CEPA data](https://cepa.stanford.edu/seda/data-archive) includes data files with a range of detailed data on educational conditions, contexts, and outcomes in schools and school districts across the United States.
