### Lead Extraction and Qualification Workflow with Phantombuster

## Use Case

**Scenario:** B2B Sales Outreach  
**Target Profiles:** Decision-makers such as Marketing Managers, Growth Leads, and Founders in SaaS companies.



## Extracted Profile Fields

1. **Full Name** – Needed for personalized outreach.
2. **Job Title** – Helps identify decision-making authority.
3. **Company Name** – Useful for segmentation and research.
4. **Location** – Ensures geographic relevance.
5. **LinkedIn Profile URL** – Direct access for contact and verification.
6. **Company Size (via enrichment)** – Helps qualify business scale.



## Workflow Stages

### 1\. Search Input (Start)

* Use LinkedIn Sales Navigator search URL with filters:

  * Industry: SaaS
  * Roles: Marketing Manager, Founder, Growth Lead
  * Location: US, UK, India
* Input this URL into Phantombuster (LinkedIn Search Export Phantom).



### 2\. Data Extraction

* Phantom extracts profile data:

  * Name, Title, Company, Profile URL
* Data is stored automatically in a CSV/Google Sheet.



### 3\. Data Enrichment

* Use additional Phantom or API (e.g., Clearbit) to fetch:

  * Company size
  * Industry confirmation



### 4\. Qualification Filtering

Apply filters:

* **Job Title contains:** "Manager", "Head", "Founder"
* **Company Size:** 10–500 employees
* **Location:** Must match target regions

Only leads meeting all conditions move forward.



### 5\. Final Review \& Export

* Clean duplicates and incomplete records
* Tag leads (Hot / Warm based on role relevance)
* Export final list to Google Sheets or CRM
* Ready for outreach via email or LinkedIn automation



## Outcome

* A clean, targeted list of qualified leads
* Reduced manual effort
* Improved outreach efficiency and conversion potential

