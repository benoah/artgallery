# Image attributions:
* https://picsum.photos/
* https://unsplash.com/

# GitHub repo of images and JSON file
* https://github.com/bobziroll/scrimba-react-bootcamp-images

# Icon library
* https://remixicon.com/

# Libraries
* React Router - https://reacttraining.com/react-router/web/guides/quick-start
* PropTypes - https://reactjs.org/docs/typechecking-with-proptypes.html

# New URL
* https://cdn.jsdelivr.net/npm/remixicon@2.3.0/fonts/remixicon.css

# Challenge One 

Set up React Router for our app. We should be able to do the following:

1. Click on the words "Pic Some" in the header to go to the "/" route, which should display the Photos component (found in the pages folder)

2. Click on the shopping cart icon in the header to go to the "/cart" route, which should display the Cart component (found in the pages folder)

# Challenge Two

Set up the Context for our app.

1. In a new file, create a new context with React
2. In that same file, create a custom component that renders the Provider of the context you created
3. For now, just pass in an empty string "" as the context provider's value prop
4. Export the custom Provider component and the full context object (so we can pass it to the useContext hook eventually)
5. Set up your index.js dto use the custom context Provider you created. (You can wrap it as a parent of the Router component)


# Challenge three

Add state to our context and pass it through the Provider

1. Add state to hold the array of all photos our app gets from the API
2. Pass the array of all photos through the value of the provider so it's available anywhere the app accesses the context
