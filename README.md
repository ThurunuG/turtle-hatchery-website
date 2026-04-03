# Hikkaduwa Turtle Hatchery Website

This project is a static multi-page website created for a turtle hatchery and ticket booking experience. It combines informational content about the Hikkaduwa Turtle Hatchery with a client-side ticket reservation flow built using HTML, CSS, and JavaScript.

## Project Overview

The website includes:

- An informational page about the Hikkaduwa Turtle Hatchery
- A ticket booking page with date, guest, and duration selection
- A details page to collect customer information
- A payment page with basic front-end validation
- A confirmation page that displays the final booking summary

The booking flow uses `localStorage` to pass user selections and form data between pages.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- `flatpickr` for date selection
- `intl-tel-input` for phone number input styling
- `localStorage` for temporary client-side data storage

## Project Files

Main files included in this repository:

- `Hikkaduwa Turtle Hatchery.html`
- `Hikkaduwa Turtle Hatchery.css`
- `TicketsPage.html`
- `TicketsPage.css`
- `TicketsPage.js`
- `DetailsPage.html`
- `DeatilsPage.css`
- `DetailsPage.js`
- `PaymentPage.html`
- `PaymentPage.css`
- `PaymentPage.js`
- `ConfirmationPage.html`
- `ConfirmationPage.css`
- `ConfirmationPage.js`

## Booking Flow

1. `TicketsPage.html`
   Users choose the visit date, guest categories, and time slots.

2. `DetailsPage.html`
   Users enter their full name, mobile number, and email address.

3. `PaymentPage.html`
   Users enter card details with front-end validation.

4. `ConfirmationPage.html`
   The system displays the final booking summary using saved `localStorage` data.

## How to Run

Because this is a static front-end project, you can run it in either of these ways:

1. Open `Hikkaduwa Turtle Hatchery.html` directly in a browser.
2. Or use a local server such as VS Code Live Server for a smoother development experience.

Recommended entry page:

- `Hikkaduwa Turtle Hatchery.html`

## Features

- Multi-page website structure
- Responsive navigation menu
- Informational tourism-style landing page
- Ticket price calculation based on guest type and peak hours
- Booking summary panel across all booking steps
- Form validation for contact and payment details
- Confirmation page with stored booking details

## Notes

- This repository currently contains the hatchery and booking-related pages.
- Some navigation links inside the HTML point to other pages such as `Home Page.html`, `Turtle Categories.html`, and `Threats To Turtles.html`, but those files are not present in this repository.
- All validation and payment handling are front-end only. There is no backend or real payment gateway integration.

## Future Improvements

- Add the missing linked pages to complete the full website
- Connect the booking flow to a backend database
- Replace mock payment validation with a real payment integration
- Improve accessibility and form validation messages
- Refactor repeated layout sections into reusable components if migrated to a framework

## Author

This project appears to be an academic web development assignment focused on front-end design, interaction, and form handling.
