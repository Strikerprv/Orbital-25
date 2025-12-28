# Orbital-25
Orbital 2025 - Team HoneyToast

## Motivation:
While planning for our overseas trip before university started, we found it very troublesome to plan and book the itinerary, as there are different websites to go to for booking flights, accommodation and activities, and even more websites to scroll through to find the activities to do. Therefore, we thought it would be a good idea to have a single website with all this information compiled and easily accessible, saving a lot of hassle when planning future travel trips.

Although present websites such as Trip.com make booking the aforementioned things very easy, we would like to add more personalised aspects such as an AI-powered chatbot and enable connection with the user’s primary calendars (eg. Google Calendar) to appeal users to start using the website and return as recurring users.

## Aim:
We aim to create a comprehensive one-stop website which satisfies user’s travel planning needs.

## Project Scope:
HoneyToast will be a website that is able to help users book most of their trips seamlessly and at once. The goal would be to simply have the user input their trip details once at the beginning, and HoneyToast would be able to use their trip details to search for flights, accommodations, as well as activities to do without them having to type out those details every time they start planning for different parts of their holiday, saving them the hassle. 


## User Stories:
1. As a user looking to travel overseas, I want a detailed itinerary which includes options for flight and accommodation bookings. After settling these details, I would like to have a list of activities that I could consider partaking in while I am at my destination.
2. As a user who is only interested in booking flights and hotel accommodations, I want to be able to see multiple options for both flight and hotel bookings which are within my budget. For example, hotel bookings should provide varied options (eg. more expensive hotel with more amenities and higher reviews & pod hotels which are much cheaper). Similarly, flight bookings should also provide multiple flight timings and costs within my budget.
3. As a user who has already reserved flights and accommodations, I want to be able to see the list of activities that I could join while I am in the country. Also, I would like to be able to book tickets for activities that require bookings.
4. As a user who has used the website to develop their itinerary, I would like to be able to easily access the itinerary during my holiday via a mobile application which displays the plan for the day in a concise manner.
5. As a user that is uncertain whether the suggested itinerary is ideal, I would like to be able to see other people’s review of the itinerary and select the most suitable itinerary.
6. As a user that wants to earn money from my accommodations such as hotels or airbnb, I would like my listing to be easily accessible for customers and booked with low commission.




## Features:

1. **User Authentication**

For users to login and make an account with our website so that we can retain certain booking details for future development of personalised elements such as personalised travel destination and itinerary recommendations. 

Implemented user authentication through Supabase, with full login and logout functionality. Able to login through email verification.

_Login page_:
<img width="1919" height="365" alt="image9" src="https://github.com/user-attachments/assets/584eb734-febb-41d7-be0b-829d67d4076a" />


2. **Trip Manager**

Users can save their existing trip plans so that they can easily refer to the list of places they are travelling to and when they are doing so when necessary.

Trip details stored in Supabase database, and search bar allows for search context so the latest trip inputted will be automatically filled into the accommodations search bar for improved user experience.

_Trip input page_:
<img width="1900" height="852" alt="image12" src="https://github.com/user-attachments/assets/c632d5b0-1bd1-4bda-9668-b05420855568" />

3. **Accommodation booking**

To allow users to book accommodations when they travel overseas. There are filters to search by destination, price, trip dates, number of adults and children, and number of rooms.

Hotel details are stored in Supabase database, and hotel pages are fully customizable based on uploaded photos, hotel name, description, location and price.

_Accommodations page search bar_:
<img width="1506" height="414" alt="image3" src="https://github.com/user-attachments/assets/7c184fce-5bb0-42a5-a7a4-212bdf83661d" />

_Accommodations page list of results_:
<img width="1902" height="766" alt="image10" src="https://github.com/user-attachments/assets/b5e236bd-b4ae-4f31-9c35-70dd4d89f6a4" />


4. **Flight booking**

Users can search for one-way and two-way flights. Real-time flight details are found using SerpApi Google Flights search API, and users will get redirected to external pages to finalise and purchase their flight booking.

The flight booking feature comprises four pages: 1) the initial flight search page, 2) outbound flight search page, 3) return flight search page and 4) flight summary and confirmation page. Users go through the four pages in the same order to search and select the flights that they prefer.

_Initial flight search page_:
<img width="1999" height="951" alt="image18" src="https://github.com/user-attachments/assets/58d1097a-1ea4-48bf-85ae-ea36d45a9270" />

_Return flight search page_:
<img width="1999" height="898" alt="image4" src="https://github.com/user-attachments/assets/afae6379-7c96-4faf-ba16-745b3b0486bc" />



5. **Itinerary generator**

User inputs their rough idea for an overseas trip, and this is sent as a prompt to deepseekAPI to generate a rough itinerary for users to use as a starting point to plan their trips.

_Itinerary generator_:
<img width="921" height="404" alt="image6" src="https://github.com/user-attachments/assets/e4958160-6709-46bd-81c2-61c2252250fa" />


6. **Booking manager**

Simple bookings page to help users access their accommodation bookings with hotel name, address, check-in and check-out dates as well as price.

_Booking Manager_:
<img width="1503" height="398" alt="image21" src="https://github.com/user-attachments/assets/19d6d197-3083-4c0e-827c-9f9a3b99e18b" />


7. **Travel calendar**

Travel calendar is used for users to plan for their future trips by showing them the dates that they are unavailable (e.g. existing trips or events on their calendars).

_Event information displayed when event icon is clicked_:
<img width="1999" height="1012" alt="image7" src="https://github.com/user-attachments/assets/63ee7628-acd0-4dba-8435-867786e93440" />
