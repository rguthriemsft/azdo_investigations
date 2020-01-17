# PR Triggers

- PR triggers will fire for these branches once the pipeline YAML file has reached that branch. For example, if you add master in a topic branch, PRs to master will not start automatically building. When the changes from the topic branch are merged into master, then the trigger will be fully configured.

- If no pr triggers appear in your YAML file, pull request builds are automatically enabled for all branches, as if you wrote the following pr trigger. This configuration triggers a build when any pull request is created, and when commits come into the source branch of any active pull request.
