## Overview
- This project analyzes GitHub users based in Barcelona with over 100 followers, focusing on their followers, repositories, and other attributes.
- The data was scraped using the GitHub API, targeting users with over 100 followers and their public repositories.
- The analysis uncovered interesting trends, including the influence of hireability on email sharing among developers.
  
## Process
1.Data Scraping:

- Used the GitHub API to collect user data for individuals located in Barcelona with more than 100 followers.
- Fetched up to 500 public repositories for each user, capturing relevant details.

2.Data Storage:

- Stored user information in users.csv with fields such as login, name, company, location, email, hireable status, bio, public repositories count, followers, following, and account creation date.
- Saved repository details in repositories.csv, including the repository owner's login, full name, creation date, star count, watcher count, language, and license details.

## Interesting Facts

- A significant portion of repositories in Barcelona are written in JavaScript but surprisingly PHP is also seen in many repositories.

## Recommendation for Developers

Developers in Barcelona should focus on collaboration in JavaScript-based and Python-based projects to leverage the local expertise and community.
