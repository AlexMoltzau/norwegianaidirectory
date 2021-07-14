# The Norwegian AI Directory

The Norwegian AI Directory (aidirectory.no) was set up in an effort to create an easily accessible repository of information to help navigate the field of AI in Norway.

This repository on GitHub was set up to share data, code and insight related to this pilot project the Norwegian AI Directory by the Norwegian Artificial Intelligence Research Consortium (NORA). 

NORA aims to strengthen Norwegian research, education and innovation within artificial intelligence, machine learning and robotics. NORA is a collaboration between eight universities, two university colleges and three research institutes in Norway.

The intention of this website is to go beyond the members of NORA and map out information more broadly about Norway, and we intend to partner with other data providers to ensure we provide an accurate picture.

Currently the website contains several tabs with data we can shere here in .csv files:
- AI Projects (curated research information based on data from the Norwegian Research Council).
- Funding (curated list of funding opportunities by the research coordinator in NORA).
- Education (a list of all AI-related courses in Norway).

### AI Projects
The ‘AI Projects’ tab has data gathered from the Norwegian Research Council (NFR). One important aspect to note about data from NFR is that it only shows funding allocations to Norwegian actors, as such it does not show the full sum of an EU project. Searches were made at Prosjektbanken both in Norwegian and English on ‘artificial intelligence’, ‘kunstig intelligens’, ‘machine learning’, ‘maskinlæring’, ‘robotics’, ‘robotikk’, ‘dyp læring’, and ‘deep learning’. Data was exported and joined from these searches in June 2021. The project ID’s were communicated to Kari-Anne Kristensen (system owner at NFR). 2000 projects were pruned to 821. After manually checking each project with a binary coding for relevance (1/0), we arrived at 785 relevant projects. This list of projects will be sent to the NORA research support network for additional quality assurance. One aim in the future is to use a REST API to synchronise with data published by NFR. This is already possible to some extent through the Norwegian Directorate of Digitalisation’s REST API called Datahotell. However, there were discrepancies between the NFR quarterly data published in the Norwegian National Data Catalogue (Felles Datakatalog) and data found on Prosjektbanken. For accuracy we decided to choose Prosjektbanken. The wish long-term would be to use a REST API to directly synchronise relevant data with Prosjektbanken, and manually remove new data entries that we see, through our research support network, lacks relevance for the field of AI. More details about the NFR data can be found in their own description.

### Education
The ‘Education’ tab contains AI-related courses on PhD and master’s level in Norway gathered by NORA. The data gathering was undertaken by NORA and the courses on PhD-level were sent to our education council for quality assurance. The current list of courses now containing courses on master’s level will be sent to the NORA education council for further checks. One possibility to gather more information is through exploring the database for statistics on higher education (DBH). Another suggested pathway is to collaborate more with the newly formed Directorate for Higher Education and Competencies (HK-dir), a merger of several departments under the Norwegian Ministry of Education and Research. We are open to suggestions on how we can gather and display more information about AI-related courses in Norway.

### Funding
The ‘Funding’ tab is structured as a list of opportunities in the field of AI to secure financing for your projects. This list is currently curated by Sachin Gaur, the research coordinator in NORA, and is part of NORA’s contribution towards Research Council of Norway funded EU network for Horizon Europe. Navigating funding from the EU can be challenging, and we do not propose we have a complete list, rather we do our best to highlight the opportunities that we find to share it with you. NORA is also an Innovation Norway funded entrepreneurial ecosystem for innovation, as such you might also see AI-related funding opportunities relevant for startups in the future.
