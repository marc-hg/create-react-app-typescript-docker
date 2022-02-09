This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Thanks to Karan Pratap Singh for his guide on dockerizing a react app with dev and prod multi stage builds. https://dev.to/karanpratapsingh/dockerize-your-react-app-4j2e

## How to Run
In the project directory, you can run:

### `docker-compose -f docker-compose.dev.yml up`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `docker-compose -f docker-compose.prod.yml build`
Builds the app for production to a lightweight docker image you can deploy.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

You can launch it like

docker run -d -p 8080:80 my_prod_image

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
