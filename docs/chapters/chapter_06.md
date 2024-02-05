# 6. Data management, data sharing and ethical issues


## 6.1 Licensing 

Licensing is an essential aspect of open-source projects hosted on GitHub, as it defines how others can use, modify, and distribute your project's code. GitHub provides a platform for collaboration, but it's up to the project owner to choose an appropriate license for their project. Here's a step-by-step guide on how to license your project on GitHub:

_Step 1: Choose a License_

Before you can license your project, you need to choose a license that aligns with your project's goals and your preferences for how others can use your code. Common open-source licenses include the MIT License, Apache License 2.0, GNU General Public License (GPL), and many others. You can find a list of licenses and their descriptions on websites like [choosealicense.com](https://choosealicense.com/) and [opensource.org](https://opensource.org/licenses).

_Step 2: Create a License File_

Once you've selected a license, you need to create a file in your project repository that contains the full text of the chosen license. You can name this file "LICENSE" or "LICENSE.txt" and place it in the root directory of your repository.

For example, if you choose the MIT License, the "LICENSE" file might look like this:

MIT License

Copyright (c) [year] [your name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all

copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

_Step 3: Commit and Push the License File_

After creating the license file, commit it to your repository and push the changes to GitHub. This will make the license text accessible to anyone who visits your repository.

```shell

git add LICENSE

git commit -m "Add MIT License"

git push origin main

```

_Step 4: Indicate the License in Your Repository_

To ensure that GitHub correctly recognizes your chosen license, you can specify it in the repository settings:

1. Go to your GitHub repository on the GitHub website.

2. Click on the "Settings" tab.

3. In the left sidebar, click on "Options."

4. Scroll down to the "GitHub" section.

5. Under "License," select the license you've chosen from the dropdown menu.

6. Click "Save" to update your repository settings.

By following these steps, your project is now properly licensed, and others will know how they can use and contribute to your codebase. Always make sure to choose a license that aligns with your project's goals and the level of openness you desire for your code. Additionally, consider including a `LICENSE` badge in your README file to prominently display your project's license.


## 6.2 Citation

Citing GitHub projects is essential when you're referencing or using code or other materials from a repository in your academic, research, or documentation work. Proper citation gives credit to the original authors and helps readers locate the source. Below is an example of how to cite a GitHub project, along with a common citation style (APA) and a modified example for other citation styles like MLA or Chicago.

GitHub Repository Citation Example (APA Style):

Author(s). (Year). Title of the GitHub repository. GitHub. URL

Here's an example:

Smith, J. (2022). Awesome Project: A Collection of Useful Code. GitHub. https://github.com/johnsmith/awesome-project

GitHub Repository Citation Example (MLA Style):

Author(s). "Title of the GitHub repository." GitHub, Year, URL.

Example:

Smith, John. "Awesome Project: A Collection of Useful Code." GitHub, 2022, https://github.com/johnsmith/awesome-project.

GitHub Repository Citation Example (Chicago Style):

Author(s), "Title of the GitHub repository," GitHub, Year, URL.

Example:

Smith, John, "Awesome Project: A Collection of Useful Code," GitHub, 2022, https://github.com/johnsmith/awesome-project.

In these examples:



* Author(s): Include the name(s) of the project owner(s) or contributor(s). If it's an organization, you can use the organization's name.
* Year: Mention the year when you accessed or used the GitHub repository. If the project has a specific release or version, you may want to mention that instead.
* Title of the GitHub repository: Include the name of the GitHub repository as it appears on the repository's main page.
* GitHub: Indicate that the source is from GitHub to clarify the platform.
* URL: Provide the full URL of the GitHub repository. Ensure it's clickable in your document.

Please note that citation styles may vary depending on the guidelines of your institution, publisher, or the specific style guide you are using. Always follow the citation style recommended or required by the organization or publication you are submitting your work to.


## 6.3 Sharing repositories

Sharing GitHub repositories while considering intellectual property (IP) concerns is crucial to protect your work, respect the rights of others, and ensure that you are compliant with GitHub's terms of service. Here are some guidelines on how to share GitHub repositories with IP considerations in mind:

1. Understand Intellectual Property Rights:

   - Before sharing any code on GitHub, make sure you understand intellectual property rights, including copyright, licenses, and patents. Know your rights and responsibilities.

2. Choose the Right License:

   - Select an appropriate open-source license for your project. Common licenses include MIT, Apache 2.0, GNU GPL, and more. The license you choose defines how others can use, modify, and distribute your code. Clearly specify the license in your repository.

3. Respect Third-Party Licenses:

   - If your project includes code, libraries, or assets from third parties, ensure that you comply with their licenses. Check the licenses of any dependencies and follow their requirements.

4. Use License Files:

   - Include a LICENSE file in your repository that contains the full text of the chosen license. This makes it clear to users how they can use your code.

5. Add a NOTICE File:

   - If required by your license, include a NOTICE file to give attribution to contributors and provide any additional information required by the license.

6. Avoid Unauthorized Code:

   - Do not include code or assets in your repository that you do not have the legal right to use. This includes proprietary code or assets without permission.

7. Handle Sensitive Information Carefully:

   - Avoid committing sensitive information, such as API keys, passwords, or personal data, to your repository. Use environment variables or configuration files outside of your repository for such information.

8. Use Private Repositories if Necessary:

   - If your project contains sensitive or proprietary information that should not be public, consider using a private repository on GitHub. Private repositories restrict access to collaborators you invite.

9. Collaborate Transparently:

   - Clearly document your project's contributors and give proper credit to their contributions. Use the GitHub "Contributors" section and include their names in your README or documentation.

10. Maintain a Contributor License Agreement (CLA):

    - If your project is widely used and you want to manage contributions and intellectual property more formally, consider implementing a Contributor License Agreement (CLA). CLAs define the terms under which contributions are made.

11. Regularly Review and Update:

    - Periodically review your project to ensure that it complies with licenses and any legal requirements. Update licenses and dependencies as needed.

12. Seek Legal Advice:

    - If you have complex IP concerns or are unsure about any legal matters, consider seeking legal advice from a qualified attorney experienced in open-source licensing and intellectual property.

By following these guidelines and being mindful of intellectual property considerations, you can safely and responsibly share GitHub repositories while respecting the rights of contributors and third-party dependencies.


## 6.4 Social


### Follow people, organisations:

You can follow people on GitHub to receive notifications about their activity and discover projects in their communities.

When you follow people, you'll see their public activity on your personal dashboard. If someone you follow stars a public repository, GitHub may recommend the repository to you. For more information, see "About your personal dashboard."

You can unfollow someone if you do not wish to see their public activity on GitHub.


    Following a user on GitHub:



* Navigate to the user's profile page.
* Under the user's profile picture, click Follow.

    Unfollowing a user on GitHub:

* Navigate to the user's profile page.
* Under the user's profile picture, click Unfollow.

    Viewing followed users on GitHub:

* Navigate to the user's profile page.
* Under the user's profile picture, click following.

GitHub also provide ways to keep track of users and their activity on the platform. Here's how you can do it:

1. Watch Users' Repositories:

   You can watch repositories created by users you are interested in. When you watch a repository, you'll receive notifications about its activity, including issues, pull requests, and discussions. To watch a repository:

   - Go to the user's repository that you want to watch.

   - Click the "Watch" button at the top-right of the repository page.

  - Choose whether you want to be notified for "All activity," "Releases only," or "Not notified." Select your preference.

2. Star Repositories:

   Starring a repository is a way to bookmark or mark a repository as interesting. While it doesn't directly notify you about the user's activity, it helps you keep track of repositories you find noteworthy. To star a repository:

   - Go to the user's repository that you want to star.

   - Click the "Star" button at the top-right of the repository page.

3. Follow Users on Twitter or Other Social Media:

   Some GitHub users share their activity and updates on social media platforms like Twitter. If you want to keep up with someone's GitHub activity, you can follow them on these external platforms where they may share links to their GitHub repositories and updates.

4. Explore GitHub Activity:

   You can explore GitHub's activity feed, which shows public activity from users you follow or repositories you've starred. This can help you keep track of recent contributions by users you are interested in.

  To access your activity feed, go to your GitHub homepage when you're logged in, and you'll see a feed of recent activity from users and repositories you follow.

Please note that GitHub's features and interface may change over time, so it's a good idea to check the GitHub documentation or the platform itself for any updates or changes in how you can follow or interact with other users. Additionally, GitHub's main focus is on collaboration and open-source projects, so it may not provide the same level of social interaction features as traditional social media platforms.


### Watching the repository

To watch a GitHub repository means to receive notifications and updates about its activity, including new issues, pull requests, comments, and more. It's a way to stay informed about changes happening in repositories you're interested in. Here's how to watch a GitHub repository:

1. Navigate to the Repository:

   Go to the GitHub repository you want to watch. You can do this by entering the repository's URL in your web browser or by searching for the repository on GitHub.

2. Watch the Repository:

   Once you're on the repository page, you'll see a button at the top-right corner labeled "Watch." Click on it.

3. Choose Notification Settings:

   After clicking "Watch," a dropdown menu will appear with options for notification settings. You can select one of the following options:

   - Not watching: This means you won't receive any notifications.

   - Watching: You'll receive notifications for all activity, including issues, pull requests, and more.

   - Custom: You can customize your notification preferences. This allows you to choose which types of events you want to be notified about.

4. Confirm Your Selection:

   Once you've chosen your notification settings, click on the option you prefer. A checkmark will appear next to your selection.

5. Star the Repository (Optional):

   While watching a repository doesn't require you to star it, you might want to do so if you find the repository particularly interesting or useful. Starring a repository is similar to bookmarking it.

   To star a repository, you can click the "Star" button located next to the "Watch" button at the top-right corner of the repository page.

6. Unwatch or Manage Notifications (Optional):

   If you ever want to stop watching a repository or manage your notification settings, you can do so by going to the repository and clicking the "Unwatch" button (which will appear in place of the "Watch" button after you've started watching it). You can also manage your notification settings in your GitHub account settings.

By following these steps, you'll start watching the GitHub repository, and you'll receive notifications based on your chosen notification settings whenever there is activity in that repository. Watching repositories is a great way to stay up-to-date with open-source projects, track issues, and engage with the GitHub community.


### Community support 

Getting community support on GitHub involves engaging with the open-source community to seek help, share knowledge, and collaborate on projects. Here are several ways you can get community support on GitHub:

1. GitHub Discussions:

   - Many repositories have a "Discussions" tab where you can ask questions, share ideas, or seek help from maintainers and the community. You can start or participate in discussions related to the project.

2. Issue Tracker:

   - If you encounter a bug or have a specific problem with a project, check the project's issue tracker. Often, there are existing issues or bug reports that can help you find solutions or workarounds. You can also open a new issue to report problems or request assistance.

3. Contribute to Open-Source Projects:

   - Actively participating in open-source projects can help you build relationships with maintainers and other contributors. By contributing code, documentation, or bug fixes, you can become part of the community and receive support from experienced contributors.

4. Read the Documentation:

   - Always start by reading the project's documentation. Many common questions are answered in project documentation, including installation instructions, configuration details, and usage guidelines.

5. Stack Overflow:

   - Sometimes, GitHub projects have a presence on Stack Overflow. You can search for questions related to the project using the project's name as a tag and find answers or ask your own questions.

6. GitHub Discussions in Related Organizations:

   - If a project doesn't have a dedicated "Discussions" section, it may be part of a larger organization or community. Check the organization's or community's GitHub repository or forum for relevant discussions and support.

7. Twitter and Social Media:

   - Some open-source maintainers and projects share updates and interact with the community on Twitter and other social media platforms. Following these accounts can keep you informed and provide opportunities to engage.

8. Meetups and Conferences:

   - Some open-source communities organize virtual or in-person meetups and conferences. Attending these events can help you connect with maintainers and other community members.

9. GitHub Actions and CI/CD Workflows:

   - If you're having trouble with CI/CD workflows or GitHub Actions, consult the GitHub Actions documentation, and consider asking questions on the GitHub Community Forum's Actions category.

10. GitHub Community Forum:

    - The [GitHub Community Forum](https://github.community/) is a place where GitHub users discuss various topics related to GitHub. You can ask questions, share knowledge, and connect with other users.

11. Documentation Feedback:

    - If you find issues or inaccuracies in a project's documentation, consider opening a documentation-related issue in the project's repository. This helps improve the documentation for everyone.

When seeking community support on GitHub, remember to be respectful, provide clear information about your issue or question, and follow any guidelines or codes of conduct set by the project maintainers and the community. Your active and constructive participation in the community can lead to valuable connections and a positive experience.


### Exploring projects

Exploring GitHub projects is a great way to discover interesting open-source repositories, contribute to existing projects, or find solutions to coding challenges. Here's how you can explore GitHub projects:

1. GitHub Explore Page:

   The GitHub Explore page is a curated collection of repositories and topics. You can access it by going to https://github.com/explore. Here, you'll find various categories and topics to explore, such as trending repositories, programming languages, and more.

2. GitHub Search:

   Use GitHub's search bar to find repositories based on keywords, topics, or user accounts. You can enter specific search queries like "JavaScript frameworks," "machine learning," or "web development" to find relevant projects.

   - To search for repositories, go to the GitHub homepage (https://github.com/) and enter your query in the search bar at the top.

3. Browse GitHub Topics:

   GitHub has a Topics feature that allows repository owners to add relevant topics to their projects. You can browse these topics to find repositories related to specific areas of interest.

   - To browse topics, go to https://github.com/topics and select a topic that interests you.

4. GitHub Collections:

   GitHub Collections are themed collections of repositories created by GitHub. These collections often include repositories that are grouped by subject or purpose, making it easier to discover projects.

   - To access GitHub Collections, visit https://github.com/collections.

5. Explore GitHub Trending:

   GitHub Trending showcases the most popular repositories and projects on GitHub for a specific timeframe (daily, weekly, or monthly). This is a great way to discover what's currently trending in the open-source community.

   - To view GitHub Trending, go to https://github.com/trending.

6. Use GitHub's Advanced Search:

   GitHub offers an advanced search feature that allows you to filter repositories based on various criteria, such as stars, forks, programming languages, and more. You can access it by clicking "Advanced search" next to the search bar on the GitHub homepage.

7. GitHub Topics in Repositories:

   When you visit a repository on GitHub, you can explore the topics associated with it. These topics can provide additional context about the project and related technologies.

8. Follow Users and Organizations:

   Consider following GitHub users and organizations whose projects interest you. Their activity and repositories will appear in your GitHub feed, making it easier to discover new projects.

9. GitHub Discussions and README Files:

   Explore the "Discussions" tab and the README file of repositories. These sections often contain valuable information about the project's goals, how to get started, and potential ways to contribute.

10. Participate in Open Source Events:

    Join open-source events such as Hacktoberfest or specific community events organized around a programming language or technology. These events often promote collaboration and can help you discover interesting projects.

Remember that GitHub is a vast platform with millions of repositories covering a wide range of topics and technologies. Take your time to explore, read documentation, and engage with the community to find the projects that align with your interests and goals.