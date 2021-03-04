# Snap Shot

### Instructions

You are given 45 mins to create a clone of https://yog9.github.io/SnapShot/

- Carefully examine the site
- Try to timebox 30 mins for React and Unit Tests (1 unit test is enough) and 15 mins for CSS
- You are allowed to use any library you prefer.
- You may also google any information but not the solution.
- Please think out loud and ask any clarification questions...

Snap Shot is a gallery created using React,React Hooks, React Router and Context API. The Routes were setup for four default pages and a search page. Also the images were displayed using the Flickr API and axios to fetch data.

You will be tested for the following

- React js
- React Router
- React Hooks
- Unit Tests
- Context API
- Flickr API
- CSS Layout
- Responsiveness

### Flickr API

**GET**

`https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=${apiKey}&tags=${query}&per_page=24&format=json&nojsoncallback=1`

`export const apiKey = "636e1481b4f3c446d26b8eb6ebfe7127";`
