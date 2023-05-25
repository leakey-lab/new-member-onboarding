# Documenting Data Files

Providing detailed information about your data or code are essential to making it findable and reusable, both for you and collaborators in the future. Effective documentation includes both study-level and data-level information.

## Study-Level Documentation
- Research Design
- Context for data collection
- Scope of samples and populations
- Data collection methods
- Quality assurance procedures
- Data transformation protocols

## Data-Level Documentation
- Contents of data files
- Variables, labels, and types
- Values, measures, and units
- Encoding/interpretation methods
- Treatment of missing data
- Handling of private data

Metadata and Readme files are two types of documentation, which are described below. Codebooks are typically used by survey researchers, and will not be covered here.

1. Metadata Files
  - Enhance the findability of the data
  - They are typically in XML or JSON format and are human- and machine-readable. Therefore they’re easy to search through digital repositories and resource databases.
  - They adhere to a standard schema. The most commonly accepted one is [Dublin Core](https://www.dublincore.org/specifications/dublin-core/usageguide/elements/).
  - When submitting data to a repository to be published, they will ask for this information and make it available through their search functions.
2. README Files
  - Enhance the understanding and usability of the data
  - They are typically in TXT or markdown format. These are typically human-readable and used by other researchers to understand the full context of the data. They need to be read on any platform.
  - These files include both the study-level and the data-level documentation elements. The standard elements of metadata files are included here as well, but readme files give users fuller contextual information after downloading the data. The readme files should be downloadable with the dataset.
  - Examples Templates:
    - [Dataset](https://github.com/lensor/new-member-onboarding/blob/main/Data-Management/README_DATASET_template.txt)
    - [Code](https://github.com/lensor/new-member-onboarding/blob/main/Data-Management/README_SOFTWARE_template.txt)
