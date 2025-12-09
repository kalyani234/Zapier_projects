# AI Automation Systems for Medical Aesthetics Clinics

This repository contains two end-to-end automation systems built for medical aesthetics clinics using Zapier, OpenAI, Google Sheets, HubSpot, and Gmail. These workflows reduce manual effort, eliminate inventory errors, accelerate lead response times, and create real operational impact for clinics offering Botox, fillers, injectables, and advanced skin treatments.

---

## Project 1 — AI Lead Qualification System

- Automates the analysis of all incoming leads using Zapier + OpenAI.
- Extracts structured CRM fields:
  - Primary treatment of interest
  - Budget range
  - Urgency
  - Client concerns
  - AI lead intent score
- Generates a personalised response message for each inquiry.
- Auto-updates HubSpot with enriched AI-generated fields.
- Enables prioritisation of high-intent clients and improves conversion.
- Eliminates manual review and ensures accuracy in lead handling.


   +------------------+          +----------------+          +--------------------+
   |  Lead Source     |  --->    |    Zapier      |  --->    |    OpenAI (LLM)    |
   | (Web Form, IG)   |          |  Trigger Zap   |          | Extract + Generate |
   +------------------+          +----------------+          +--------------------+
                                          |                           |
                                          v                           v
                                 +----------------+          +--------------------+
                                 |  HubSpot CRM   |          | Auto Reply Message |
                                 |  AI Fields Set |          | Returned to Zap    |
                                 +----------------+          +--------------------+
                                          |
                                          v
                                 +----------------+
                                 |  Clinic Team   |
                                 |  Lead Priorit. |
                                 +----------------+
  <img width="539" height="628" alt="image" src="https://github.com/user-attachments/assets/653260c0-9283-4edc-b0b5-ff2e71c00501" />



---

## Project 2 — Intelligent Inventory Automation

- Automates stock-level tracking for injectables and consumables (Botox, Profhilo, Juvederm, etc.).
- Practitioners log product usage via Google Forms.
- Zapier updates live inventory in Google Sheets.
- Detects:
  - Low stock (below minimum threshold)
  - Approaching expiry dates
- Sends automatic Gmail alerts to clinic managers.
- Prevents last-minute stockouts and expired product usage.
- Saves operational time and maintains regulatory compliance.

   +---------------------+      
         | Practitioner Input  |
         |  Google Form        |
         +----------+----------+
                    |
                    v
         +---------------------+
         | Zapier Trigger      |
         | Update Sheet        |
         +---------------------+
                    |
        +-----------+-----------+
        |                       |
        v                       v
+----------------+     +-----------------------+
| Inventory Sheet|     | Expiry / Low Stock   |
|   Updated      |     | Condition Check      |
+----------------+     +-----------------------+
                                |
                                v
                      +----------------------+
                      | Gmail Alert Email    |
                      | Sent to Manager      |
                      +----------------------+
<img width="763" height="657" alt="image" src="https://github.com/user-attachments/assets/caacd4ac-9814-4056-aa12-aedbedb8d1de" />



---

## Technologies Used
- Zapier  
- OpenAI API  
- HubSpot CRM  
- Google Sheets  
- Google Forms  
- Gmail Automation  

---

## Repository Structure

