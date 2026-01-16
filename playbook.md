# Ransomware Response Playbook

## Step 1: Preparation

The goal of this phase is to establish the technical and legal foundation required to respond to a ransomware incident.

* **Data Resiliency:**
    * Maintain three copies of all medical records.
    * Store them on two different media types.

* **Legal Readiness:**
    * Contact channels with INAI (Mexico) and HHS/OCR (USA).
    * Compliance with LFPDPPP and HIPAA.

---

## Step 2: Detection and Analysis

* **SIEM Alerting:** Monitor for high CPU usage on EHR servers.
* **Forensics:** Begin a Chain of Custody log for legal evidence.

---

## Step 3: Containment

* **Isolation:** Disconnect infected VLANs from the clinical network.
* **Paper Protocol:** Switch to manual records to ensure patient care.

---

## Step 4: Eradication

* **Clean Up:** Perform full system scans and remove malware.
* **Hardening:** Patch vulnerabilities in medical devices.

---

## Step 5: Recovery

* **Prioritization:** Restore life-critical systems (ICU) first.
* **Integrity:** Verify medical data accuracy before going live.

---

## Step 6: Lessons Learned

* **Compliance:** Finalize mandatory notifications to INAI/HHS.
* **Training:** Update staff on new security protocols.
