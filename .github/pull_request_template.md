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
Required when the PR changes UI-visible files or behavior. Commit PNGs under
.github/pr-review/evidence/ and include their paths below. The URL is display-only
context; the reviewer reads committed bytes at the exact PR head. Update the
headSha and paths after every push.
-->

- [ ] PR has no UI-visible changes. (Context only; the bot decides whether evidence is required.)
- [ ] UI changes have committed before/after screenshots listed below with display URLs.
- [ ] Screenshot captions and path mappings describe the latest commit.
<!-- Store screenshots at .github/pr-review/evidence/<descriptive-name>.png. Keep the PNGs in this PR. -->

| State | Screenshot | Caption | Changed UI path(s) |
| --- | --- | --- | --- |
| Before | Display URL + `.github/pr-review/evidence/before-<name>.png` | Before — describe unchanged state | `path/to/changed-ui-file` |
| After | Display URL + `.github/pr-review/evidence/after-<name>.png` | After — describe resulting state | `path/to/changed-ui-file` |

<!-- pr-review:image-evidence
{"schemaVersion":1,"headSha":"<40 lowercase hex>","screenshots":[{"path":".github/pr-review/evidence/<name>.png","url":"<GitHub display URL>","caption":"<what changed>","uiPaths":["<changed UI path>"]}]}
-->
