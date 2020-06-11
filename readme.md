# COVID-19 classification data

Files [11.06.2020]:

* classify_20201106_abstractComplete.csv [records with abstracts]
* classify_20201106.csv [records with or without abstracts]

## Annotation 

First, we screened the retrieved publications whether they reported on SARS-CoV-2/COVID-19. If this was the case, we annotated the study design. If studies were of an epimiological study design, we annotated the country, when clearly reported.

We distinquish between epidemiological study designs, basic reserach and other. We consider reviews, commentaries and editorials not providing new data as 'non-original' (table x).

| Studytype1                            | Code | Group | Original |
|---------------------------------------|------|-------|----------|
| Case report                           | 1    | Epi   | Yes      |
| Case series                           | 2    | Epi   | Yes      |
| Case-control study                    | 3    | Epi   | Yes      |
| Cohort study                          | 4    | Epi   | Yes      |
| Cross-sectional study                 | 5    | Epi   | Yes      |
| Diagnostic study                      | 6    | Epi   | Yes      |
| Ecological study                      | 7    | Epi   | Yes      |
| Guidelines                            | 8    | Epi   | Yes      |
| Modelling study                       | 9    | Epi   | Yes      |
| Other                                 | 10   | Epi   | Yes      |
| Outbreak or surveillance report       | 11   | Epi   | Yes      |
| Qualitative study                     | 12   | Epi   | Yes      |
| Review                                | 13   | Epi   | No       |
| Trial                                 | 14   | Epi   | Yes      |
| Animal experiment                     | 21   | Basic | Yes      |
| In vitro experiment                   | 22   | Basic | Yes      |
| Biochemical/protein structure studies | 27   | Basic | Yes      |
| Sequencing and phylogenetics          | 23   | Basic | Yes      |
| Within-host modelling                 | 24   | Basic | Yes      |
| Basic research review                 | 25   | Basic | No       |
| Other                                 | 26   | Other | NA       |
| Comment/editorial/non-original        | 30   | Other | No       |

**Table x.** Classification of study designs, and the group and original status to which we assigned studies. Epi: epidemiological study designs; Basic: basic research study design; Other: not Epi nor Basic.

## Crowd-distributed screening and verification

### Screening, verification and resolution

All publications were screened by a first reviewer and verified by a second. Disagreement was resolved by a third reviewer. An online [annotation guide](https://ispmbern.github.io/covid-19/living-review/annotationguide.html) was available, and questions were discussed via email, google sheets, online meetings or direct messaging.

### Assignment of tasks

Assigned of tasks to the crowd members was coordinated centrally. Through an online tool, the crowd members performed their tasks. An example with source code of the screening tool can be found here: [Link](https://zika.ispm.unibe.ch/assets/data/pub/screening_demo/). 