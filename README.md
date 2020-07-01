# HCAI COVID 19 Dashboard

> __NOTE: Dashboard currently in development__

> THIS IS SYNTHETIC DATA, AND IS NOT REFLECTIVE OF ACTUAL RESULTS

Once you clone this repo, run `renv::restore()` on your first instance in R Studio to load up the managed package list.

This dashboard shows the location at where a patient was when they had their first COVID-19 positive PCR test, in relation to a hospital attendance in A&E or inpatient admission.

This therefore, does not always reflect where a patient has ultimately recieved inpatient care.

For example, where a patient attended A&E in Trust 1 and was tested positive, then two days later was admitted as an inpatient in Trust 2, this dashboard will assign them to Trust 1.

Please note that these data are purely for PHE internal testing purposes only and are not fit for reporting or analysis at this time.

Unlinked caess are assigned a trust based on the lab which undertook the test, this will result in some trusts having unlinked cases from smaller surrounding hospitals shown in grey
