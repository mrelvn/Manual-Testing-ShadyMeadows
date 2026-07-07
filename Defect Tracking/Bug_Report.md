# 🐛 Defect Tracking Log - Shady Meadows B&B

**Project:** Shady Meadows B&B (Front-End)
**Environment:** QA / Staging (OS: Windows 11 | Browser: Chrome)
**Reporter:** Farzan Ahmad 

### 1. [PSM-27] Guest form does not expand instantly alongside the calendar upon clicking 'Book Now'
*   **Issue Type:** Bug | **Status:** To Do
*   **Priority:** Medium | **Severity:** Major

**Steps to Reproduce:**
1. Navigate to the rooms listing page.
2. Go to any active room booking card.
3. Click on the *"Book Now"* action button.

**Expected Result:**
Clicking "Book Now" should dynamically reveal both the booking calendar and the guest details form together directly beneath the active card.

**Actual Result:**
Only the booking calendar is revealed under the room booking card. The guest details form is completely missing.

---

### 2. [PSM-28] System crashes and displays a blank page when selecting a 0-night stay
*   **Issue Type:** Bug | **Status:** To Do
*   **Priority:** High | **Severity:** Critical (Blocker)

**Steps to Reproduce:**
1. Navigate to the “Check Availability & Book Your Stay” section.
2. Select a same Check-In and Check-Out date (e.g., 15-Oct).
3. Click on the “Book Now“ button for any active room card.
4. Fill the mandatory fields and click the “Reserve Now“ button.

**Expected Result:**
The system should either block the same-date selection or display a logical validation error message indicating a minimum 1-night stay is required.

**Actual Result:**
After selecting the same date for Check-In and Check-Out, the system crashes, and a blank page opens showing "Page couldn't load".

---

### 3. [PSM-29] Past dates are visible and can be selected via mouse click on the room booking calendar
*   **Issue Type:** Bug | **Status:** To Do
*   **Priority:** Highest | **Severity:** Major

**Steps to Reproduce:**
1. Navigate to the rooms booking section.
2. Select any active room card and open the booking calendar.
3. Locate any date prior to the current date (e.g., yesterday's date).
4. Attempt to click and select that past date.

**Expected Result:**
All past dates should be visually grayed out (disabled) and must be completely unselectable via mouse click to prevent booking backdates.

**Actual Result:**
Past dates are neither visually disabled nor restricted. The user is able to successfully click and select past dates on the calendar.

---

### 4. [PSM-30] System crashes and a blank page opens after entering alphanumeric characters in the phone field
*   **Issue Type:** Bug | **Status:** To Do
*   **Priority:** High | **Severity:** Critical (Blocker)

**Steps to Reproduce:**
1. Navigate to the room booking form.
2. Locate the **Phone** input field.
3. Enter alphabetical characters into the field (Test Data: `123ABC45678`).
4. Click on the "Reserve Now" button.

**Expected Result:**
The system should block the form submission and display a clear validation error message stating that the phone number must be numeric only.

**Actual Result:**
The system crashes instantly upon form submission, and a blank browser page opens displaying "Page couldn't load".

---

### 5. [PSM-31] Clicking the 'Cancel' button only collapses the guest form instead of returning to the default view
*   **Issue Type:** Bug | **Status:** To Do
*   **Priority:** Medium | **Severity:** Major

**Steps to Reproduce:**
1. Navigate to the rooms section.
2. Select any specific room and open its booking UI (Calendar and Guest Form).
3. Click on the *"Cancel"* button.

**Expected Result:**
The booking UI should collapse completely, closing both the guest form and the calendar, and smoothly return the user to the default view showing all available room cards.

**Actual Result:**
Only the guest form collapses. The system keeps the booking calendar open and remains stuck on that specific room card.