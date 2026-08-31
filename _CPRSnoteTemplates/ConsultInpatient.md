VASCULAR SURGERY INPATIENT / EMERGENCY DEPARTMENT CONSULT 

--------------------------------------------
CONSULT REQUEST
--------------------------------------------
Requesting provider/team:{FLD:TEXT (1-40 CHAR) REQ}. 
Consultation date: {FLD:DATE (TODAY DEFAULT)}.
Consult question: {FLD:TEXT (1-40 CHAR) REQ}.


--------------------------------------------
MEDICALLY-APPROPRIATE HISTORY & PHYSICAL
--------------------------------------------
Relevant history provided by the patient, patient family members, referring team:
{FLD:WP 10/70}


|ACTIVE PROBLEMS| 


All: |ALLERGIES/ADR|

|ACTIVE MEDS COMBINED|


SOCIAL HISTORY / SOCIAL FACTORS AFFECTING CARE (Examples: limited ability to 
offload limb, transportation barriers, wound care access, smoking):
{FLD:WP 10/70}



-------------------------------------------------------
CONSULTANT'S INDEPENDENT ASSESSMENT AND RECOMMENDATIONS
-------------------------------------------------------
Our working diagnosis for the consulting problem/question is:
{FLD:WP BLANK (0 INDENT)}


We are asking the referring physician/team to do the following:
{FLD:WP 10/70}

Our vascular surgery team will provide the following additions to this patient's 
management:
{FLD:WP 10/70}

I have personally discussed this working diagnosis and management plan with staff vascular surgeon 
Dr. {FLD:TEXT (1-30 CHAR) REQ}.


-------------------------------------------------------
COMMUNICATION TO REQUESTING PROVIDER
-------------------------------------------------------
Discussed assessment and plan with {FLD:TEXT (1-30 CHAR) REQ} at {FLD:DATE & TIME (REQUIRED)}. 

The aforementioned recommendations were reviewed with this health care provider 
and verbally acknowledged as understood. 

-------------------------------------------------------
PRELIMINARY SURGICAL READINESS
-------------------------------------------------------
REVIEW of pertinent laboratory data
Last three eGFR estimates:
|LR EGFR LAST 3|

Hematological, three most recent HEMOGLOBIN levels:
|HGB 3/6MO|

Coagulation-related:
    |LAB HEADER|
|LR PLT 1M NULL|
|LR INR 1Y NULL|
|LR PTIME 1Y NULL|
|LR PTT(MAIN LAB) 1Y NULL|

Preliminary checklist:
 5[ ] type & screen, 90d
 6[ ] 12-lead ECG, 90d
        |EKG MOST RECENT|
 7[ ] chest x-ray, 90d
        |RA CHEST XRAY 2 PA LAT|
 8[ ] pacemaker nurse evaluation note, 6 mos.
10[ ] LST documentation, lifetime
11[ ] contrast allergy history: |ALLERGIES/ADR|
15[ ] antiplatelet/anticoagulant med plan
|ANTICOAGULATION/ANTI-PLATELET ACTIVE MEDS|


16[ ] SGLT2-Is and GLP-1 agonist med plan
|DIABETES MEDICATIONS|

17[ ] dialysis timing
-------------------------------------------------------
