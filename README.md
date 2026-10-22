# RMIT HACKATHON 2026: UNLOCKED
[![Built with TideCloak](https://tide.org/badges/built-with-tidecloak.svg)](https://tide.org/tidecloak?utm_source=github&utm_medium=readme&utm_campaign=unlocked)

## Project T-link:

T-link is a secure, role-based document vault where sensitive company files are encrypted line by line, requiring multi-party quorum approvals to read or rewrite sensitive data.
Built with [TideCloak](https://tide.org/tidecloak?utm_source=github&utm_medium=readme&utm_campaign=unlocked).

### 1. Vision & originality

We’re introducing a granular document security model where files aren't just locked as a whole—instead, individual lines carry different security levels. Traditional access control is often an all-or-nothing affair, but T-link lets organizations securely mix public, staff-only, and executive-only data within the exact same document, backed by multi-role approval workflows.

### 2. Trust constraint insight

Today, sharing sensitive reports usually means stripping out details or trusting people with full documents they only need a peek at. This creates massive data leak risks. When you remove that constraint with line-by-line cryptographic masking and team-based sign-offs, teams can collaborate safely on sensitive files (like payroll or acquisition term sheets) without over-exposing confidential data.

### 3. Value & impact

HR professionals, finance leads, and executives benefit by retaining strict compliance without grinding daily operations to a halt. For instance, an HR manager can look at an employee directory while sensitive home addresses and phone numbers stay sealed until the proper multi-party approvals are unlocked.

### 4. Why TideCloak matters

TideCloak serves as the foundational security layer for T-link by replacing vulnerable password-based logins with passwordless authentication. By establishing tamper-proof user identity and strictly enforcing role assignments TideCloak ensures that multi-party quorum approvals cannot be forged or bypassed. This enables client-side AES-GCM decryption of sensitive document lines only when genuine, cryptographically verified authorizations are granted.
### 5. Prototype & storytelling

The interactive prototype demonstrates a fully functional multi-role workspace featuring six pre-loaded encrypted documents across HR, Finance, and Executive categories. Judges can test the system by logging into different demo accounts to see how visibility levels dynamically adjust permissions in real time. Users can submit access requests for sealed document lines, switch accounts to fulfill required multi-party quorum approvals, and track live updates in the audit log and approval inbox.

## Setup

To run the prototype locally:
1.Clone the repository.
2.Open index.html in your web browser or serve it via a local development server (e.g., npx serve or Live Server).
3.Sign in using any of the built-in demo accounts (password for all is demo1234).
