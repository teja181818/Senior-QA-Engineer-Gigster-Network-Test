****Test Plan for "Rent a car" functionality of Lyft's website:**
**1.	Introduction:****
•	Purpose: The purpose of this test plan is to ensure that the "Rent a car" functionality on Lyft's website functions as expected, providing users with a seamless experience in renting a car.
•	Scope: The testing will cover the "Rent a car" form functionality, including positive and negative scenarios.
•	Resources: Testing will be conducted using various web browsers and devices to ensure compatibility.
•	Roles and Responsibilities: QA team members will be responsible for executing tests and reporting issues.
**2.	Test Scenarios:**
•	Positive Scenario: User successfully rents a car.
•	Negative Scenario: User encounters an error while attempting to rent a car.
**3.	Test Environment:**
•	Browsers: Chrome, Firefox, Safari, Edge
•	Devices: Desktop, Laptop, Tablet, Mobile (iOS and Android)
**4.	Test Cases:**
**a)	 Positive Scenario: User Successfully Rents a Car**
 ** i.	Preconditions:**
          a.	User is on the Lyft website and navigates to the "Rentals" section.
          b.	The user has valid payment information available.
 ** ii.	Steps:**
          a.	Step 1: User selects the "Rentals" option from the Lyft website's navigation menu.
          b.	Step 2: User fills out the "Rent a car" form with the following valid information:
                  i.	Pickup Location: "San Francisco International Airport (SFO)"
                  ii.	Pickup Date: Today's date or a future date
                  iii.	Return Date: A date at least one day after the pickup date
                  iv.	Car Type: Standard, SUV, Luxury, etc.
          c.	Step 3: User clicks on the "Search" or "Rent Now" button.
          d.	Step 4: User is presented with available cars matching the selected criteria.
          e.	Step 5: User selects a car and clicks on the "Continue" button.
          f.	Step 6: User proceeds to the payment page, fills out payment details, and completes the rental process.
          g.	Step 7: User receives a confirmation message on the website and a confirmation email with rental details.
**iii.	Expected Results:**
          a.	User is able to successfully rent a car without encountering any errors.
          b.	User receives a confirmation message on the website and a confirmation email with rental details.
          c.	The rented car is reserved for the specified pickup and return dates.
**b)	Negative Scenario: User Encounters an Error While Attempting to Rent a Car**
**    i.	Preconditions:**
          a.	User is on the Lyft website and navigates to the "Rentals" section.
     ** ii.	Steps:**
          a.	Step 1: User selects the "Rentals" option from the Lyft website's navigation menu.
          b.	Step 2: User fills out the "Rent a car" form with the following invalid information:
                i.	Pickup Location: An invalid location or a location outside Lyft's service area
                ii.	Pickup Date: A past date or a date before the current time
                iii.	Return Date: A date before the pickup date or a date within the same day as the pickup date
                iv.	Car Type: Any selection
          c.	Step 3: User clicks on the "Search" or "Rent Now" button.
          d.	Step 4: System should display appropriate error messages for each invalid input.
          e.	Step 5: User corrects the invalid inputs and resubmits the form.
          f.	Step 6: User attempts to proceed to the payment page without filling out all required fields.
          g.	Step 7: System should prevent the user from proceeding and display an error message.
     ** iii.	Expected Results:  **
                a.	System displays appropriate error messages for each invalid input.
                b.	User is unable to proceed to the payment page until all required fields are correctly filled out.
                c.	User receives guidance on how to correct the errors and proceed with the rental process.
**5.	Test Execution:**
•	Execute each test case in the specified test environment.
•	Record any discrepancies or issues encountered during testing.
•	Document test results and provide detailed reports.
**6.	Defect Management:**
•	Report any defects encountered during testing using a designated defect tracking tool.
•	Assign severity and priority levels to each reported defect.
•	Work with the development team to resolve identified issues.
**7.	Conclusion:**
•	Upon completion of testing, provide a summary of test results and any recommendations for improvements to the "Rent a car" functionality.
