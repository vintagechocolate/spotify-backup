# Repository instructions

## Branch policy

- Use `main` as the default and publishing branch on both GitLab and GitHub, and as the primary local working branch.
- Never create or publish a branch named `master`.
- Before publishing, verify the destination repository and explicitly target `main`: `git push <remote> HEAD:main`.
- Keep both hosting services' default branches set to `main` and use `main` in repository download links.
- GitLab and GitHub currently have separate commit histories. Fetch the destination's `main` and apply the requested changes on top of that history; do not force-push one host's history over the other.
