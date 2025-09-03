# Meeting minutes of the project team

This document summarizes the meetings of the workstream

## 2024-07-24 - kick-off

### Agenda

-   Introductions
-   Discussions on problem statement and possible solutions
-   Ideas on how to go forward
-   Wrap up and immediate next steps

### Notes

-   Group met with context that reproducibility is poor in price statistics research and we should improve it. The group then decided how to tackle this problem and how to properly scope the objectives to make things achievable. Main challenges currently faced in the discipline included:
    -   Research is becoming increasingly empirical, hence we need processes to work with data and code to make the research more easily reproducible
    -   There are no agreed upon benchmark datasets *per se* in the discipline to test methods on
    -   The discipline will not own most of the datasets as most research is done on either confidential internal datasets owned by NSOs or on proprietary (purchased datasets). The open datasets that exist are not organized or cohesively documented/available.
    -   The reason **why** reproducibility is important is not as inherent/widely communicated as it could be, hence any attempts to solve the technical and processes aspects needs to include this aspect in the communication.
-   The group touched on goals to solve these aspects and on processes that can be set up to incentivize reproducibility, including by lowering the complexity and creating an easy 'on ramp' to making projects more reproducible (including by cataloging open datasets and showcasing how code can be made reproducible), coordinating with the two bi-annual conference to recommend reproducibility be part of the paper submission process, embedding metadata standards into the data available to make it easier and more standardized when various benchmark datasets are used to evaluate a specific method, etc.
-   The data catalogue for open datasets was seen as a major deliverable to the discipline, and one that needed to be phased. In other words we can set up a 'proof of concept' or interim catalogue in a simple way to demonstrate the use case, and later transition to a fuller and more comprehensive catalogue with more resources and infrastructure, potentially hosted by the UN Global Platform. Showcasing the interim solution and broadening the adoption to beyond just price statistics would help make this business case.
-   The outcome of the discussion resolved to target two main deliverables: developing the proof of concept data catalogue, and writing guidance (for instance in the form of a white paper) on how to make projects more reproducible. This target scope was later summarized [through our project charter](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/project-charter.md).

## 2025-01-28

### Agenda

-   Intro and discussion on timelines and scope. Confirm cadence of meetings
-   Quick discussion on how to track PM activity. We could use something like GitHub, the UN wiki, or some other option
-   Discussion on Objective A. We have two options ([.Stat suite](https://de-demo.siscc.org/vis?lc=en&df%5bds%5d=staging%3ASIS-CC-stable&df%5bid%5d=DSD_SCANNER_DATA%40DF_SEASONAL_PRODUCTS&df%5bag%5d=LU1&df%5bvs%5d=1.0&av=true&dq=..M.&lom=LASTNPERIODS&lo=36&to%5bTIME_PERIOD%5d=false&ly%5bcl%5d=TIME_PERIOD&ly%5brs%5d=MEASURE%2CUNIT&ly%5brw%5d=PRODUCT&vw=ov "https://de-demo.siscc.org/vis?lc=en&df%5bds%5d=staging%3ASIS-CC-stable&df%5bid%5d=DSD_SCANNER_DATA%40DF_SEASONAL_PRODUCTS&df%5bag%5d=LU1&df%5bvs%5d=1.0&av=true&dq=..M.&lom=LASTNPERIODS&lo=36&to%5bTIME_PERIOD%5d=false&ly%5bcl%5d=TIME_PERIOD&ly%5brs%5d=MEASURE%2CUNIT&ly%5brw%5d=PRODUCT&vw=ov") and [data contract catalogue](https://sergegoussev.github.io/data_contract_experiments/ "https://sergegoussev.github.io/data_contract_experiments/")) for interim data catalogue.
-   Discussion on Objective B. Can we adopt any best practices from [the Turning Way](https://book.the-turing-way.org/ "https://book.the-turing-way.org/") and their [template repo](https://github.com/the-turing-way/reproducible-project-template "https://github.com/the-turing-way/reproducible-project-template") for price statistics?
-   Roundtable

### Notes

-   Group discussed objectives for the 2025 CPI Expert Group meeting. It was decided to focus on an interim data catalogue and provide interim guidance at the conference, with the fuller guidance to be developed over the next year.
-   GitHub projects was agreed upon as the structure for PM activity
-   The draft data catalogue idea was given the green light to flush out further as our likely implementation of the interim version. Metadata standards should be implemented but it would be hard to use a platform where we don't own the dataset (such as dominik's data).
-   Guidelines for how to develop reproducible research through git was seen as a good way, with the idea that the guidance we would produce would (a) provide the target state to aim for and (b) summarize maturity levels ([similar to RAP maturity levels](https://nhsdigital.github.io/rap-community-of-practice/introduction_to_RAP/levels_of_RAP/)) that showcase how researchers can start easily and progress over time.

## 2025-02-11

### Agenda

-   Discussion on the [proposed project charter for the project](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/project-charter.md) (since merged into main)
-   Update on the 2 repositories for the project ([project repo](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/outline-project-structure-and-purpose/project-charter.md) and [interim data catalogue repo](https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue)) and [the mocked up project management approach](https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1)
-   Roundtable

### Notes

-   Team discussed scope for 2025 CPI EG presentation. The [project plan outlined two milestones](https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1), one on data catalogue and one on guidance will be the target. The project structure and use of the GitHub project was summarized.
-   The use of the two repos was discussed. The [reproducibility-project repo](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project) will host the guidance we develop in whatever format we decide (ideas shared including using quarto to [write reproducible papers](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project), or a [quarto static site](https://quarto.org/docs/websites/) if we will more tend towards creating guidance). [price-stats-data-catalogue](https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue) will host the interim open data catalogue.
-   Scope of the data contract was firmed up - we could aim to catalogue input datasets that are used to create some experimental indices and version the output datasets (that may be price indices or other artifacts) as part of the repository on github (such as by saving them in data folder and formatting them in [tidy data format](https://nhsdigital.github.io/rap-community-of-practice/implementing_RAP/workflow/tidy-data/)).
-   Use of tools like Zenodo was discussed and will be investigated to mint DOIs - [ticket #3](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/issues/3)

## 2025-02-25

### Agenda

-   Discussion on format for meeting minutes and how to review/approve the minutes each meeting.
-   How to track materials related to reproducibility but are just references to others' material (not the overall guidance we will provide).
-   What format is seen as the best way to deliver guidance on reproducibility? It is best to decide an applicable format and stick with it. Options include writing a paper, using a static site, or using the wiki

### Notes

-   The team agreed on keeping notes in this `meeting-minutes.md` file. The team also agreed to the process:
    -   The note taker would summarize the meeting and would draft a branch and prepare a Pull Request for the team to review the meeting minutes at the next meeting.
    -   At the start of the next meeting, the team would review the PR, would commit any changes/fixes needed. and [squash and commit the PR](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/about-merge-methods-on-github#squashing-your-merge-commits) into the `main` branch to approve the minutes.
-   The team agreed to track other materials in `other-open-materials.md` for now
-   The team discussed the means of how guidance will be provided at the end of the day as a lot of material could be included based on the goals in [Objective B of our project](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/project-charter.md#expected-outcomes-in-a-little-more-detail "https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/project-charter.md#expected-outcomes-in-a-little-more-detail"). Some possible options:
    -   a paper (similar to say [the FAIR paper on software](https://www.nature.com/articles/sdata201618 "https://www.nature.com/articles/sdata201618") to be presented at say 2026 Ottawa Group conference) as the main document for guidance and other materials as supporting (like the catalogue). This could use the [quarto manuscript format](https://quarto.org/docs/manuscripts/ "https://quarto.org/docs/manuscripts/") for example.
    -   a static site (again say a quarto one [like this one](https://escap-sd.github.io/ESCAP_RAP_class/docs/ "https://escap-sd.github.io/ESCAP_RAP_class/docs/")) as the main means of sharing guidance, but also a short paper for the 2026 OG conference as an offline guide
    -   a set of [wiki pages similar to other content](https://unstats.un.org/wiki/display/GWGSD/ "https://unstats.un.org/wiki/display/GWGSD/") made by the Task Team
-   The team agreed that a static site (the quarto option) is likely the most appropriate as the site can be expanded and maintained as appropriate, a presentation with a link to the site could be provided at conferences.
-   The team discussed planning for the next 1.5 months. The [project roadmap outlines the target timelines](https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1). As several issues remain unassigned, the team are encouraged to sign up based on bandwidth.
-   Roundtable discussion included:
    -   Update on Zenodo - which is an option for uploading and citing data (detail in [issue 3](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/issues/3#issuecomment-2681854343)). There isn't a process yet identified for datasets that are not owned by the community and where the owner does not upload it to a repository that mints a DOI.
    -   Update on citing data in PriceIndices R package as it has a DOI. Ability to extract the data without installing the package has to be confirmed.

## 2025-03-11

### Agenda

-   Review mock up quarto site for the project, as well as contributing and code of conduct
-   Review ongoing work prior to the 2025 CPI Expert Group
-   Roundtable

### Notes

-   Team discussed [the mock up site](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/) structure with a home and two main sections, one on how to make your projects reproducible by publishing your code and on using open data.
-   The team also discussed the basic [contributing guide](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/CONTRIBUTING.md "https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/CONTRIBUTING.md") and [code of conduct](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/CODE_OF_CONDUCT.md "https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/blob/main/CODE_OF_CONDUCT.md").
-   The deliverables to be presented at the 2025 CPI Expert Group were discussed as per the [view in the project roadmap](https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1?layout=roadmap).
-   An approach on how to import data from a package was discussed. For instance, how should researchers use data from an R package (such as the PriceIndices package, which has datasets we would like to make list in the interim catalogue) and they wanted to import the data and use it in Python? The team discussed on a phased approach: guidance on how to download the dataset and use it in python from the R ecosystem will be proposed; a longer term approach could be to work with dataset owners to get them to publish it on a repository like Zenodo.
-   Support by the UN Global Platform team for the project was also discussed

## 2025-03-25

### Agenda

-   Review of skeleton data catalogue
-   Review of the changes to the project site, specifically how to cite code and how to cite data sections
-   Review roadmap and discussion of topics left to finish in this phase of the project

### Notes

-   The team discussed the [skeleton of the proof of concept data catalogue](https://un-task-team-for-scanner-data.github.io/price-stats-data-catalogue/). The technical process to register new datasets is basically to (1) draft a new `yaml` file in the [`datasets/`](https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue/tree/main/datasets) folder using the [`datacontract.cli`](https://cli.datacontract.com/) specifications, and then (2) when the PR is accepted (after relevant review) and merged with the `main` branch, the runner will re-render the catalogue and the dataset will show up.
-   The team discussed next steps. The dataset in [#6](https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue/issues/6) is still the third we'd want for presentation at CPI EG.
-   There is a need to differentiate open versus proprietary but popular datasets. Open datasets will be the focus for now with potential for expansion after the conference.
-   The team discussed [how to cite datasets](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/datasets-guidance/how-to-cite.html) and [how to cite code](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/reproducibility-guidance/citing-code.html) topics, and based on the example by the [recent Baker et al (2022) FAIR principles for software paper](https://www.nature.com/articles/s41597-022-01710-x#data-availability), we decided to go with a nuanced recommendation for now:
    -   if data or code that a research uses exists should be included in the bibliography
    -   data or code that is created as part of the paper should be (ideally published to something that mints a DOI) but the links to the dataset or code are included at the end of the paper under "Data availability" and "Code availability" headers.
    -   The idea of topics to discuss after the conference was also brought up - the process of creating synthetic datasets.
-   To support researchers to structure their code, the team also discussed and endorsed recommending a [template RAP](https://github.com/UN-Task-Team-for-Scanner-Data/price-index-pipeline).

## 2025-04-08

### Agenda

-   Review of [mock-up guidance on the project cite](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/ "https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/") and the [template RAP for price index methods](https://github.com/UN-Task-Team-for-Scanner-Data/price-index-pipeline "https://github.com/UN-Task-Team-for-Scanner-Data/price-index-pipeline").
-   Discussion of the [contributing guide](https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue/pull/10 "https://github.com/UN-Task-Team-for-Scanner-Data/price-stats-data-catalogue/pull/10") for the catalogue
-   [Review roadmap](https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1 "https://github.com/orgs/UN-Task-Team-for-Scanner-Data/projects/1/views/1") and discussion of topics left to finish in this phase of the project

### Notes

-   The team discussed the flushed out project site with the initial guidance that could be provided during the upcoming CPI Expert Group conference and the mock-up price index RAP.
-   The group particularly focused on the contributing guide for the catalogue and how to deal with various scenarios. Particularly:
    -   How should we assess and decide what is approved to be registered to the catalogue? The team will for now adopt a group consensus approach of approving new datasets following a discussion during one of the regular team meetings. The approach could be flushed out in more detail once there are several additional datasets to register.
    -   What is the scope for datasets registered to the catalogue? The team agreed that any dataset related to price statistics, whether consumer, producer, or otherwise, could be included - as the methods to be applied are similar, even if datasets and applications are slightly different. For more nuanced cases (such as elementary aggregate data), the justification to include may depend on value for researchers.
-   Next steps for the group is to prepare for the upcoming CPI Expert Group conference by reviewing the mocked-up content and preparing the presentation material.

## 2025-04-22

### Agenda

-   Adding an [“about the team” section in the about page](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/about.html) to showcase project members/contributors, [similar to the Turing way](https://book.the-turing-way.org/afterword/contributors-record).
-   Review material to be presented during the CPI Expert Group
-   Discussion on how material related to academic classes in price statistics can be positioned to be reproducible

### Notes

-   The team discussed and endorsed the about team page, similar to how [the Turing way records contributors](https://book.the-turing-way.org/afterword/contributors-record). Action item for the team is either to contribute to the page directly via PR (see CONTRIBUTING) or coordinate offline.
-   How this guide and the interim catalogue will be presented next week was discussed and approved
-   For academic material, the group discussed possible guidance. Initial thoughts of the group was that while code can be in GitHub and follow compendium type structure, datasets do not need to be registered if they are small training datasets and could just be version controlled in GitHub directly. The policies of the university should take precedence.
-   The group agreed to switch to a 3 week cadence with the next meeting three weeks after the conference.

## 2025-05-20

### Agenda

-   Discuss OKR based slight restructure of the charter to clarify the direction.
-   Discuss what to recommend as guidance in the call out email when the Ottawa Group organizers do a call for papers
-   Discuss backlog of items to prioritize work for the year (did not finish)

### Notes

-   The team discussed and approved the proposed [OKR based](https://www.whatmatters.com/faqs/okr-meaning-definition-example) restructure of the project charter. Key points included how to include administrative activities that aim to disseminate knowledge about the project/our guidance. Final charter and structured milestones can be mocked up and presented at the subsequent meeting.
-   The team discussed how training (provided by workstream 3) could support the project. A notable example was RAP principles, which can be taught in a general way and options to apply them to either research or production could be given at the end. A process flow may also be applicable to support individuals knowing how to open their projects.
-   The team discussed the difference between a researcher developing a new method (in which case open data is best) or a researcher is applying a tried method on their internal data (in which case use of proprietary data is absolutely fine).
-   Team to add PR directly or email Serge to add their contact info to the [Project team members](https://un-task-team-for-scanner-data.github.io/reproducibility-project/docs/about.html#project-team-members) section.

## 2025-06-10

### Agenda

-   Updated project charter and github project.
-   Pull request on other open examples.
-   Discuss possible style changes to the site

### Notes

-   The team discussed and agreed upon an updated project direction for the year. Specifically, the overall vision has been clarified with the goal of instilling of reproducibility practices in the price statistics discipline. Furthermore, a project management appraoch using objective and key results (KRs) that the team aims to achieve per year towards the vision was also set up. Note that the specific KRs may need to be tweaked and will be discussed at subsequent meetings.
-   A [PR with other examples was discussed](https://github.com/UN-Task-Team-for-Scanner-Data/reproducibility-project/pull/50). The papers section was discussed specifically - idea is to show papers with 'packaged' code as there could be many notable repos mentioned in papers and it could be challenging to be comprehensive. For really notable ones, we could encourage packaging. The section will be further refined before being pushed.
-   Style changes were discussed for the site. We could test using an `<iframe>` to embed the catalogue into the site. We can also organize how to guides separately from initial introductory content. Site will be mocked up with proposed changes at a later meeting.

## 2025-07-22

### Agenda

-   Review proposed OKR changes to structure goals for the year
-   Discussion on "Open material for price statistics" guide
-   Discussion of an example that could serve as a proprietary to open guide

### Notes

-   Team reviewed and agreed to proposed changes to the OKRs with 3 KRs for one objective:
    -   Key challenge of how to measure was discussed. For growth for instance (KR3), its hard to measure as the denominator  (if we use a ratio) is tough to agree to (not all conference presentations are research materials). Aiming for a specific number of papers may be easier to estimate.
    -   Next steps include the discussions on how to measure each Key Result.
-   Team discussed the *Overview on open material for price statistics* page:
    -   Article is made up of 3 sections: generic (software for official statistics), software specifically for price statistics (needs to be on hosted on CRAN etc.), and older/inactive projects. Actual packages are included, i.e. to make the list, it needs to be installable (not code used to produce analysis).
    -   This should be a living document - would fall under longer term task team maintenance.
    -   Infeasible to keep package owners notified that we included their package on the list. CRAN and other repos already let owners know who uses their packages.
    -   Caveats around using packages, esp. old/outdated ones on the page (e.g. with a disclaimer) makes the list useful.
    -   The list is intended to advocate best practice of making software citable to help increase awareness
    -   Team to review draft PR by end of week
-   Team discussed the [GEKS decomposition code](https://github.com/ONSdigital/mean-splice-decomposition) that was published alongside [Liu (2025) Practical Decompositions of mean-spliced on published indices](https://unece.org/sites/default/files/2025-04/geneva%20paper.pdf). The paper was initially written with  internal data and internal code in mind but converted to use open data and published its code alongside the paper. Thus, the example could use as a good use case as guidance (say as a 'call to action'). Group agreed on the value and will look to return to the article to decide on best approach.  
