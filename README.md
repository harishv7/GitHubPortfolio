# GitHubPortfolio

This is a React-based application that fetches all your public repositories and curates them into a nice webpage for you.

To see an example, visit: http://harishv7.github.io/portfolio

To preview your own GitHub portfolio, visit: http://harishv7.github.io/portfolio/?name=YOUR_GITHUB_USERNAME_GOES_HERE. Basically add your github username as a query parameter and it will fetch the repo details from your account.

To use this and generate your own portfolio page, you can download this repository, and under client/js/app.jsx, specify your username in the first line.
Example: ```var gitHubUserName = "octocat";```

Subsequently, you can test out this page using ```node index.js``` from the root repo dir.
