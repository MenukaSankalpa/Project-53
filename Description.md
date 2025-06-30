# Movie Ticket Booking Website – Simple Explanation
In this project, we are building a full stack movie ticket booking website using the MERN Stack (MongoDB, Express.js, React.js, Node.js).

# What the website does:

Users can sign up and log in using Clerk, which supports:
Email signup
Social login (like Google)
Phone number login

After logging in, users can:
Explore available movies
Select seats
Book tickets online

# Admin Dashboard:

We also have a special section for admins, where they can:
Add new movies
Manage bookings
See booking details

# Multi-session Login with Clerk:

Users can create multiple accounts/profiles on the same device.
Easily switch between accounts without logging out.

# Email Automation with Inngest:

We use Inngest (a background task manager) to:
Send emails to all users when a new movie is added
Send booking confirmation emails
Send reminder emails a few hours before the movie starts

# Smart Seat Reservation:

When a user starts booking:

Their selected seats are reserved for 10 minutes
If payment fails or is cancelled, they can try again within 10 minutes
If they don’t complete the payment in 10 minutes, the seats are released automatically

# Technologies Used:

Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Authentication: Clerk
Email/Background Tasks: Inngest