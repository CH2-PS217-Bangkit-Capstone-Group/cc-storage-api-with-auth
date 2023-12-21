# Module Used

- Node.js
- Express.js
- Firebase (for cloud storage)
- Multer
- Moment (for time zoning)

# Prerequisites

- Node.js installed
- Install all modules
- Setup Firebase account and project and also credentials

# Endpoints
- /profileimage/:uid (POST) - Upload profile image
- /profileimage/:uid (GET) - Retrieve profile image
- /images/:uid/:category (POST) - Upload image with a category
- /images/:uid (GET) - Retrieve all images for a user
- /images/:uid/:category (GET) - Retrieve images by category
- /outfit/:uid (POST) - Upload outfit image
- /outfit/:uid (GET) - Retrieve outfit images
- /deleteaccount/:email (DELETE) - Delete user account
