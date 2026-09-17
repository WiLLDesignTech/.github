<!--
  Keep this description concise and public-safe. The review workflow determines
  whether UI evidence is required from the files changed by this PR. A checkbox
  or explanation here cannot waive a required UI gate.
-->

## Change

- What changed and why:
- Related issue or task:
- Validation performed:
- Risk or rollout notes:

## UI evidence

<!--
  Required when this PR changes UI-visible files or behavior. Attach a visible
  before and after screenshot for every affected screen, route, state, or flow.
  Use captions that identify the state and map each image to changed UI paths.
  Update the images and headSha after every push. The bot verifies the current
  commit, attachment URLs, file coverage, and image bytes.
-->

- [ ] This PR has no UI-visible changes. (Context only; the bot decides whether evidence is required.)
- [ ] For UI changes, visible before and after screenshots are attached below for every affected UI path.
- [ ] The screenshot captions and path mappings describe the latest commit.

| State | Screenshot | Caption | Changed UI path(s) |
| --- | --- | --- | --- |
| Before | Attach image here | Before — describe the unchanged state | `path/to/changed-ui-file` |
| After | Attach image here | After — describe the resulting state | `path/to/changed-ui-file` |

<!-- pr-review:image-evidence
{"schemaVersion":1,"headSha":"<40 lowercase hex>","screenshots":[{"url":"<GitHub attachment URL>","caption":"<what changed>","uiPaths":["<changed UI path>"]}]}
-->
