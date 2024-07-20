+++
title = "You should use GitHub"
date = 2024-07-19
+++

You should use GitHub. Check out the prerequisite blog post called ["You should learn Git"](@/blog/you-should-learn-git.md) if you're interested.

GitHub is a powerful, cloud-based storage solution for Git repositories! Create remote copies of your projects _and_ take advantage of GitHub's killer features. The service is an industry standard in the software scene (and others) for a reason.

I should mention an important distinction: __Git is a software__ that lives on your computer, and __GitHub is a web platform__.

## What is a repository?

I need to define some terms before we get involved.

For starters, a Git repository or _repo_ is any directory that is "Git-enabled." Repos are identified by the `.git/` subdirectory that contains all of Git's generated data. A repository looks like any other project; the only difference lies in Git's ability to detect and record changes to project files.

A _remote repository_ — often shortened to _remote_ — is a version of your repo that is hosted on a different computer, typically on an online service such as GitHub.

<img src="/blog/github-repo.png" alt="image of a GitHub repo" />

> Above: the remote repo for this website! You can find it [here](https://github.com/massivebird/massivebird.github.io) on GitHub.

Local repositories on your computer can be associated with a remote one. This association allows Git to "push" and "pull" changes to/from the remote. More on that in a moment.

## GitHub in a nutshell

I use GitHub to host all of my projects that I don't want to lose. If my hard drive shatters under the [extreme sub-zero temperatures of Vostok, Antarctica](https://wmo.asu.edu/content/world-lowest-temperature), my work is still safely stored on GitHub's servers. The only reason why I don't back up absolutely everything is because I'm lazy; it's dead simple to do.

When I make new changes to my project, I commit them with a `git commit` command, then I run `git push` to send those new changes to the remote. Almost instantly, you can visit the remote in the web browser and see my new changes.

Downloading new changes is just as easy. I like working on both my laptop and PC, and I can easily sync work between the two. After pushing changes from one machine, all I have to do is run `git pull` on the other. Git inspects the remote, detects the new changes, and then applies them to the project. The same project is now identical on both machines.

Git interfaces with GitHub to make data transfers extremely simple. Whether you're downloading entire projects, pushing new changes, or pulling the latest updates, the process is easy, fast, and satisfying.

## GitHub's additional features

GitHub has even more features in store for you. Here are some of my favorites!

### Issues (as in the feature)

GitHub Issues is a project planning feature available on all repos. Within Issues, users can create posts to request features, report bugs, and more. When a post has been resolved — for example, when a bug has been fixed — the post can be flagged as "Closed," reorganizing it separately from unresolved "Open" issues.

Issues is a great place to declare and manage short-term and long-term project goals. Even for small projects, Issues helps me maintain a list of areas to improve on. Issues also decouples project objectives from your source code, which eliminates "TODO" comment clutter.

You can read more about GitHub Issues [here](https://github.com/features/issues).

### Forks

You can _fork_ anyone's GitHub project, creating a copy of the repository under your account. Forked repositories are labeled as such along with a link to the original repo. Forks can be freely modified without affecting the original project, which is great when you want to modify someone else's work.

You can read more about GitHub forks [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

### Pull requests

Pull requests, commonly abbreviated to PRs, enable users to propose project changes. Pull requests are posts just like Issues, so they support discussion threads and categorization.

The average workflow involves creating a fork of a project, committing and pushing changes to your fork, then filing a pull request on the original project repo containing those changes. Your PR might even be approved and merged!

You can read more about GitHub's pull requests [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

## Resources

+ [GitHub Skills](https://skills.github.com/): an official guide to GitHub
