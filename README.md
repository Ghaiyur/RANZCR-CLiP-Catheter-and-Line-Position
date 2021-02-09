# RANZCR CLiP-Catheter and Line Position
Classify the presence and correct placement of tubes on chest x-rays to save lives

## Introduction 

Serious complications can occur as a result of malpositioned lines and tubes in patients. Doctors and nurses frequently use checklists for placement of lifesaving equipment to ensure they follow protocol in managing patients. Yet, these steps can be time consuming and are still prone to human error, especially in stressful situations when hospitals are at capacity.

Hospital patients can have catheters and lines inserted during the course of their admission and serious complications can arise if they are positioned incorrectly. Nasogastric tube malpositioning into the airways has been reported in up to 3% of cases, with up to 40% of these cases demonstrating complications [1-3]. Airway tube malposition in adult patients intubated outside the operating room is seen in up to 25% of cases [4,5]. The likelihood of complication is directly related to both the experience level and specialty of the proceduralist. Early recognition of malpositioned tubes is the key to preventing risky complications (even death), even more so now that millions of COVID-19 patients are in need of these tubes and lines.

The gold standard for the confirmation of line and tube positions are chest radiographs. However, a physician or radiologist must manually check these chest x-rays to verify that the lines and tubes are in the optimal position. Not only does this leave room for human error, but delays are also common as radiologists can be busy reporting other scans. Deep learning algorithms may be able to automatically detect malpositioned catheters and lines. Once alerted, clinicians can reposition or remove them to avoid life-threatening complications.

The Royal Australian and New Zealand College of Radiologists (RANZCR) is a not-for-profit professional organisation for clinical radiologists and radiation oncologists in Australia, New Zealand, and Singapore. The group is one of many medical organisations around the world (including the NHS) that recognizes malpositioned tubes and lines as preventable. RANZCR is helping design safety systems where such errors will be caught.

Detect the presence and position of catheters and lines on chest x-rays. Use machine learning to train and test your model on 40,000 images to categorize a tube that is poorly placed.

The dataset has been labelled with a set of definitions to ensure consistency with labelling. The normal category includes lines that were appropriately positioned and did not require repositioning. The borderline category includes lines that would ideally require some repositioning but would in most cases still function adequately in their current position. The abnormal category included lines that required immediate repositioning.

This may help clinicians save lives. Earlier detection of malpositioned catheters and lines is even more important as COVID-19 cases continue to surge. Many hospitals are at capacity and more patients are in need of these tubes and lines. Quick feedback on catheter and line placement could help clinicians better treat these patients. Beyond COVID-19, detection of line and tube position will ALWAYS be a requirement in many ill hospital patients.

## Acknowledgement

- Koopmann MC, Kudsk KA, Szotkowski MJ, Rees SM. A Team-Based Protocol and Electromagnetic Technology Eliminate Feeding Tube Placement Complications [Internet]. Vol. 253, Annals of Surgery. 2011. p. 297–302. Available from: http://dx.doi.org/10.1097/sla.0b013e318208f550
- Sorokin R, Gottlieb JE. Enhancing patient safety during feeding-tube insertion: a review of more than 2,000 insertions. JPEN J Parenter Enteral Nutr. 2006 Sep;30(5):440–5.
Marderstein EL, Simmons RL, Ochoa JB. Patient safety: effect of institutional protocols on adverse events related to feeding tube placement in the critically ill. J Am Coll Surg. 2004 Jul;199(1):39–47; discussion 47–50.
- Jemmett ME. Unrecognized Misplacement of Endotracheal Tubes in a Mixed Urban to Rural Emergency Medical Services Setting [Internet]. Vol. 10, Academic Emergency Medicine. 2003. p. 961–5. Available from: http://dx.doi.org/10.1197/s1069-6563(03)00315-4
Lotano R, Gerber D, Aseron C, Santarelli R, Pratter M. Utility of postintubation chest radiographs in the intensive care unit. Crit Care. 2000 Jan 24;4(1):50–3.
