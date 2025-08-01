# JFXGithubClient
A JavaFX Github Client (For Demonstration Purposes Only).

![Banner1](https://github.com/DevTony101/JFXGithubClient/blob/master/banner1.png)

The project uses the [Github API for Java](https://github.com/github-api/github-api). You can use it as soon as you download the project.

## Feautures
The project currently supports the following operations:
- Log in to your GitHub user account
- List all your followers
- List and search through all your repositories (Private and Public)
- Delete a repository (Be careful!)

## Future Improvements
- As shown in the [~~documentation~~ (DEAD LINK)](http://github-api.kohsuke.org/), it's a bad idea to authenticate a user with its password directly, so a future version of the project might try with the Personal Access Token.
- To show the file directory of the project.
- Implement the rest of the GitHub functions.

## Inspiration
The app's design is based on GitHub's actual page. Thanks to the guys at [github-api](https://github.com/github-api) for their well documented API.

## Fork Tasks
- Run this, to see what it can actually do.
- Upgrade it.
- Add PAT token support, but may just work with a PAT as password, a hack used in the past for laggard GitHub consuming cloud services.
- Consider replacing banner, because it looks off to have original author's detasils in it.
- If useful, add features, if not, delete repo.
