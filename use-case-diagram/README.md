# Airbnb Clone Backend

This repository contains the backend services for an Airbnb-style property rental marketplace. It powers the core functionalities allowing users to list, discover, and book unique accommodations.

---

## 🚀 Use Case Scenarios

Our Airbnb Clone backend supports a wide range of interactions for different types of users: **Guests**, **Hosts**, and **Admins**. Below are common scenarios demonstrating how users will leverage the platform.

### 🏠 For Guests (Looking for a Place to Stay)

Guests are at the heart of our platform, seeking the perfect accommodation for their travels.

1.  **Exploring Listings:**

    - A guest arrives at the platform and wants to find a place in **Lagos** for their upcoming vacation. They use the search bar, specify "Lagos" as the location, set a price range, and indicate they need space for "2 guests."
    - They might further refine their search by applying filters for amenities like "Wi-Fi" and "pool" to narrow down options.
    - As they scroll through the results, new properties are loaded via **pagination**, ensuring a smooth Browse experience.

2.  **Viewing Property Details:**

    - The guest clicks on a promising listing, "Cozy Apartment in Lekki," to view its full details. They see the description, available dates, photos, amenities, and read existing reviews from previous guests.

3.  **Booking a Property:**

    - After checking the availability, the guest selects their desired dates for the "Cozy Apartment in Lekki." The system validates these dates to prevent **double bookings**.
    - They proceed to the payment page, where they securely complete the **upfront payment** using an integrated payment gateway (e.g., Stripe).
    - Upon successful payment, the guest receives an **email notification** confirming their booking details. The booking status is updated to "confirmed."

4.  **Managing Bookings:**

    - Life happens! The guest later realizes they need to cancel their trip. They navigate to their bookings section and initiate a **cancellation** for the "Cozy Apartment in Lekki" booking, adhering to the host's cancellation policy.
    - They receive an **email notification** confirming the cancellation.

5.  **Leaving Reviews:**
    - After a wonderful stay, the guest wants to share their experience. They log in and leave a **review and rating** for the "Beachfront Villa" they just checked out from, providing valuable feedback for the host and future guests.

### 🏡 For Hosts (Listing Their Property)

Hosts are essential for providing diverse accommodation options on the platform.

1.  **Registering as a Host:**

    - Someone with a spare room or property decides to become a host. They sign up, selecting the "host" role during registration, and securely authenticate their account.

2.  **Creating a New Listing:**

    - The host logs in and goes to their dashboard to "Add New Listing." They provide a captivating title ("Spacious Home with Garden"), a detailed description, the exact location, daily price, a list of amenities (e.g., "parking," "air conditioning"), and upload high-quality photos of their property.
    - They also set the property's availability dates.

3.  **Managing Existing Listings:**

    - The host realizes they need to update the price for their "City Center Loft" due to increased demand. They navigate to their listings, **edit** the property details, and save the changes.
    - They might also **delete** an old listing that is no longer available.

4.  **Receiving Booking Notifications:**

    - A new booking comes in for their "Mountain Retreat"! The host receives an **email notification** about the pending booking.
    - Once the guest's payment is confirmed, the booking status changes, and they receive a final **confirmation notification**.

5.  **Receiving Payouts:**

    - After a guest successfully checks out from their "Riverside Cabin," the host automatically receives their **payout** for the completed booking via the integrated payment gateway.

6.  **Responding to Reviews:**
    - The host sees a new review for their "Spacious Home with Garden." They read the feedback and publicly **respond** to thank the guest or address any comments.

### ⚙️ For Admins (Platform Management)

Admins ensure the smooth operation and health of the entire platform.

1.  **User Management:**

    - An admin can access the **Admin Dashboard** to view all registered users (guests and hosts). They might need to review a user's profile, suspend an account, or verify user details.

2.  **Listing Oversight:**

    - The admin reviews reported listings or checks for policy compliance. They can **monitor, edit, or remove** any property listing if necessary.

3.  **Booking and Payment Monitoring:**
    - The admin can track all **bookings** across the platform, view their statuses, and intervene in case of disputes or issues.
    - They can also monitor **payment transactions** and generate reports on payouts and earnings.

---

This backend infrastructure is designed to provide a secure, scalable, and efficient foundation for all these interactions, ensuring a seamless experience for every user on the Airbnb Clone platform.
