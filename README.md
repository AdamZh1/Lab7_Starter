1. I would pick option 1, as it makes everything consistent and simple for development. Setting up tests in a GitHub action ensures that your code is tested every time you work on new features, and avoids the possibility that you forget to run them locally. Additionally, it makes sure everyone runs the same tests, as everytime any one pushes to the repo, it will run the same tests for everyone.
2. No, I would not use E2E testing to check if a function returns the correct output as that is usually done by Jest, and E2E testing would be inefficient for this task. It is supposed to simulate user actions from start to finish, so using it to check one function would be inefficient. Additionally, it's supposed to test what it sees on screen, rather than the backend of a function.
3. The difference between navigation and snapshot mode is that navigation analyzes a page right after it loads, while snapshot analyzes a page in its current state. Navigation is prioritized for performance metrics, while snapshot mode is prioritized for finding accessibility issues.
4. Based on the Lighthouse results, we can improve performance a little bit by using longer cache lifetimes, as it could speed up revisits to the site. Currently, it is at 10 minutes, so it can be made longer. Additionally, the accessibility can be improved, by adding a [lang] attribute for screen readers. Something to improve Search Engine Optimization would be to write a meta description so that web crawlers better understand the app's content.




