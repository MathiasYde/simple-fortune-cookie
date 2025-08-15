# Simple Fortune Cookie

Fortune Cookie as a service.

## Features

Our extensive user research led us to the revelation that our service requires the following features:

- Get one fortune cookie: Feeling just a little bit sad and like you need just a little advice? Grab a single fortune cookie and find a little joy in life
- Get all fortune cookies: Feeling a whole lot of sad, then grab all of our fortune cookies!
- Make a new fortune cookie: Want to collaborate on creating the best fortune cookies? Then submit a new fortune cookie that will be added to the database

## Architecture

Frontend
Backend
Database
**Frontend**: The user interface of the service, allowing users to interact with fortune cookies. Users can request a single fortune, view all fortunes, or submit new ones. The frontend communicates with the backend via API calls.

**Backend**: Handles the business logic and processes requests from the frontend. It retrieves fortunes from the database, adds new fortunes, and ensures data is properly managed and served to the frontend.

**Database**: Stores all fortune cookies, including user-submitted ones. The backend interacts with the database to fetch, insert, and update fortune data as needed.
