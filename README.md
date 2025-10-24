# DIVINE-datasets <a href="https://bruigtp.github.io/DIVINE-datasets/"><img src="figures/logo.png" align="right" height="138" alt="DIVINE website" /></a>

<br>

DIVINE-datasets provides 13 curated and it is designed to support researchers in quickly accessing clean and structured data.


| Description | CSV |
|-------------|-----|
| Laboratory measurements at admission | [analytics](data/analytics.csv) |
| Pre-existing conditions, functional status and comorbidity indices at admission | [comorbidities](data/comorbidities.csv) |
| Clinical complications occurring during hospitalization | [complications](data/complications.csv) |
| Medications taken prior to hospital admission | [concomitant_medication](data/concomitant_medication.csv) |
| Patient baseline demographics and lifestyle factors | [demographic](data/demographic.csv) |
| Outcomes and end-of-follow-up metrics | [end_followup](data/end_followup.csv) |
| ICU admissions and interventions during hospitalization | [icu](data/icu.csv) |
| In-hospital antibiotic treatments | [inhosp_antibiotics](data/inhosp_antibiotics.csv) |
| In-hospital antiviral treatments | [inhosp_antivirals](data/inhosp_antivirals.csv) |
| Other in-hospital treatments and supportive therapies | [inhosp_other_treatments](data/inhosp_other_treatments.csv) |
| Severity scores at hospital admission | [scores](data/scores.csv) |
| COVID-19–related symptoms recorded at admission | [symptoms](data/symptoms.csv) |
| Vital signs measured at admission, oxygen support and basic chest x-ray findings | [vital_signs](data/vital_signs.csv) |
| COVID-19 vaccination records | [vaccine](data/vaccine.csv) |

## Quick notes
- Files are CSVs with header rows.
- Use `patient_id` (or equivalent) to join tables where available.
- Date columns use ISO format where possible (`YYYY-MM-DD`).

## Citation
If you use these data, please cite the DIVINE study and the relevant publication:

Pallarès N., Tebé C., Abelenda-Alonso G., Rombauts A., Oriol I., Simonetti A. F., Rodríguez-Molinero A., Izquierdo E., Díaz-Brito V., Molist G., Gómez Melis G., Carratalà J., Videla S., & MetroSud and DIVINE study groups (2023). *Characteristics and Outcomes by Ceiling of Care of Subjects Hospitalized with COVID-19 During Four Waves of the Pandemic in a Metropolitan Area: A Multicenter Cohort Study.* Infectious Diseases and Therapy, 12(1), 273–289. https://doi.org/10.1007/s40121-022-00705-w

## Contact
For questions, corrections or data-use requests: `npallares@igtp.cat`