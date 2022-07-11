# FAIKR3-Project

## Introduction

Postoperative patient care has several components: - surveillance, − prevention of complications associated with surgical disease or other preexisting comorbidities, − specific postoperative treatment of the surgical disease and its complications. While these distinctions are purely didactic, the postoperative care merges into an active surveillance with a higher level of standardization than it would seem at first glance.

The goal of this project is to determine where patients in a postoperative recovery area should be sent to next. Because hypothermia is a significant concern after surgery, the attributes correspond roughly to body temperature measurements.

Number of Instances: 90

Number of Attributes: 9 including the decision (class attribute)

Attribute Information:

1. L-CORE (patient's internal temperature in C):
            
            high (> 37), mid (>= 36 and <= 37), low (< 36)
2. L-SURF (patient's surface temperature in C):
              
              high (> 36.5), mid (>= 36.5 and <= 35), low (< 35)
3. L-O2 (oxygen saturation in %):
              
              excellent (>= 98), good (>= 90 and < 98),
              fair (>= 80 and < 90), poor (< 80)
4. L-BP (last measurement of blood pressure):
              
              high (> 130/90), mid (<= 130/90 and >= 90/70), low (< 90/70)
5. SURF-STBL (stability of patient's surface temperature):
              
              stable, mod-stable, unstable
6. CORE-STBL (stability of patient's core temperature)
              
              stable, mod-stable, unstable
7. BP-STBL (stability of patient's blood pressure)
              
              stable, mod-stable, unstable
8. COMFORT (patient's perceived comfort at discharge, measured as
              
              an integer between 0 and 20)
9. ADM-DECS (discharge decision):
              
              I (patient sent to Intensive Care Unit),
              S (patient prepared to go home),
              A (patient sent to general hospital floor)


Dataset [link](https://archive.ics.uci.edu/ml/datasets/Post-Operative+Patient).