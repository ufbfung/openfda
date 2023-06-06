# Overview
This repository is used for development of useful APIs calls for a variety of use cases. 

# Initial use cases
- Retrieve a list of unique structured product labels (SPL) for products/drugs of interest. Specifically, we want to retrieve the spl_set_id, which is stable across versions of the label as we only want the most recent version. We will the input we want to use, but will explore a variety of options to support that include: pharmaceutical class, generic name, & ndc_codes
- Retrieve a list of 'indications' from the SPL that correspond with the SPLs we identified from the first use case. We will take this and export it into a csv that can be manipulated and reviewed with subject matter experts (SMEs). 
