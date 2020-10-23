# C3-Challenge

This repo contains my solution to the c3.ai COVID [Challenge](https://c3.ai/c3-ai-covid-19-grand-challenge/how-it-works/).

# Projects may address but are not limited to:

-   Applying machine learning/AI methods to mitigate the spread of COVID-19
-   Genome-specific COVID-19 medical protocols, including precision medicine of host responses​
-   Biomedical informatics methods for drug design and repurposing existing therapies​
-   Design and sharing of clinical trials for collecting and analyzing data on medications, therapies, and interventions​
-   Modeling, simulation, prediction of COVID-19 propagation and efficacy of interventions​
-   Logistics and optimization analysis for design of public health strategies and interventions​
-   Rigorous approaches to designing sampling and testing strategies​
-   Data analytics for COVID-19 research harnessing private and sensitive data, including the role of edge computing/IoT for gathering data​
-   Improving societal resilience in response to the spread of the pandemic​
-   Broader efforts in biomedicine, infectious disease modeling, response logistics and optimization, public health, tools, and methodologies around the  containment of infectious diseases, and response to pandemics so as to be better prepared for future infectious disease response.​

# Some thoughts & ideas:

- There are few critical areas for any viral disease:
  - Virus spreading and transmission
  - Asymptomatic and presymptomatic virus shedding (the incubation period)
  - Diagnosis
  - Treatment
  - Vaccine development
  - Origin of virus
  - Viral pathogenesis
  
### Ideas on vaccine allocation
- On vaccince allocation problem, instead of prioritizing groups of people and vaccinate them in order, what if we vaccince people from all the groups and with different proportions? For example, let's say, there are four groups: first responders, elderly, people with precondition, general public. One policy is to prioritize these groups and vaccinate them in order, say, 1-elderly, 2-first-responders, etc. An alternative policy is to vaccincate people from each group but just with different proportions. So, it'd be for example first-responders (90%), elderly (80%), people with precondition (50%), general public (20%). So, really the question is: **Which policy yields better results in terms of minimizing morbidity and mortality rates _faster_? and if the latter policy turns out to be the better policy, what's the percentages of each group who should receive the vaccine given the initial state?**
  - **Note:** The **initial states** for each group are factors such as % of coverage, morbidity and mortality rate, etc.
- How do we choose groups? by age? by occupation? by health status? or a combination of them?

# Miscellaneous

Here, we gather relevant sources about infectious disease mathematical modeling:

- [Mathematical modelling of infectious disease](https://en.wikipedia.org/wiki/Mathematical_modelling_of_infectious_disease)
- [Facebook AI model to forecast the spread of COVID-19](https://ai.facebook.com/blog/using-ai-to-help-health-experts-address-the-covid-19-pandemic/)

# Vaccine Allocation

Vaccinating massive number of people is a challenging task. Below, we document related materials about this topic.

- [Challenges of Achieving Mass COVID-19 Vaccination - Johns Hopkins](https://www.biospace.com/article/johns-hopkins-lays-out-the-public-health-challenges-of-achieving-massive-covid-19-vaccination/)
- [Framework for Equitable Allocation of COVID-19 Vaccine](https://www.nap.edu/catalog/25917/framework-for-equitable-allocation-of-covid-19-vaccine)
- [A Framework for Equitable Allocation of Vaccine for the Novel Coronavirus](https://www.nationalacademies.org/our-work/a-framework-for-equitable-allocation-of-vaccine-for-the-novel-coronavirus#sectionProjectScope)
- [WHO SAGE values framework for the allocation and prioritization of COVID-19 vaccination](https://apps.who.int/iris/bitstream/handle/10665/334299/WHO-2019-nCoV-SAGE_Framework-Allocation_and_prioritization-2020.1-eng.pdf?ua=1)
- [Framework for equitable allocation of a COVID-19 vaccine for adoption by HHS, state, tribal, local, and territorial authorities](https://www.sciencedaily.com/releases/2020/10/201002111729.htm)
- [CDC - Guidance on Allocating and Targeting Pandemic Influenza Vaccine during an Influenza Pandemic](https://www.cdc.gov/flu/pandemic-resources/national-strategy/planning-guidance/index.html)
- [Interim Framework for COVID-19 Vaccine Allocation and Distribution in the United States - August 2020](https://www.centerforhealthsecurity.org/our-work/pubs_archive/pubs-pdfs/2020/200819-vaccine-allocation.pdf)
- [An ethical framework for global vaccine allocation](https://science.sciencemag.org/content/369/6509/1309/tab-pdf)
- [AMA statement on framework for equitable COVID-19 vaccine allocation](https://www.ama-assn.org/press-center/ama-statements/ama-statement-framework-equitable-covid-19-vaccine-allocation)
- [Allocating and Targeting Pandemic Influenza Vaccine During an Inf luenza Pandemic](https://www.cdc.gov/flu/pandemic-resources/pdf/2018-Influenza-Guidance.pdf)
- [Trump Administration Releases COVID-19 Vaccine Distribution Strategy](https://www.hhs.gov/about/news/2020/09/16/trump-administration-releases-covid-19-vaccine-distribution-strategy.html)
- [Optimal pandemic influenza vaccine allocation strategies for the Canadian population](https://europepmc.org/article/pmc/pmc2865540)
- [Fairness versus Efficiency of Vaccine Allocation Strategies](https://www.sciencedirect.com/science/article/pii/S1098301514047718)


