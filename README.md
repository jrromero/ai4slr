This page contains supplementary material of the paper 
> de la Torre-López, J., Ramírez, A. & Romero, J.R. Artificial intelligence to automate the systematic review of scientific literature. Computing 105, 2171–2194 (2023). https://doi.org/10.1007/s00607-023-01181-x

# Abstract
Artificial intelligence (AI) has acquired notorious relevance in modern computing as it effectively solves complex tasks traditionally done by humans. AI provides methods to represent and infer knowledge, efficiently manipulate texts and learn from vast amount of data. These characteristics are applicable in many activities that human find laborious or repetitive, as is the case of the analysis of scientific literature. Manually preparing and writing a systematic literature review (SLR) takes considerable time and effort, since it requires planning a strategy, conducting the literature search and analysis, and reporting the findings. Depending on the area under study, the number of papers retrieved can be of hundreds or thousands, meaning that filtering those relevant ones and extracting the key information becomes a costly and error-prone process. However, some of the involved tasks are repetitive and, therefore, subject to automation by means of AI. In this paper, we present a survey of AI techniques proposed in the last 15 years to help researchers conduct systematic analyses of scientific literature. We describe the tasks currently supported, the types of algorithms applied and available tools proposed in 34 primary studies. Our survey also provides a historical perspective of the evolution of the field and the role that humans can play in an increasingly automated SLR process.

# Additional material

## Literature search
The results of the search and filtering process are provided in the next document:

List of returned papers per database, candidate papers, and primary studies ([XLSX](http://www.uco.es/grupos/kdis/ai4slr/survey/KDIS_AI4SLR_SearchResults.xlsx), 1.28 MB)

The second document defines the 'data extraction form' used for the analysis of primary studies, and includes summary statistics:

Data extraction form and summary statistics ([XLSX](http://www.uco.es/grupos/kdis/ai4slr/survey/KDIS_AI4SLR_SummaryStatistics.xlsx), 52 KB)

# Analysis of tools

From the list of SLR automation tools available in the [SR Toolbox website](http://systematicreviewtools.com/), we analyse those specifically applying Artificial Intelligence. For each tool, we collect information about its purpose (i.e., SLR tasks it supports) and applied techniques from their official websites. The information is summarised in the table below. The second column of the table specifies the SLR task to which AI is applied, even though the tool might automate other tasks without AI as well. The specific AI techniques are detailed when such information is available from the documentation, which is not a frequent case.

| Tool        | SLR task                          | AI techniques                                     | Website                                                   |
|-------------|-----------------------------------|---------------------------------------------------|-----------------------------------------------------------|
| 2Dsearch    | Automated search                  | Text mining, machine learning, ontologies         | [https://www.2dsearch.com/](https://www.2dsearch.com/)    |
| Abstrackr   | Paper selection                   | Active learning (SVM)                             | [http://abstrackr.cebm.brown.edu/](http://abstrackr.cebm.brown.edu/) |
| Alvis       | Automated search                  | Text mining, ontologies                           | [http://bibliome.jouy.inra.fr/demo/food/alvisir/webapi/search](http://bibliome.jouy.inra.fr/demo/food/alvisir/webapi/search) |
| ASReview    | Paper selection                   | Active learning (NB, RF, SVM, LR, ANN) and deep learning (LSTM) | [https://asreview.nl/](https://asreview.nl/) |
| BeCAS       | Data extraction                   | Text mining                                       | [https://bioinformatics.ua.pt/becas/](https://bioinformatics.ua.pt/becas/) |
| BEST        | Automated search and data extraction | Text mining                                     | [http://best.korea.ac.kr/](http://best.korea.ac.kr/)      |
| BioReader   | Paper selection                   | Text mining                                       | [https://services.healthtech.dtu.dk/service.php?BioReader-1.2](https://services.healthtech.dtu.dk/service.php?BioReader-1.2) |
| CLAMP       | Data extraction                   | NLP                                               | [https://clamp.uth.edu/](https://clamp.uth.edu/)          |
| Colandr     | Automated search, paper selection and data extraction | NLP, machine learning and text mining | [https://www.colandrapp.com/signin](https://www.colandrapp.com/signin) |
| cTALES      | Data extraction                   | NLP, text mining                                  | [http://ctakes.apache.org/](http://ctakes.apache.org/) |
| CoCTER      | Paper selection                   | Machine learning, NLP, text mining                | [https://www.icf-docter.com/](https://www.icf-docter.com/) |
| Dr. Evidence | Automated search                 | Machine learning                                  | [https://www.drevidence.com/](https://www.drevidence.com/) |
| EPPI-Reviewer | Paper selection                 | Text mining                                       | [https://eppi.ioe.ac.uk/CMS/Default.aspx?alias=eppi.ioe.ac.uk/cms/er4](https://eppi.ioe.ac.uk/CMS/Default.aspx?alias=eppi.ioe.ac.uk/cms/er4) |
| EvidenceSET | Data extraction                  | Visual text mining                               | [http://evidenceset.com.br/](http://evidenceset.com.br/) |
| FASTREAD    | Paper selection                   | Active learning (SVM)                             | [https://github.com/fastread/src](https://github.com/fastread/src) |
| HelioBLAST  | Automated search                  | Text mining                                       | [https://helioblast.heliotext.com/](https://helioblast.heliotext.com/) |
| JSTOR       | Automated search                  | Text mining                                       | [https://www.jstor.org/](https://www.jstor.org/) |
| LitSuggest  | Automated search                  | Machine learning                                  | [https://www.ncbi.nlm.nih.gov/research/litsuggest/](https://www.ncbi.nlm.nih.gov/research/litsuggest/) |
| MeSH        | Automated search                  | Text mining                                       | [https://meshb.nlm.nih.gov/MeSHonDemand](https://meshb.nlm.nih.gov/MeSHonDemand) |
| MetaMap     | Data extraction                   | NLP                                               | [https://lhncbc.nlm.nih.gov/ii/tools/MetaMap.html](https://lhncbc.nlm.nih.gov/ii/tools/MetaMap.html) |
| PICO Portal | Paper selection, data extraction  | Machine learning, NLP                             | [https://picoportal.org/](https://picoportal.org/) |
| Quertle     | Automated search                  | Text mining                                       | [https://www.qinsight.info/](https://www.qinsight.info/) |
| RAx         | Automated search, paper selection, data extraction | N/A                   | [https://raxter.io/](https://raxter.io/) |
| Rayyan      | Paper selection, data extraction  | Machine learning, NLP                             | [https://www.rayyan.ai/](https://www.rayyan.ai/) |
| Research Screener | Paper selection            | Deep learning, NLP                                | [https://researchscreener.com/](https://researchscreener.com/) |
| RobotAnalyst | Paper selection                | Machine learning, text mining                     | [http://nactem.ac.uk/robotanalyst/](http://nactem.ac.uk/robotanalyst/) |
| RobotReviewer and RobotSearch | Automated search, paper selection | Machine learning | [https://vortext.systems/robotreviewer](https://vortext.systems/robotreviewer) |
| SLR.qub     | Automated search                  | Visual text mining                               | [https://github.com/gmergel/SLR.qub](https://github.com/gmergel/SLR.qub) |
| SWIFT: ActiveScreener and Review | Paper selection | Active learning, text mining, topic modelling | [https://www.sciome.com/swift-activescreener/](https://www.sciome.com/swift-activescreener/) |
| SyRF        | Paper selection                   | Machine learning                                 | [https://syrf.org.uk/](https://syrf.org.uk/) |
| Sysrev      | N/A                                | Machine learning, ontologies, visual text mining | [https://sysrev.com/](https://sysrev.com/) |
| Systematic Review Assistant | Quality assessment | Machine learning, text mining                  | [http://www.datamining.org.uk/sysreview.html](http://www.datamining.org.uk/sysreview.html) |

Acronyms: ANN=Artificial Neural Network, LR=Logistic Regression, LSTM=Long-Short Term Memory, NB=Naive Bayes, NLP=Natural Language Processing, RF=Random Forest, SVM=Support Vector Machine. N/A stands for non available or not applicable.

As can be seen, most of the tools are focused on three tasks: automated search, paper selection and data extraction. For automated search, existing tools enhance the capabilities of scientific search engines (Scopus, PubMed, etc.) with text mining to retrieve more specialised results. Some of them are general in scope, such as 2Dsearch and JSTOR, whereas others are domain-specific tools like Alvis (microbiology) or BEST (biomedicine). Regarding paper selection, most of the tools use ML, sometimes combined with text mining and NLP. In this case, the tools can be applied to any domain, and make use of the results of automated searches provided by the user. Abstrackr is one of the most popular tools in this task considering its appearance in several publications, but a recent project called ASReview offers the widest selection of algorithms. Tools for data extraction are far less abundant, and they all are specialised in a scientific discipline: BeCAS (biomedicine), CLAMP (health), cTALES and MetaMap (medicine) and EvidenceSET (software engineering). Here, NLP is the predominant technology to process pieces of scientific manuscripts. Finally, three tools---namely, PICO Portal, RAx and Rayyan---can be viewed as a kind of reference manager with AI capabilities, supporting the three tasks. However, their documentation does not clarify as to what extent AI is applied in all of them.

From the aforementioned list of tools, Abstrackr, a tool for paper selection has been extensively evaluated by independent researchers. A first study seeks to find relevant works for four ongoing SLRs carried out as part of health research projects [1]. More than 70,000 papers constitute the candidate papers retrieved by the searchers. The evaluation consists in comparing how many of the papers selected by the humans were predicted as relevant by Abstrackr, thus measuring the percentage of papers that would not need to be manually revised for inclusion. The authors conclude that the reliability of the tool and the time saved depend on the specific project. Since some relevant papers could be missed, they suggest that Abstrackr can be used as an extra reviewer. Three additional evaluations of Abstrackr have been carried out in 2020, showing a great interest in its practical use. Two studies [2,3] analyse the benefits of Abstrackr to assist in two different types of reviews: systematic reviews, for which two researchers independently scrutinise candidate papers; and "rapid" reviews, which are conducted by one researcher only. The authors analyse how Abstrackr behaves under these scenarios in terms of proportion of studies missed, workload savings and estimated time savings. Each paper considers a different collection of candidate papers related to 11 and 16 SLRs, respectively. Finally, Tsou et al. [4] also perform a comparative study to evaluate the use of two tools: Abstrackr and EPPI-Reviewer. The authors compare the results provided by each tool over the same set of candidate papers belonging to nine evidence-based medical reports. They conclude that both tools perform well on the paper selection task, although human intervention during the screening phase is still needed.

# References
[1] A. Gates, C. Johnson, L. Harting. Technology-assisted title and abstract screening for systematic reviews: A retrospective evaluation of the Abstrackr machine learning tool, 7(1). 2018.

[2] A. Gates, M. Gates, D. DaRosa, S.A. Elliott, J. Pillay, S. Rahman, B. Vandermeer, L. Hartling. Decoding semi-automated title-abstract screening: findings from a convenience sample of reviews. Systematic Reviews, 9(1):272. 2020.

[3] A. Gates, M. Gates, M. Sebastianski, S. Guitard, S.A. Elliott, L. Hartling. The semi-automation of title and abstract screening: A retrospective exploration of ways to leverage Abstrackr’s relevance predictions in systematic and rapid reviews. BMC Medical Research Methodology, 20(1):139, 2020.

[4] A.Y. Tsou, J.R. Treadwell, E. Erinoff, K. Schoelles. Machine learning for screening prioritization in systematic reviews: Comparative performance of Abstrackr and EPPI-Reviewer. Systematic Reviews, 9(1):73. 2020.
