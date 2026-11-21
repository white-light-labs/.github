# Agent Instructions

## Human Review and Merge Gate

- The user must review every pull request. Andrew's approval of a specific PR for merging authorizes the agent to merge it; use GitHub's Squash and merge by default unless Andrew specifies another method. Agents may implement requested changes, create a branch, commit, push, and open or update a pull request when the user authorizes those steps.
- After opening or updating a pull request, stop and give the user its link and a concise summary. Do not submit an approving review, close the pull request, enable auto-merge, or otherwise land changes before Andrew approves that specific pull request.
- Requests such as “proceed,” “continue,” “finish,” “push the changes,” or “open a PR” authorize implementation and PR preparation only; they are not approval to merge.
- Passing checks, a mergeable status, repository settings, available permissions, or approval to merge a different pull request do not count as approval for this pull request.
- If Andrew approves a pull request as review-only or requests changes, do not merge it. Never submit an approving review on his behalf.
- If a pull request is merged automatically or by another actor, report that promptly; do not treat it as standing permission to merge future pull requests.
