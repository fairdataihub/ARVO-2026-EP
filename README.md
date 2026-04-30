[![CC BY 4.0][cc-by-shield]][cc-by]


[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

# Repository of the ARVO 2026 Annual Meeting Poster on the Envision Portal

## About

This repository contains the file and information associated with our poster presentation at The Association for Research in Vision and Ophthalmology (ARVO) Annual Meeting 2026 (May 3-7, Denver, CO). Our poster is titled "Toward the Envision Portal: Designing a FAIR and AI-Ready Framework for Ophthalmic Imaging Sharing and Discovery".

**Abstract** 

_Purpose_

Ophthalmic imaging datasets generated in research studies, such as Optical coherence tomography (OCT) images and fundus photographs, are a valuable resource for advancing discovery, particularly through artificial intelligence (AI) models. They are, however, not consistently shared. Even when shared, their reuse is hindered by fragmented sharing that limits findability and by inconsistent structure that reduces interpretability. This work presents the preliminary investigation underlying the design of the Envision Portal, an open-source platform intended to support the sharing and discovery of FAIR (Findable, Accessible, Interoperable, Reusable) and AI-ready ophthalmic imaging datasets.

_Methods_

To define the requirements for an effective AI-ready ophthalmic imaging sharing and discovery platform, we evaluated existing examples of FAIR data practices and ophthalmic imaging standards, including ongoing large-scale NIH initiatives focused on data standardization and AI-readiness, such as Bridge2AI and SPARC. We also examined design principles and operational models from successful data-sharing platforms, including OpenNeuro and SPARC.science, to identify transferable approaches in metadata organization, validation, user workflows, and system architecture. These insights were synthesized into the preliminary technical framework for the Envision Portal.

_Results_

Our evaluation identified core requirements for the Envision Portal. A unified dataset standard is necessary for consistency. Drawing from the impact of BIDS in OpenNeuro, we identified the Bridge2AI Clinical Dataset Structure (CDS) with DICOM for image and OMOP clinical data as an effective model. Automated user-friendly tools are required to implement these standards and reduce curation burden while ensuring compliance. FAIR features such as DOIs, structured metadata, and schema.org exposure, as used in OpenNeuro and SPARC.science, are also essential for enabling indexing and AI-ready reuse. These findings informed the initial technical blueprint for the Envision Portal. 

_Conclusions_

Our findings define the core framework required to support interoperable, AI-ready ophthalmic imaging datasets. These specifications provide the structural foundation for implementing the Envision Portal, currently under development and expected to launch in early 2026.




## Schedule

| Type            | Date & Time             | Authors                          | Session / Location                                              | Details |
| --------------- | -----------------|--------------------------------- |------------------------------------------------------ |------------------- |
| Course          |  Wednesday, May 6, 2026, 10:15 am – 12:00 pm MT | Bhavesh Patel (presenter) | Session 3: Fundamentals of model training and federated learning  |[ARVO website](https://www.arvo.org/annual-meeting) |


## Material

- [ARVO-2026-Envision-Portal-poster.pdf](ARVO-2026-Envision-Portal-poster.pdf): pdf file of the poster.

## Resources

We list here major resources relevant to our poster.

| Description                                         | Link                                                              |
| --------------------------------------------------  | ----------------------------------------------------------------- |
| Envision Portal                       | https://envisionportal.org |
| Clinical Dataset Structure (CDS) specification                           | https://cds-specification.readthedocs.io |
| Ophthalmic dataset classifier                           | https://github.com/EyeACT/envision-classifier |
| Ophthalmic dataset discovery pipeline                           | https://github.com/EyeACT/envision-discovery |
| FAIR Principles                        | https://doi.org/10.1038/sdata.2016.18 |

## License
The material in this repository is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

## Contact us
For submitting feedback or getting in touch, email bpatel@calmi2.org.

