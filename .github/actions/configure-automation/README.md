# Configure Automation Action

This action will be responsible for reading the `.github/automation.yml` file in a repository and making an API call to the central automation server to trigger a specific workflow.

For example, it could be used in a scheduled workflow to run stale issue checks.

It will require inputs such as the workflow to trigger (e.g., `stale-issue-check`) and any necessary context.
here 