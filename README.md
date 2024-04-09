# workflows

* `workflow_call` is used to make a workflow callable from another workflow. When a workflow has this event in it, it is considered reusable. When called from another workflow, it will get the full event payload from the calling workflow.
* `workflow_dispatch` provides a way to manually trigger a workflow. When this
event is present, the workflow can be manually triggered via the GitHub API, the
GitHub CLI, or the Actions browser interface.
* `workflow_run` allows you to trigger execution of a secondary workflow after a
prerequisite workflow has run to completion—whether it succeeded or f
