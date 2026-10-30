# aura-stamper

This is a minimal, note-only repository. Its known root files are `README.md` and `hi.txt`; no application entry point, package manifest, build configuration, output directory, or browser preview procedure is established by those files.

## Review the note

Open `hi.txt` to view or edit the note. Reopen it afterward to compare the content with your intended change. This checks the note itself; it does not verify how a separate application might display it.

## Deployment-readiness checklist

The listed files do not establish a deployable application or deployment process. Treat the items below as recommendations to follow if this repository is later used by a consuming application—not as verified capabilities or results.

- [ ] **Confirm what is being published.** Identify the actual application or process that will use `hi.txt`. Do not assume this repository has a web page, build step, or publishable output.
- [ ] **Check the root and output locations.** For any consuming application, verify its documented project root and the directory it actually produces or serves. This repository does not identify either location.
- [ ] **Check relative references.** If the note or consuming application refers to local assets, confirm that each file exists at the referenced path from the application’s actual root. If files are moved or renamed, update dependent references deliberately.
- [ ] **Review configuration safely.** The known files do not include an environment template or configuration file. If configuration is introduced, document the settings the application actually reads, use placeholders in tracked templates, and keep real secrets and private data out of tracked files. Check ignore rules for local secret-bearing files; do not assume a configuration mechanism already exists.
- [ ] **Review the published result.** After publishing through the actual consuming application, open its real preview or interface and check that it displays the intended note and that local references resolve. No preview address or procedure is established here. If no consuming application is involved, review the final `hi.txt` content instead.

## Troubleshooting

These are diagnostic steps, not reports of known problems:

1. Confirm what you intend to review: `hi.txt` is the note; the listed files establish no browser entry page.
2. If a consuming application displays the note, check that application's actual entry page and the path it uses to locate `hi.txt`.
3. If the consuming page fails to display the note, inspect that application's browser console and Network panel for errors and failed requests.
4. Check that local assets referenced by a consuming application exist at their referenced paths. Treat remote resources separately: they require network access and are not established by this repository's known files.

## Configuration and data handling

Treat `hi.txt` as tracked repository content: do not put passwords, private keys, personal records, or other information that should not be shared in it. Anyone with access to the repository may be able to read tracked content.

If configuration or a preview application is added later, document its actual settings and handling requirements. Keep real secrets out of tracked files; use placeholders in any future template and check ignore rules for local secret-bearing files. Do not infer that a configuration mechanism is already supported.

## Contributing and handoff

Keep changes scoped to the intended note content in `hi.txt`. Preserve the existing filename and any relative references; if a file is moved or renamed, update the references that depend on it. In a handoff, describe what changed and identify the affected file. Do not describe an application preview or rendering result unless one was actually reviewed.

Before publishing, manually review the result. These are actions to perform, not verified results:

- [ ] Review the complete text in `hi.txt`, including relevant whitespace and line breaks.
- [ ] Check that any local image, audio file, or font referenced by the note or a consuming application exists at the referenced path.
- [ ] If assets are added, identify which are actually referenced before removing any. If an external font or script is introduced, confirm it is intentional and describe its purpose in the handoff.
- [ ] Confirm the handoff description matches the final changes and that filenames and relative references remain valid.
- [ ] If a consuming application publishes the note, perform a final preview after publishing and check the actual result; do not claim this was done unless it was.

## If a consuming interface is added

The listed files do not establish a rendered page or interactive controls. If `hi.txt` is displayed in an app or website, review that consuming interface separately:

- Check that controls are keyboard reachable and operable, with visible focus.
- Check that controls have meaningful labels and the note remains readable against its background.
- If images are added, check that informative images have suitable text alternatives and decorative images are handled appropriately.
- If the interface uses motion, check that it respects the user's reduced-motion preference.

## Personalization

For changes to the note's visible content, edit `hi.txt`. No theme, image assets, or application-specific settings are established by the listed files. If you add files or a preview workflow, document their purpose, identify the actual root and output locations if applicable, and preserve relative file references introduced by that change.

## Final release review

- Confirm the documented starting point still matches the files present at the repository root.
- Review the published result once on a narrow screen and once on a wider screen; treat this as a release check, not an automated test report.

## Repository map

- Start with the files listed at the repository root and follow the paths documented above.
