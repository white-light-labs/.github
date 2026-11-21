# Agent Instructions

## Human Review and Merge Gate

- The user must review and authorize the merge of every pull request. Agents may implement requested changes, create a branch, commit, push, and open or update a pull request when the user authorizes those steps.
- After opening or updating a pull request, stop and give the user its link and a concise summary. Do not submit an approving review, merge or close the pull request, enable auto-merge, or otherwise land changes unless the user explicitly asks to approve or merge that specific pull request.
- Requests such as “proceed,” “continue,” “finish,” “push the changes,” or “open a PR” authorize implementation and PR preparation only; they are not approval to merge.
- Passing checks, a mergeable status, repository settings, available permissions, or approval to merge a different pull request do not count as approval for this pull request.
- If the user explicitly asks to merge a named pull request, that instruction authorizes its merge. Do not submit an approving review on the user's behalf.
- If a pull request is merged automatically or by another actor, report that promptly; do not treat it as standing permission to merge future pull requests.
