# aura-stamper

This is a minimal, note-only repository. Its known root files are `README.md` and `hi.txt`; no application entry point, package manifest, or build configuration is present.

## Review the note

Open `hi.txt` to view or edit the note. Reopen it afterward to compare the content with your intended change. The listed files establish no application preview procedure.

## Troubleshooting

These are diagnostic steps, not reports of known problems:

1. Confirm what you intend to review: `hi.txt` is the note; there is no documented browser entry page in the listed files.
2. If a consuming application displays the note, check that application's actual entry page and the path it uses to locate `hi.txt`. Preserve relative paths when files are moved, and update references deliberately.
3. If the consuming page fails to display the note, inspect that application's browser console and Network panel for errors and failed requests.
4. Check that local assets referenced by a consuming application exist at their referenced paths. Treat remote resources separately: they require network access and are not established by this repository's known files.

## Configuration and data handling

The known files do not include an environment template or configuration file. Treat `hi.txt` as tracked repository content: do not put passwords, private keys, personal records, or other information that should not be shared in it. Anyone with access to the repository may be able to read tracked content.

If configuration or a preview application is added later, document its actual settings and handling requirements. Keep real secrets out of tracked files; use placeholders in any future template and check ignore rules for local secret-bearing files. Do not infer that a configuration mechanism is already supported.

## Contributing and handoff

Keep changes scoped to the intended note content in `hi.txt`. Preserve the existing filename and any relative references; if a file is moved or renamed, update the references that depend on it. In a handoff, describe what changed and identify the affected file. Do not describe an application preview or rendering result unless one was actually reviewed.

Before publishing, manually review the result. These are actions to perform, not verified results:

- Review the complete text in `hi.txt`, including relevant whitespace and line breaks.
- Check that any local image, audio file, or font referenced by the note or a consuming application exists at the referenced path.
- If assets are added, identify which are actually referenced before removing any. If an external font or script is introduced, confirm it is intentional and describe its purpose in the handoff.
- Confirm the handoff description matches the final changes and that filenames and relative references remain valid.

## If a consuming interface is added

The listed files do not establish a rendered page or interactive controls. If `hi.txt` is displayed in an app or website, review that consuming interface separately:

- Check that controls are keyboard reachable and operable, with visible focus.
- Check that controls have meaningful labels and the note remains readable against its background.
- If images are added, check that informative images have suitable text alternatives and decorative images are handled appropriately.
- If the interface uses motion, check that it respects the user's reduced-motion preference.

## Personalization

For changes to the note's visible content, edit `hi.txt`. No theme, image assets, or application-specific settings are established by the listed files. If you add files or a preview workflow, document their purpose and preserve relative file references introduced by that change.