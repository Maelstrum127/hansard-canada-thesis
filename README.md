# University of Toronto Engineering Science Thesis: Measuring Political Polarization in Canada's Parliament
This repo contains the data, scripts and reports of Connor Glossop's 4th year thesis project. This thesis analyzes the transcript data contained in the LiPaD dataset to measure political polarization in Canada.

# Repo Structure:
This repo is structured as follows: the PDF version of the thesis, Measuring Political Polarization in Canada's Parliament, is located in the root folder. All code that was run is located in the Scripts folder. Intermediate reports, such as the thesis proposal and interim report, are located in the Intermediate Documentation folder. One minor dataset can be found in the Data folder, along with the README which discribes the LiPaD dataset used for topic modelling in this thesis. The LiPaD dataset itself was not included due to GitHub file size limitations.

# Abstract:
This thesis analyzes recent trends in political polarization in Canada through the use of topic modelling algorithms. Due to recent trends of increasing political polarization in many parts of the world, especially the United States of America, analysis on the change in political polarization in Canada could help to identify possible causes and mitigate them before societal conflict occurs. Speeches taken from the Canada's House of Commons between 2004 and 2019 are processed and modelled using Latent Dirichlet Allocation and BERTopic, two popular topic modelling algorithms. The data is then aggregated, with topic frequency distributions measured for each political party. These are compared using Jensen-Shannon Divergence to establish a measure of political polarization between parties over time, as well as Generalized Jensen-Shannon Divergence to find an measure how political polarization in Canada has changed between 2004 and 2019. The level of political polarization in Canada's House of Commons increased between 2004 and 2019, with notable increases in polarization observed prior to each election.

# Background:
Political polarization has been shown to reduce the effectiveness of governments and increase the occurrences of bad policies [1]. To combat this, research has been conducted to try to measure political polarization in various countries, often leveraging the transcripts from government proceedings and outcomes of votes. The Canadian Hansard [2] contains the transcripts of all debates in the Canadian Parliament (both the House of Commons and the Senate). The full transcript of every speech, question and response by Members of Parliament and Senators are recorded every day that the parliament is in session. The results of parliamentary votes are recorded both within the Hansard document for a given day and a separate Votes database [3]. This database contains records of all votes from October 2004 onwards.

In 2021, Alsinet et al. [4] developed metrics for evaluating the political polarization of Reddit users as a substitute for the general population. Hanretty et al. [5] used statistical regression techniques to analyze the left-right split of UK Members of Parliament based on their voting results, while Goet [6] analyzed the UK’s Hansard dataset to estimate dyadic representation in various historical periods. Research has been done into analyzing dyadic representation in Canada [7], however little analysis has been performed on the political polarization present within Canada’s parliament and its change over time.


# References:

[1] C. Testa, “Is polarization bad?,” European Economic Review, vol. 56, no. 6, pp. 1104–1118, Aug. 2012, doi: 10.1016/j.euroecorev.2012.04.005.

[2] “Welcome to the House of Commons of Canada,” Ourcommons.ca, 2018. https://www.ourcommons.ca/en 

[3] “Votes - Members of Parliament - House of Commons of Canada,” www.ourcommons.ca. https://www.ourcommons.ca/members/en/votes

[4] T. Alsinet, J. Argelich, R. Béjar, S. Martínez. (2021). Measuring Polarization in Online Debates. Applied Sciences. Dec. 2021, doi: 10.3390/app112411879. 

[5] C. Hanretty, B. E. Lauderdale, and N. Vivyan, “Dyadic Representation in a Westminster System,” Legislative Studies Quarterly, vol. 42, no. 2, pp. 235–267, Aug. 2016, doi: 10.1111/lsq.12148.

[6] N. D. Goet, “Measuring Polarization with Text Analysis: Evidence from the UK House of Commons, 1811–2015,” Political Analysis, vol. 27, no. 4, pp. 518–539, 2019.

[7] C. Moore, A. Rohan, “Dyadic Representation in Canadian Parliament,” April 2022
