# Level-Agnostic-Diagnostics-for-OntoUML-and-MLT

This repository consists of the following required artifacts :
- HUTN file (Human-Usable Textual Notation) of the model
- Program file (Datalog Facts and Rules executable on NEMO Graph Rule Engine)

**Paper-facing normalized summary:**

By executing xxxxx.rls file on NEMO, the output will be generated as .csv files. Following output demonstrates the voilations which can be found in the results folder: 


err_kind_bad_ancestor(PersonTypeByGender, PersonType, OntoUML.kind).

warn_bin_over(worksFor, Researcher, Manager).
warn_bin_over_case(worksFor, Researcher, Manager, BinOver.commonIdentityProvider).
warn_bin_over_witness(worksFor, Researcher, Manager, Alex).

err_non_adjacent_iof(Taylor, PersonTypeByGender, 0, 2).
err_partition_bad_member(PersonTypeByGender, Person, Taylor).
err_categorizer_bad_member(PersonTypeByGender, Person, Taylor).

err_partition_missing(PersonTypeByGender, Person, Alex).
err_partition_missing(ResearcherTypeByDoctoralStatus, Researcher, Alex).
err_partition_missing(ResearcherTypeByContractStatus, Researcher, Alex).

err_partition_overlap(PersonTypeByGender, Casey, Man, Woman).
err_partition_subtype_overlap(PersonTypeByGender, ManWomanOverlap, Man, Woman).

err_partition_specialization(ResearcherTypeByDoctoralStatus, ResearcherTypeByContractStatus, Researcher).

