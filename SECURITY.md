# Portfolio publishing and security

The GitHub Pages site is intentionally public so recruiters and clients can access it without an account.

## Publishing rules
- Keep source recordings, editable project files, customer data, credentials, API keys, private proposals, and unpublished designs in a **separate private repository or private storage**.
- Publish only optimized, approved final media assets in this public repository.
- Verify permission to publish event photos, speaker images, client logos, and third-party footage.
- Before each commit, inspect the changed files for sensitive information.
- Use GitHub's two-factor authentication or passkeys and protect account recovery options.
- Use least-privilege collaborator access and review repository settings for branch protection.
- GitHub Pages on a free personal plan should remain linked to a public publishing repository; changing it to private may interrupt publication.
- Avoid relying on right-click blockers or watermarks as anti-copy security.

## If sensitive material is accidentally published
Immediately revoke or rotate exposed credentials. Removing a file in a new commit does **not** remove it from Git history; follow GitHub's sensitive-data removal guidance and consider all previously exposed material compromised.

## Scope
This file documents recommended operating practices; it does not mean all GitHub account security settings have been enabled automatically.
