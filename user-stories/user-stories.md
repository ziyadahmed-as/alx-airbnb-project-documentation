 user scenarios based on the user stories derived from the use case diagram. These scenarios are written from the perspective of a software development team preparing to implement features in an Airbnb-like platform.

✅ 1. Guest User – Search for Properties
Title: Property Search Functionality
Actor: Guest User
Scenario:
A guest user visits the platform without logging in. They navigate to the property search page and enter a destination, check-in and check-out dates, and the number of guests. The system filters the available properties based on the criteria and displays a list of matching results. The user can view details of each property and proceed to check availability or make a booking.

✅ 2. Guest User – Make a Booking
Title: Booking a Property
Actor: Guest User
Scenario:
After finding a suitable property, the guest user selects the dates, reviews the total price, and clicks "Book Now." The system prompts the user to log in or provide guest information. Once payment details are submitted and verified, the booking is confirmed, and the user receives a confirmation email and receipt.

✅ 3. Host – List a New Property
Title: Listing a New Property
Actor: Host
Scenario:
A registered host logs in and navigates to the "List a Property" section. The host fills out a form with property details, including title, description, location, amenities, photos, and availability. Once submitted, the system validates the input and creates a new listing. The property becomes visible to guest users during searches.

✅ 4. Host – Manage Property Availability
Title: Managing Availability
Actor: Host
Scenario:
The host accesses the "Manage Availability" section from their dashboard. A calendar interface displays the booked and available dates. The host selects specific dates to block or unblock availability. Upon saving, the system updates the listing so it reflects the changes in future guest searches.

✅ 5. Admin – View Payment History
Title: Viewing Payment History
Actor: Admin
Scenario:
An admin logs in and accesses the admin dashboard. From there, they select "View Payment History." The system displays a searchable table of all transactions including booking ID, user, host, amount, date, and payment status. The admin can filter by date range, user, or property to investigate specific transactions.