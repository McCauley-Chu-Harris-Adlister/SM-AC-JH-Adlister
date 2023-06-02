<h1>Ad-Lister Project</h1>
<h3>
This readme file provides an overview of the functionalities implemented in the "Ad Show Page" feature. The goal of this feature is to create a page that displays detailed information about an individual ad, including the user who posted it. The readme will outline the various functionalities and considerations involved in implementing this feature.
</h3>

Functionalities
Ads Index Page: The ads index page should list all the ads available, providing links to each individual ad page.



User Profile Page: When a user visits their profile page, they should see all the ads they have created. This feature ensures that users can easily view and manage their own ads.

Unique Usernames: Update the database schema to enforce uniqueness in the username column of the user table. This prevents the creation of new accounts with existing usernames, ensuring each user has a unique identifier.

Code Cleanup: Identify and eliminate duplicated code in the ads Data Access Object (DAO) and users DAO. Consider creating an abstraction or shared module that can be used by both DAOs to reduce redundancy.

Dynamic Navbar: Implement a dynamic navigation bar that displays different links depending on whether a user is logged in or logged out. This feature enhances the user experience and provides relevant options based on the user's authentication status.

Update and Delete Ads: Allow users to update and delete their ads. Make necessary changes to the frontend to enable users to discover these functionalities, and implement the backend logic to update the database accordingly.

Update Profile Information: Enable users to update their profile information. Users should be able to modify their personal details, such as name, email address, or profile picture, and save the changes to the database.

Data Validation: Implement data validation to ensure that user-provided data is valid before saving it to the database. Consider creating validation classes or functions to validate user inputs and prevent the storage of invalid or inconsistent data.

Error Messages: Provide informative error messages to users when they encounter issues or perform incorrect actions. Display error messages in appropriate situations, such as when registering with mismatched passwords or creating an ad without a title. Consider using temporary storage, such as session variables, to store error messages and a partial template (e.g., messages.jsp) to handle their display.


Ad Categories: Create a categories table and implement the necessary backend logic to associate categories with ads. Establish a many-to-many relationship between ads and categories, allowing an ad to have multiple categories, and a category to have multiple associated ads.

Search Ads by Category: Enable users to search for ads based on their category. Implement a feature that allows users to filter ads by selecting a specific category, helping them find relevant content more easily.

