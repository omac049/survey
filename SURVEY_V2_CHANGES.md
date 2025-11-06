# Survey v2 Changes - Based on Feedback

## Overview
This document summarizes the changes made to create v2 of the HR Manager Survey based on stakeholder feedback. The primary goals were to:
- Reduce survey length
- Eliminate redundant questions
- Remove leading statistics and context that might bias respondents
- Simplify certain question structures

---

## Changes by Section

### **Header & Title**
- **Changed:** Updated title to "HR Manager Survey (v2)"
- **Changed:** Badge updated to "2025 Research Study - v2"
- **Rationale:** Clearly identify this as version 2

### **Introduction Section**
- **Removed:** The entire "key-stats" section with 4 bullet points of statistics
  - 87.4% hiring stat
  - 100% pay parity stat
  - 55% global acceptance stat
  - 5%/23% equality agreement stat
- **Added:** More neutral introduction text focusing on the research purpose
- **Added:** Estimated completion time (10-15 minutes)
- **Rationale:** Original introduction was "leading the witness" with data upfront that could bias respondent answers

### **Section 1: Respondent & Organization Profile**
- **Changed:** Organization size options simplified from 4 tiers to 3 tiers:
  - **Old:** 1–49, 50–249, 250–999, 1,000+
  - **New:** Under 1,000 employees, 1,000-4,999 employees, 5,000+ employees
- **Rationale:** Simplified categorization requested in feedback

### **Section 2: Awareness & Credibility of Online Degrees**
- **Removed:** "Interview practices" question (3 options)
- **Removed:** "Record-keeping" question (3 options)
- **Removed:** Context box from "Degree modality awareness" question (90% stat)
- **Kept:** 3 remaining questions:
  - Degree modality awareness
  - Perceived credibility
  - Influencers of perception
- **Rationale:** Questions felt redundant or not pertinent to core research objectives

### **Section 3: Hiring & Compensation Practices**
- **Removed:** "Screening influence" question
- **Removed:** "Compensation parity" question + context box (100% NACE stat)
- **Removed:** "Hiring history" question + context box (87.4% NACE stat)
- **Removed:** "Leadership roles" question
- **Kept:** Only "Hiring interest" question (6-area rating scale)
- **Improved:** Changed "Functional openness" → "Hiring interest" for clarity
- **Improved:** Changed scale from "Not open/Very open" → "Not interested/Very interested"
- **Rationale:** Pare back section significantly to reduce survey length and redundancy; clearer wording

### **Section 4: Perception of Graduate vs. Undergraduate Online Programs**
- **Removed:** "Undergraduate vs. graduate credibility" question
- **Removed:** "Equality statement" agreement question + context box (5%/23% GMAC stat)
- **Changed:** "Rationale for equality rating" question renamed to "Perception of online degrees"
  - **New wording:** "Please briefly explain your organization's overall view of online degrees compared to traditional degrees."
- **Rationale:** Removed leading equality statement and simplified to one open-ended perception question

### **Section 5: Microcredentials & Upskilling**
- **No changes:** All 5 questions retained

### **Section 6: Learning & Development Investment**
- **Removed:** Context box from "Formal training programs" (218% ROI stat)
- **Removed:** Context box from "Employee training preference" (68% stat)
- **Removed:** Context box from "Perceived impact of training" (59% stat)
- **Kept:** All 4 questions retained, just removed the leading statistics
- **Rationale:** Maintain consistency by removing all context boxes with statistics that might lead respondents

### **Section 7: Future Outlook & Employer Expectations**
- **No changes:** All questions retained

### **Section 8: Featured Quote Opportunity**
- **No changes:** All content retained including informational context boxes (these are procedural, not statistical)

---

## Summary Statistics

### Questions Removed:
- Section 2: 2 questions removed
- Section 3: 4 questions removed
- Section 4: 2 questions removed
- **Total: 8 questions removed**

### Context Boxes Removed:
- Introduction: 1 large stats section
- Section 2: 1 context box
- Section 3: 2 context boxes
- Section 4: 1 context box
- Section 6: 3 context boxes
- **Total: 8 context boxes removed**

### Original Survey:
- 8 sections
- ~40 questions
- Multiple context boxes with statistics

### v2 Survey:
- 8 sections (same structure)
- ~32 questions (20% reduction)
- Only 2 informational context boxes remain (in Section 8, procedural only)
- Significantly shorter and less leading

---

## Functional Enhancements

### **Interactive Features Added**
- **Progress Tracking:** Real-time progress bar showing completion percentage
- **Auto-Save:** Responses automatically saved to browser localStorage every second
- **Submit Functionality:** Complete survey submission with validation
- **Download Responses:** Export all responses as JSON file for records
- **Clear & Restart:** Option to clear all responses and start over
- **"Other" Field Support:** Dynamic text fields appear when "Other (please specify)" is selected
- **Back to Top Button:** Quick navigation to top of survey
- **Progress Indicator:** Fixed header showing percentage complete
- **Visual Feedback:** Auto-save indicator confirms data is saved

### **Data Collection Features**
- Collects all question types: single-select, multi-select, ratings, text inputs
- Timestamps all responses
- Organizes data by section and question
- JSON format for easy analysis
- Browser-based storage (no server required for testing)

### **User Experience Improvements**
- Clearer question wording ("Hiring interest" vs "Functional openness")
- More natural scale labels ("Not interested/Very interested")
- Better labeling ("Personal experience/trust" vs "Personal bias/trust")
- Auto-focus on "Other" text fields
- Smooth animations and transitions
- Responsive design for all devices

---

## Benefits of v2

1. **Reduced Survey Fatigue:** Shorter survey reduces respondent fatigue and abandonment
2. **Less Bias:** Removal of leading statistics allows for more authentic responses
3. **Focused Questions:** Eliminated redundant questions keeps survey tight and purposeful
4. **Cleaner Analysis:** Fewer but more essential questions means cleaner data
5. **Faster Completion:** Estimated ~10-12 minutes vs original ~15-20 minutes

---

## Files Created

- **survey-v2.html** - Updated interactive survey with all changes implemented
- **SURVEY_V2_CHANGES.md** - This document summarizing all changes

---

## Next Steps

1. **Review:** Stakeholders should review v2 to ensure all concerns addressed
2. **Test:** Test survey flow and all interactive elements
3. **Pilot:** Consider pilot testing with small group before full deployment
4. **Data Collection:** Deploy v2 for actual data collection
5. **Analysis:** Compare response rates and data quality between v1 and v2 if applicable

---

**Document Created:** November 6, 2025  
**Survey Version:** 2.0  
**Changes Based On:** Stakeholder feedback document and team review
