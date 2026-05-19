# Level-Agnostic-Diagnostics-for-OntoUML-and-MLT

Paper-facing normalized summary:
err_kind_bad_ancestor(PersonTypeByGender, PersonType, OntoUML.kind)

warn_bin_over(worksFor, Researcher, Manager)
warn_bin_over_case(worksFor, Researcher, Manager, BinOver.commonIdentityProvider)
warn_bin_over_witness(worksFor, Researcher, Manager, Alex)

err_non_adjacent_iof(Taylor, PersonTypeByGender, 0, 2)
err_partition_bad_member(PersonTypeByGender, Person, Taylor)
err_categorizer_bad_member(PersonTypeByGender, Person, Taylor)

err_partition_missing(PersonTypeByGender, Person, Alex)
err_partition_missing(ResearcherTypeByDoctoralStatus, Researcher, Alex)
err_partition_missing(ResearcherTypeByContractStatus, Researcher, Alex)

err_partition_overlap(PersonTypeByGender, Casey, Man, Woman)
err_partition_subtype_overlap(PersonTypeByGender, ManWomanOverlap, Man, Woman)

err_partition_specialization(ResearcherTypeByDoctoralStatus, ResearcherTypeByContractStatus, Researcher)

