- `branch_protection_rule`: Runs whenever one of your [branch protection rules](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) are changed. You can have it run when a rule is `created`, `changed`, or `deleted`.
- `check_run`: Runs whenever a [check](https://docs.github.com/en/rest/guides/getting-started-with-the-checks-api) occurs.
- `check_suite`:
- `create`: Runs whenever some creates a branch or tag in your respository on Github.
- `delete`:
- `deployment`:
- `deployment_status`:
- `discussion`:
- `discussion_comment`:
- `fork`: Runs whenever someone forks your repository.
- `gollum`: Runs whenever someone updates a page on the \[repository's Wiki\]([About wikis](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis). (I don't make the rules here.)
- `issue_comment`:
- `issues`:
- `label`:
- `merge_group`:
- `milestone`:
- `page_build`:
- `project`:
- `project_card`:
- `project_column`:
- `public`: Runs whenever your repository changes from private to public.
- `pull_request`:
- `pull_request_comment`:
- `pull_request_review`:
- `pull_request_review_comment`:
- `pull_request_target`:
- `push`: Runs whenever a commit or tag is pushed to the repo.
- `registry_package`:
- `release`:
- `repository_dispatch`:
- `schedule`: Runs a workflow regularly on a schedule that you define.
- `status`:
- `watch`: Runs whenever someone stars your repository.
- `workflow_call`:
- `workflow_dispatch`:
- `workflow_run`: