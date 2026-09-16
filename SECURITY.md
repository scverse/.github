# Security Policy

## Reporting a vulnerability

Open the affected repository, go to its **Security** tab and click **Report a vulnerability**.
This creates a draft advisory visible only to you and the maintainers.
Email <core@scverse.org> instead if private reporting is off for that repository, or if the problem spans several packages.
Do not report a suspected vulnerability in a public issue.
Include the affected package and version, and enough detail to reproduce it.

## What to expect

A maintainer will acknowledge your report within two weeks.
If we agree it is a vulnerability, we will fix it in a patch release and publish a GitHub security advisory with a CVE.
We will credit you unless you prefer to stay anonymous, and agree the disclosure date with you.

## Supported versions

Fixes go into a new release of the affected package.
We do not guarantee backporting security fixes to older releases; some maintainers may do so at their discretion.

## Out of scope

Vulnerabilities in dependencies belong upstream.
Tell us anyway if an scverse package pins or vendors an affected version, since that part is ours to fix.
