# Flickr API Photo Widget

This Ruby on Rails application serves as a basic photo widget that allows you to display photos from Flickr feeds. You can customize the widget to display photos from your own Flickr feed or someone else's by providing the Flickr user ID.

## Setup Instructions

Follow these steps to set up and run the Flickr API Photo Widget locally:

### Prerequisites

Make sure you have the following installed:

- Ruby (version 2.7.0 or higher)
- Rails (version 6.0.0 or higher)
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ismat-Samadov/Flickr_API.git
   ```

2. Navigate into the project directory:

   ```bash
   cd Flickr_API
   ```

3. Install dependencies:

   ```bash
   bundle install
   ```

4. Set up your Flickr API key:

   - Go to the [Flickr API Docs](https://www.flickr.com/services/apps/create/apply/) and click on "Create an App" to get your API key.
   - Once you have your API key, store it securely. You can use environment variables, the figaro gem, or Rails credentials to manage your API keys.

### Usage

To run the application, start the Rails server:

```bash
rails server
```

The application will be available at `http://localhost:3000`.

### How to Use

1. Navigate to the home page of the application.
2. Enter the Flickr user ID of the desired user in the provided form field.
3. Submit the form.
4. The page will refresh and display the photos from the specified Flickr user's feed.

### Additional Notes

- You can customize the application further by adding features such as pagination, image caching, or user authentication.
- Ensure that your API key is kept secure and not exposed in any public repositories.

## Acknowledgements

This project is part of the Ruby on Rails Course by [The Odin Project](https://www.theodinproject.com/). Special thanks to the instructors for providing the guidance and resources.