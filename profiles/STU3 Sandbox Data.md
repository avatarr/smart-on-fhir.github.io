---
layout: main
title: STU3 Sandbox Data
---

The following datasets are available in the SMART STU3 Sandbox (link) for App testing and development.

* Core SMART Patients 
  * The 67 STU3 Core SMART Patients were developed using an improved version of the csv data files used to create the DSTU2 Core SMART Patients. The new [STU3 SMART Patient Data Generator](https://github.com/smart-on-fhir/sample-patients-stu3) created these sample patients from data files containing a mix of de-identified clinical data and synthetic data elements.
  * Improvements on the DSTU2 resources: Minor data cleanup, and addition of 7 practitioner resources.  
  * ID/tag:
  * Resources/ Conditions:
 
* Synthea
  * The SMART Team generated XX Synthetic sample patients in FHIR STU3 format using the [MITRE Synthea tool](https://github.com/synthetichealth/synthea/wiki). 
  * ID/tag:
  * Resources/Conditions:
 
* Patient Reported Outcome Measures (PROMs)
  * The SMART Team generated 100 Sample patients using PROMs data available online from the UK National Health Service. PROMs measures health gain in patients undergoing hip replacement, knee replacement, varicose vein and groin hernia surgery in England, based on responses to questionnaires before and after surgery.
  * The [Sample Patients that SMART generated](https://github.com/smart-on-fhir/sample-patients-prom) contain a mixture of real and synthetic data elements, based on the data available in the [PROMs csv data package](http://content.digital.nhs.uk/catalogue/PUB23908). For more information about the source of the data contained within the PROMs patient resources, please see the full [SMART PROMs Sample Patient documentation.](https://github.com/smart-on-fhir/smart-on-fhir.github.io/new/master/profiles)  
  * ID/tag: SMART-PROMs
  * Resources: Patient, Procedure, Encounter, Questionnaire, Questionnaire Response