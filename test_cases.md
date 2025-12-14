# Test Cases – Flight Booking System

| Test Case ID | Scenario ID | Test Scenario | Test Steps | Test Data | Expected Result | Actual Result | Status |
|-------------|-------------|---------------|------------|-----------|-----------------|---------------|--------|
| TC_01 | TS_01 | Verify flight search with valid source and destination | Open browser → Navigate to https://blazedemo.com → Select source city as Boston → Select destination city as London → Click Find Flights | From: Boston, To: London | Available flights should be displayed | Available flights displayed | Pass |
| TC_02 | TS_02 | Verify behavior when source and destination are same | Open application → Select source city as Boston → Observe destination dropdown | From: Boston, To: N/A | User should not be able to select the same city for source and destination | Destination dropdown does not allow selecting the same city | Pass |
| TC_03 | TS_03 | Verify flight list is displayed after search | Perform valid flight search | Valid source and destination | Flight list table should be displayed | Flight list displayed | Pass |
| TC_04 | TS_04 | Verify flight selection functionality | Perform valid flight search → Click Choose This Flight | Any available flight | Booking page should open | Booking page opened | Pass |
| TC_05 | TS_05 | Verify booking form with valid details | Select a flight → Enter valid passenger and card details → Click Purchase Flight | Valid passenger & card details | Confirmation page should be displayed | Confirmation page displayed | Pass |
| TC_06 | TS_06 | Verify booking form with missing mandatory fields | Select a flight → Leave Name field empty → Click Purchase Flight | Name: Blank | Error message should be displayed | Booking allowed without name | Fail |
| TC_07 | TS_07 | Verify successful purchase confirmation | Complete booking with valid details | Valid booking details | Confirmation message and booking ID should be displayed | Confirmation message displayed | Pass |
