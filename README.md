# Synthwav Resources

Public resource storage for [Synthwav](https://synthwav.io), including token artwork, advertising assets, and versioned project documentation.

## Repository structure

| Directory | Contents |
| --- | --- |
| [`logos/`](logos/) | Token logos used by Synthwav. Automatically preserved images are stored in `logos/auto/`. |
| [`ads/`](ads/) | Advertising and promotional images used across Synthwav. |
| [`token docs/`](token%20docs/) | Versioned PDF documentation submitted through Token Manager for review. |

## Project documentation

Project editors submit a **PDF of up to 4 MB** through **Token Manager → Project Transparency → Documentation**. The current authorized Authority, Delegate, or Steward must submit it for a claimed token.

Each uploaded PDF is saved as a separate file in `token docs/`. Synthwav records its SHA-256 content hash and links to the exact GitHub commit containing that version. The upload process never overwrites a previously saved PDF.

Documentation requires Admin review before it appears as an approved Project Docs link in the public Token Insight Profile (TIP). A replacement PDF creates a new pending review; approval does not carry over to changed content. Re-uploading an identical pending or approved PDF retains its existing review state. Administrators can reject a submission or revoke approval with a reason.

**A file being present in this public repository does not mean it is approved.** Pending, rejected, revoked, and older versions may remain here. Check the token's current TIP on Synthwav for its active documentation status.

Approval applies only to the reviewed PDF version. It is not an endorsement of the project or a guarantee of token safety. Always do your own research, and never connect your wallet or sign transactions just to read documentation.

## Uploads and updates

Use Synthwav's Token Manager for project-document submissions and replacement files. Repository files and the current approval records serve different purposes: the PDF preserves the submitted content, while Synthwav maintains its review status and history.
