# Database Schema

## hospitals

Primary Key:
- facility_id

Columns:
- facility_id
- facility_name
- address
- citytown
- state
- zip_code
- countyparish
- telephone_number
- hospital_type
- hospital_ownership
- emergency_services
- hospital_overall_rating

---

## readmissions

Primary Key:
- facility_id
- measure_name

Columns:
- facility_id
- measure_name
- excess_readmission_ratio
- predicted_readmission_rate
- expected_readmission_rate
- number_of_readmissions
- number_of_discharges
- start_date
- end_date

---

## patient_survey

Primary Key:
- facility_id
- hcahps_measure_id

Columns:
- facility_id
- hcahps_measure_id
- hcahps_question
- hcahps_answer_description
- patient_survey_star_rating
- hcahps_answer_percent
- number_of_completed_surveys
- survey_response_rate_percent
- start_date
- end_date