# Contribute to OncoHub

Thank you for your interest in activity against cancer.</br>
Every contribution is important.</br>
The OncoHub source code is under the [MIT License](LICENSE).
</br>
</br>
Feel free to ask questions on our <a href="https://discord.gg/wEHXKqXKTA" target="_blank">discord</a> channel.

Before contributing please read our code of conduct:
[code of conduct](CODE_OF_CONDUCT.md).

## How can I contribute?

There are many ways how you can contribute.

### social marketing 📣
- follow our <a>Twitter</a> account
- follow our <a>Linkedin</a> account
- tell other friends about us
- if you would like to support us with website SEO or any other marketing activity (text message on <a href="https://discord.gg/wEHXKqXKTA" target="_blank">discord</a> or contact directly to email: oncohub@proton.me)

### coding 💻

You can select a repository that is most interesting for you and start contributing. Just open an issue, or send a pull request on GitHub.

#### road to PR:
1. fork selected repo
2. clone forked project from your GitHub account to your local machine
3. add the original repo to the remote:
`git remote add upstream git@github.com:selected_repo.git`
4. create a new feature branch: 
`git checkout -b feature_branch`
5. make changes
6. linting, black, mypy, etc.: run: `pre-commit run --all-files`
7. testing: in the root directory run: `pytest`
8. `git add -p`
9. `git commit`
10. before opening PR, please rebase your branch upstream (be sure you are on your feature branch):
`git pull --rebase origin dev`
This will pull the latest changes from the dev branch on the remote repository and apply them to your local branch.
11. If there are any conflicts, you will need to resolve them manually.
12. before pushing please squash multiple related commits into one (Pull Request should contain either a single commit, or several unrelated commits)
13. `git push -f origin feature_branch`
14. go to GitHub and 'Compare & pull request'
15. add description
16. create pull requestCONTRIBUTING
17. wait for somebody to review
18. if ok, the maintainer clicks 'Confirm squash and merge'

#### found the bug?
Please open an issue with the following information:
- OS type, Python version
- short description
- screenshots, and code snippets will be helpful

### medical consulting 

If you are a doctor or scientist in the medical domain, you can become our consultant (text message on <a href="https://discord.gg/wEHXKqXKTA" target="_blank">discord</a> or contact directly to email: oncohub@proton.me)
