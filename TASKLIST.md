# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Initialization & Configuration**
  Initialize a new TanStack Start project. Configure Tailwind CSS for styling. Set up the basic folder structure for routes, components, and server functions. Ensure the dev server runs correctly.

- [ ] ⏳ **Database Setup & Schema Definition**
  Set up Drizzle ORM with SQLite. Create the initial schema including `users` and `listings` tables. Configure the database connection client and run the initial migration generation.

- [ ] ⏳ **Authentication System**
  Implement a basic authentication system (Sign Up/Login) using server functions. Create middleware to protect routes. Store session data in HTTP-only cookies. Create the Auth UI forms.

## Phase 2

- [ ] ⏳ **Create Listing Functionality**
  Build the 'Create Listing' page. Implement the server function to insert a new listing into the DB linked to the current user. Include form validation (Zod) for title, price, description, and category.

- [ ] ⏳ **Home Feed & Listing Display**
  Create the main landing page that fetches and displays a grid of active listings. Implement the server loader to fetch data from Drizzle. Design the `ListingCard` component.

- [ ] ⏳ **Listing Details Page**
  Create a dynamic route `/listings/$id`. Fetch specific listing details. Display full description, seller info, and price. Handle '404 Not Found' if the listing doesn't exist.

## Phase 3

- [ ] ⏳ **Image Upload Handling**
  Implement a basic image upload mechanism. For the MVP, this can either be a local file upload to the public folder or a simple Base64 string storage (if small) or a mock upload that returns a placeholder URL. Update the Create Listing form to support this.

- [ ] ⏳ **Search & Filter Implementation**
  Add a search bar and category dropdown to the Home Feed. Update the server loader to accept search params (query string, category) and filter the Drizzle query accordingly.

- [ ] ⏳ **Messaging System - Backend**
  Create a `messages` table in the DB. Implement server functions to `sendMessage` and `getConversation`. Ensure users can only see their own messages.

- [ ] ⏳ **Messaging System - UI**
  Create an 'Inbox' page to list conversations. Create a 'Chat' view to see message history and send new messages. Add a 'Contact Seller' button on the Listing Details page.

## Phase 4

- [ ] ⏳ **User Dashboard**
  Create a profile page where users can see their own active listings. Add functionality to delete their own listings.

- [ ] ⏳ **UI Polish & Responsive Design**
  Review all pages for mobile responsiveness. Improve styling of buttons, inputs, and cards. Add loading skeletons for data fetching states.

## Phase 5

- [ ] ⏳ **Error Handling & SEO**
  Implement global error boundaries for crashes. Add basic metadata (title, description) to pages for SEO. Clean up any console warnings.

---

_Last updated by dev0 automation_
