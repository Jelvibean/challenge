# Caching Fetching Library

This is a simple project in React that is displays a list of people.
The app is using a simple in-memory cache based on JavaScript’s built-in Map object. It's a lightweight, custom caching solution — not a library

# How to Install

1. Clone the repository
2. Run npm install -> to install all your node_modules and your dependencies.
3. Run npm start to run it locally.
4. Visit http://localhost:3000

# What the application offers:

The application has two different ways to offer the data

1. appWithoutSSRData: Displays a list of people fetched from the API using the useCachingFetch, a custom hook I created. This route will load data in the browser and will only make one call.
   Mostly spent my time buiding the fetch and making sure it functioned!!

2. appWithSSRData: TBD - Stopped to go and set up the readme and the other pieces to the project. I would need more time to figure this part out :(

#What Bells and Whistle the App has currently.

1. I added prettier which automatically formats all supported files in your project
   Its set to rewrites the files with the properly formatted code, fixing indentation, line breaks, and other formatting issues.

2. Added Linting to automatically analyzing your code to identify potential errors, stylistic issues, and code quality problems.

# Personal Note to Manager and Team :)

I come from a Nextjs/React background so honestly I had to take time to understand how this more vanilla project was set up. I may have spent some more alloted time trying to piece it all together.

If I was setting this up for the long use, I would consider installing either Nextjs or using Redux. I guess depending on the need of the project I would decided which is best.

I would consider nextjs because that is where I am comfortable, but not only that, Nextjs provides you a number of areas that would make developing easier for the following reasons:
-Server-Side Rendering (SSR)
-Static Site Generation (SSG)
-Routing out of the box
-API routes
-Better SEO and performance

This project may be a good candidate for that.

If my focus was more state management and not whole application utitilites as noted above then, redux toolkit may be a better choice.

As the project grows I would consider some important features to add as the following:

- Installing Jest and running unit test for each react component.
- We could install Playwriting for end-to-end testing (I personally have not done playwriting testing but my team had assign members to do this part.)
- I would add Stylelint to our app and have it run at the build as well to also check our CSS side of the app.
- Depending on what library we are considering I would install bootstrap or Tailwind for our UI side of the app. Or we may have a custom inhouse library instead.
- Install SASS for our CSS pieces.
- If we use Redux, looking into Toolkit Query would be an option.

I am sure there is more but these are the ones I know from outside of Next and what I have the opportunity to have experience in.

Overall I hope this gives you a picture of my thinking.
Thank you for reviewing!!!
