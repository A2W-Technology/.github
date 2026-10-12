# A2W-Technology — GitHub organization setup checklist

## Required for the public organization profile

1. Confirm you have **owner** access to `https://github.com/A2W-Technology`.
2. Create a **public** repository named **`.github`**, owned by **A2W-Technology**, if it does not already exist.
3. Copy this package's `profile/` folder into the root of that `.github` repository. GitHub automatically displays `profile/README.md` on the organization overview page.
4. Copy the root `README.md` and this file for organization maintainers, if desired.
5. Connect the **A2W-Technology** organization to the GitHub app used by ChatGPT if you'd like ChatGPT to commit changes directly. This is separate from permissions on your personal GitHub account.

## Organization About / Profile — suggested values

- **Organization display name:** A2WTech | A to W Digital Solutions
- **Description:** A2WTech builds websites, custom software, web applications and mobile apps for businesses in Sri Lanka and beyond.
- **Website:** https://www.a2wtech.com
- **Location:** Batticaloa, Sri Lanka
- **Public email:** hello@a2wtech.com
- **Company LinkedIn:** https://www.linkedin.com/company/a2wtech
- **Instagram:** https://www.instagram.com/a2w_tech
- **Logo / avatar:** Upload the approved, high-resolution A2WTech logo in organization profile settings. The SVG files here are for README branding, not a replacement for the organization's avatar.

## Recommended organization hygiene

- Require **two-factor authentication** for organization members.
- Give contributors the least privilege they need; keep ownership limited to trusted administrators.
- Define teams for engineering, reviews, and administration when needed.
- Prefer private repositories for client source code, secrets, credentials, and internal systems.
- Enable repository rulesets or branch protection for production branches; require reviews and applicable CI checks.
- Add CODEOWNERS and security policies to actively developed public projects when relevant.
- Use GitHub Secrets for CI credentials; never commit keys, tokens, `.env` files, or customer data.
- Pin up to six **relevant public repositories** on the organization overview once approved public projects exist.
- Optionally add default community health files in the `.github` repository (CONTRIBUTING.md, SECURITY.md, issue templates), once policies are agreed internally.

## Important

The README and SVG assets can be published as provided. Organization display name, avatar, description, verified domains, visibility, organization permissions, and security policies are separate GitHub settings; uploading a README does not update them.

## If A2W-Technology is NOT an organization

If the account is actually a GitHub *user* account named `A2W-Technology`, use the files in `IF_A2W_TECHNOLOGY_IS_A_USER_ACCOUNT/` and follow that folder's `SETUP.md` instead. GitHub user profiles use a public repository named after the username, not `.github/profile/README.md`.
