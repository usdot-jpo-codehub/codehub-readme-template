Contributing to README Template

We welcome your contributions to README Template. This doc describes the process to contribute patches to README Template and the general guidelines we expect contributors to follow.
Before You Start

We accept patches in the form of github pull requests. If you are new to github, please read How to create github pull requests first.
Contributor License Agreements

Contributions to this project must be accompanied by a Contributor License Agreement. You (or your employer) retain the copyright to your contribution, this simply gives us permission to use and redistribute your contributions as part of the project.
If you are an individual writing original source code and you're sure you own the intellectual property, then you'll need to sign an individual CLA.
If you work for a company that wants to allow you to contribute your work, then you'll need to sign a corporate CLA.
Contributing Process

Most pull requests should go to the master branch and the change will be included in the next major/minor version release (e.g., 3.6.0 release). If you need to include a bug fix in a patch release (e.g., 3.5.2), make sure it’s already merged to master, and then create a pull request cherry-picking the commits from master branch to the release branch (e.g., branch 3.5.x).
For each pull request, a Public Access Implementation and Support team member will be assigned to review the pull request. For minor cleanups, the pull request may be merged right away after an initial review. For larger changes, you will likely receive multiple rounds of comments and it may take some time to complete. We will try to keep our response time within 7-days but if you don’t get any response in a few days, feel free to comment on the threads to get our attention. We also expect you to respond to our comments within a reasonable amount of time. If we don’t hear from you for 2 weeks or longer, we may close the pull request. You can still send the pull request again once you have time to work on it.
Once a pull request is merged, we will take care of the rest and get it into the final release.
Pull Request Guidelines

Create small PRs that are narrowly focused on addressing a single concern. We often receive PRs that are trying to fix several things at a time, but if only one fix is considered acceptable, nothing gets merged and both author's & review's time is wasted. Create more PRs to address different concerns and everyone will be happy.
For speculative changes, consider opening an issue and discussing it first. 

Provide a good PR description as a record of what change is being made and why it was made. Link to a GitHub issue if it exists.
Don't fix style and formatting unless you are already changing that line to address an issue. PRs with irrelevant changes won't be merged. If you do want to fix formatting or style, do that in a separate PR.
Unless your PR is trivial, you should expect there will be reviewer comments that you'll need to address before merging. We expect you to be reasonably responsive to those comments, otherwise the PR will be closed after 2-3 weeks of inactivity.
Maintain clean commit history and use meaningful commit messages. PRs with messy commit history are difficult to review and won't be merged. Use rebase -i upstream/master to curate your commit history and/or to bring in latest changes from master (but avoid rebasing in the middle of a code review).
Keep your PR up to date with upstream/master (if there are merge conflicts, we can't really merge your change).
Reviewer Guidelines

Apply the "release notes: yes" label if the pull request's description should be included in the next release (e.g., any new feature / bug fix). Apply the "release notes: no" label if the pull request's description should not be included in the next release (e.g., refactoring changes that does not change behavior, integration from Google internal, updating tests, etc.).

