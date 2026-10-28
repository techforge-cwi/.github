# Security

## Committed a password, API key, or token by accident?

1. **Tell an officer right away** on Discord. It happens to everyone, and nobody's in trouble.
2. **Revoke or regenerate the key** on the site that issued it. Deleting the file or the commit doesn't help, because the key stays in the git history and bots scan GitHub for them within minutes.
3. An officer will help clean up the repo.

To prevent it, keep secrets in a `.env` file and make sure `.gitignore` lists `.env`.

## Found a security problem in a TechForge project?

Please **don't open a public issue**. Message an officer on Discord with what you found and how to reproduce it.
