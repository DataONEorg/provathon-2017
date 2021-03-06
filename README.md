# [Prov-a-thon: Practical Tools for Reproducible Science](https://dataoneorg.github.io/provathon-2017/)

<div class="logos" style="float: center">
<img style="width: 200px; margin: 20px" src="https://www.dataone.org/sites/default/files/d1-logo-v3_aligned_left_0_0.jpeg">
<img style="width: 300px; margin: 20px" src="images/wholetale-logo.png">
<img style="width: 170px; margin: 20px" src="https://arcticdata.io/wp-content/themes/aurora/library/images/logo_.png">
</div>

Provenance information enables datasets that are linked 
to the software and analysis code that created them and used them in research.
It allows users to trace new and ongoing uses of data, and provides rich information about 
the origins of data that ultimaltely supports reproducible research workflows. 
*Prov-a-thon* is a two-day workshop designed to advance practical approaches to
incorporating provenance information into tools and workflows that are useful in 
earth, environmental, and archeological research domains.

- Dates: Aug 31 - Sep 2 (morning), 2017
- Venue: Tamaya Resort, New Mexico
- Sponsors
    - [DataONE](https://dataone.org)
    - [Whole Tale](https://wholetale.org)
    - [Arctic Data Center](https://arcticdata.io)
    - Community Dynamics Project
    

## Goals:
- Learn about Whole Tale/DataONE/other provenance tools and reproducibility
- Add provenance data for rich datasets into DataONE
- Build interest amongst data creators/submitters about adding provenance data
- Organize efforts about reproducibility training and evangelization in archaeology and environmental science
- Stimulate coordination of the development/use of provenance and reproducibility tools

## Background reading

Lowndes, J. S. S., B. D. Best, C. Scarborough, J. C. Afflerbach, M. R. Frazier, C. C. O’Hara, N. Jiang, and B. S. Halpern. 2017. [Our path to better science in less time using open data science tools](https://doi.org/10.1038/s41559-017-0160). Nature Ecology & Evolution 1:0160.

Marwick, B. 2017. [Computational Reproducibility in Archaeological Research: Basic Principles and a Case Study of Their Implementation.](https://doi.org/10.1007/s10816-015-9272-9) Journal of Archaeological Method and Theory 24:424–450.


McPhillips, T., Song, T., Kolisnik, T., Aulenbach, S., Belhajjame, K., Bocinsky, R.K., Cao, Y., Cheney, J., Chirigati, F., Dey, S. and Freire, J., 2015. [YesWorkflow: A User-Oriented, Language-Independent Tool for Recovering Workflow Information from Scripts.](http://www.ijdc.net/index.php/ijdc/article/download/10.1.298/401) International Journal of Digital Curation, 10(1), pp.298-313.

Cao, Y., Jones, C., Cuevas-Vicenttín, V., Jones, M.B., Ludäscher, B., McPhillips, T., Missier, P., Schwalm, C., Slaughter, P., Vieglais,
D. and Walker, L., 2016,June.
[DataONE: A Data Federation with Provenance Support](https://link.springer.com/chapter/10.1007/978-3-319-40593-3_28).
[(extended preprint)](https://github.com/DataONEorg/provweek2016-demo/raw/master/dataone-demo-latex-version/dataone-prov-demo-long.pdf)
In International Provenance and Annotation Workshop
(pp. 230-234). Springer.

Ludäscher B, Chard K, Gaffney N, Jones M, Nabrzyski J, Stodden V, Turk
M,
[Capturing the "Whole Tale" of Computational Research: Reproducibility in Computing Environments](https://arxiv.org/abs/1610.09958),
Science Gateways Workshop, San Diego, 2016.




## Resources links

- [Provenance editing demo](https://dataoneorg.github.io/provathon-2017/prov-editing/prov-editing.html)
- [Tools for uploading Provenance in R](https://nceas.github.io/oss-lessons/publishing-data/upload-data.html)
- R Recordr package
- [Whole Tale dashboard](https://dashboard-dev.wholetale.org)

- YesWorkflow
    - [YW prototype & walk-through tutorial (start here)](https://github.com/yesworkflow-org/yw-prototypes)
    - [Try-YW (play with a limited YW version in the browser)](http://try.yesworkflow.org)
    - [YW production system (under development)](https://github.com/yesworkflow-org/yw)

- [**Day 1 notes**](20170831_notes.md)
- [**Day 2 notes**](20170901_notes.md)
- [**Day 3 notes**](20170902_notes.md)


## Participants

- [Jamie Afflerbach](https://github.com/jafflerbach)
- [Kyle Bocinsky](https://github.com/bocinsky)
- [Carl Boettiger](https://github.com/cboettig)
- [Emery Boose](https://github.com/erboose)
- [Amber Budden](https://github.com/aebudden)
- Peter Darch
- [Matt Harris](https://github.com/mrecos)
- Linh Hoang
- Xiaoliang Jiang
- [Chris Jones](https://github.com/csjx)
- [Matt Jones](https://github.com/mbjones)
- [Eric Kansa](https://github.com/ekansa)
- [Keith Kintigh](https://github.com/kintigh)
- [Josh London](https://github.com/jmlondon)
- [Julie Lowndes](https://github.com/jules32)
- [Bertram Ludäscher](https://github.com/ludaesch)
- Hui Lyu
- [Ben Marwick](https://github.com/benmarwick)
- [Paulina Przystupa](https://github.com/ciszka)
- Peter Slaughter
- Pratik Srivastava
- [Dave Vieglais](https://github.com/datadavev)

## Agenda

### Day 1: Thursday, August 31, 2017

**0715 - 0800 Breakfast**

**0800 - 1000 Welcome and Overviews (Room: Tamaya ABC)**

- 0800 - 0825 Overview of DataONE (Bill Michener, DataONE)

- 0825 - 0845 Overview of Provenance  (Bertram Ludäscher, UIUC)

    -   Different notions and uses of provenance,  reproducibility 
    
- 0845 - 0945 Overview of the Status of Provenance Tools (Matt Jones, NCEAS)

    -   Review of provenance-related tools & systems (ProvONE, Prov in R + Matlab, YW, Prov Entry UI, Whole Tale)

    -   Demo of the DataONE provenance display system:

        -   Search.dataone.org: [*https://search.dataone.org/\#view/urn:uuid:3249ada0-afe3-4dd6-875e-0f7928a4c171*](https://search.dataone.org/#view/urn:uuid:3249ada0-afe3-4dd6-875e-0f7928a4c171)

    -   Demo of the prov entry UI

- 0945 - 1000 Goals of Prov-a-thon (Dave Vieglais, DataONE)
 

**1000 - 1030 Break**
 

**1030 - 1200 Introductions and Lightning Talks (Room: Eagle AB)**

- 1030 - 1050 Around the room introductions (Amber Budden, DataONE)

- 1050 - 1150 Lightning talks: Provenance and Reproducible Workflows (Kyle Bocinsky, Whole Tale)

    -   *Kyle Bocinsky*, *Ben Marwick*, Paulina Przystupa, *Matt Harris*, *Eric Kansa*, Carl Boettiger, *Emory Boose*, *Josh London*, *Jamie Afflerbach*, *Julie Lowndes*, *Peter Darch* (*confirmed*)
    
- 1150 - 1200 Agenda review (Matt Jones)

**1200 - 1300 Lunch**

- poster session featuring summer internships related to provenance (DataONE, Whole-Tale)
    - Xiaoliang Jiang, Linh Hoang, Hui Lyu, Pratik Srivastava

**1300 - 1445 Provenance Tools I (Room: Eagle AB)**

- 1300 - 1400  Intro to the DataONE R provenance tools (Matt)

    -   R libraries: `dataone`, `datapack`, `recordr`

- 1400 - 1445 Intro to YesWorkflow (Bertram)

    -   YW modeling exercise (Bertram)

**1445 - 1515 Break**

**1515 - 1700 Provenance Tools II (Room: Eagle AB)**

- 1515 - 1700 Intro to the Whole Tale web tool (Matt & Bertram)

    -   Hands on with WT tool, including importing data from DataONE
    
### Day 2: Friday, September 1, 2017

**0715 - 0800 Breakfast**

**0800 - 1000 Breakout Groups: Archaeology (Room: Eagle A), Environmental Science (Room: Eagle B)**

-   Environmental Science (Jones)

    -   Breakout agenda planning

    -   Hands on provenance metadata writing activities, troubleshooting, usability

    -   Identify future development directions (DataONE/YW/WT/rrtools/others?)

    -   Discussion of barriers to reproducibility in environmental sciences

    -   Planning for advocacy for reproducible research approaches in environmental science

-   Archaeology (Bocinsky)

    -   Hands-on with WT/rrtools/opencontext/dataone — Building tales

    -   Discussion of barriers to reproducibility in archaeology (generalizable to other disciplines; ideas below)

        -   Lack of training in computational methods/reproducibility

        -   Persistence of data hoarding/siloing

        -   Data sensitivity & archaeological looting

        -   Few “sticks” from journals/funding agencies/professional societies

        -   Few “carrots” from journals/peers/tenure committees/funding agencies
        
-   Archaeology Goals (Bocinsky):

    -   Tool assessment/usability feedback (YW/WT)

    -   Identify future development directions (DataONE/YW/WT/rrtools/others?)

    -   Create provenance records (DataONE)

    -   Identify ways to promote reproducibility in the communities

    -   Identify next steps/plans for further collaboration

    -   [**How To Do Archaeological Science Using R**](https://benmarwick.github.io/How-To-Do-Archaeological-Science-Using-R/) book status update (Ben/Matt/Paulina/Kyle)

    -   Intro and feedback on *rrtools* package (Ben)

    -   Plan further advocacy for reproducibility in Archaeology (ideas below)

        -   SAA committees (publications/curriculum)

        -   SAA Events/forums/workshops?

        -   Collaborations with open journals?

            -   White paper on data access and reproducibility for arch. journals?

**1000 - 1030 Break**

**1030 - 1200 Continued Breakout Sessions**

**1200 - 1300 Lunch**

**1300 - 1445 Continued Breakout Sessions**

**1445 - 1515 Break**

**1515 - 1700 Plenary: Reproducibility and Provenance for Science**

-   Report back from breakout groups (10 minutes each)

-   Moderated Discussion (Kyle & Matt):

    -   Evangelism and advocacy for reproducible research in general

    -   The tool landscape supporting reproducible research

-   Next steps

    -   Roadmap for DataONE and Whole Tale tool development

        -   How can the working group(s) help?

    -   How to get buy-in from data contributors at the user level

    -   How to build a community pulling towards the same reproducible research goals

    -   What do we collectively want to do next

-   Conclusion, establish report back mechanism 

### Day 3: Saturday, September 2, 2017

**0730 - 0800 Breakfast**

**0800 - 1100 Review,  Reflections, Follow-up**

**1100 - 1200 Lunch (boxes)**



