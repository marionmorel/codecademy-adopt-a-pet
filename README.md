# Adopt a Pet!

## Codecademy Project

In this project, you will have the opportunity to practice using React Router to add client-side routing to a React Application. Specifically, you will be building a pet adoption website that allows users to view all the animals of a particular species and view the profiles of specific animals.

Currently, the app renders a <code>HomePage</code> component that fetches and displays all adoptable pets (you can view the code for this page in **src/pages/home/index.js**). We have also built a <code>PetDetailsPage</code> to display the details for a particular pet (**src/pages/detail/index.js**), but this component will not render until you create a route to display it.

Your objective will be to add client-side routing to the application using React Router so that:

- The <code>HomePage</code> component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.
- The <code>PetDetailsPage</code> page displays when the browser’s current URL includes a specific pet’s <code>id</code>.
- The <code>PetDetailsPage</code> displays data for the correct pet based on the <code>id</code> in the URL parameters’ values.
- When the user searches for a pet in the search bar, they are redirected to the <code>SearchPage</code>, which uses the query parameter called name to filter pets by <code>name</code>.
- When a user clicks a pet whose details are not available, they are redirected to a <code>PetNotFoundPage</code>.
- From the <code>PetNotFound</code> page, users can click “Go Home” button that will take them to the root path page.

Before you get started, spend some time familiarizing yourself with the project’s starting code. In particular, in the src/ folder, take note of the components that you’ll be primarily working with:

- **src/App.js** (<code>App</code>)
- **src/pages/home/index.js** (<code>HomePage</code>)
- **src/pages/detail/index.js** (<code>PetDetailsPage</code>)
- **src/pages/search/index.js** (<code>SearchPage</code>)
- **src/pages/petNotFound/index.js** (<code>PetDetailsNotFound</code>)