# NHS App Dashboard v1.4

## Data Caveats:
- GP Registered Patients data is not available for a small proportion of GP practices. Any metrics that use this measure as a denominator (e.g. Proportion of GP population registered for the NHS App) will have a slightly higher than expected rate.

- The dashboard displays data only for GP practices that are currently active. Should a practice close, their historical data will no longer appear in the dashboard.

## Version 1.4 Change Log (29-11-2020)

### 1. Features Added

- **National Summary and Local App Usage:** Split national and local level data into separate sheets. Filters now work correctly on all graphs with no caveats
- **Data Table page:** Allows users to easily filter data via Region, STP, CCG, CCG Code, Practice, Practice Code. 
- **Data Dictionary page:** Will help users understand the meaning, description, lowest level of data, calculation, limitations and data source(s) for the different metrics in the NHS App Analytics Dashboard
- **Information icons:** Allow the user to understand the purpose behind each page 

### 2. User Interface Changes
-  UI fixes on National Summary Dashboard charts and titles to ensure accessibility, as well as adherence to NHSE&I dashboard formatting guidance
- Clickable mailto link added to About page to allow users to email developers for support
- Minor UI fixes to the About page
- UI fixes on National Summary and App Usage pages
- Consistent colour scheme applied to all charts on dashboard to improve user experience
- Minor UI fixes on National Summary and App Usage page
- Header formatting changed for all pages to improve user experience
- Null Value(s) option deleted from filters
- Filters now correspond with all charts

### 3. Features Removed: 
To ensure the dashboard only includes metrics that are supported by the NHS App, the following charts have been removed:
- Registrations by Non-Patient Online users running total
- % of registrations by Non-Patient Online Users based on running totals
- Active returning visitors


## Version 1.3 Change Log (29-09-2020)

### 1. User Verification Process 
To improve the App’s user registration journey and increase digital uptake, a 2-tier verification process has been implemented for new App users. The two tiers are as follows: 
- Partially Verified (P5) users - Requiring Name, Email, D.O.B, Postcode and Mobile Number 
- Fully Verified (P9) users - Requiring Photo ID and Photo/Video Identity Matching 
Partially verified (P5) users cannot access confidential information, and have limited access to App features until fully (P9) verified. 

### 2. Updated Registration Metric 
The 'NHS App Registrations' metric has been updated to give a count of new App users who have obtained full (P9) verification. The dashboard has now been updated to account for this change and will resume weekly updates.

As a result of the new verification process and developments to the App over time, a new method for tracking user acquisition has been established. Previously, patients moving practice may have been assigned a new Linkage Key, and would therefore have been counted as a new app user. Data prior to May-2020 has been updated to reflect the new tracking method made possible by the new verification system, which avoids the risk of duplication. This may result in a slightly lower registrations count at practice level prior to May-2020.
