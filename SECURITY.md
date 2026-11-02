# Security

How to report a vulnerability in Orcraft, and what happens with the report. The full text is at https://orcraft.app/security/.

## Reporting a vulnerability

Write to support@orcraft.app with "Security" in the subject, or use the private report form of this repository (Security tab, Report a vulnerability). Both reach only us. Please do not publish a vulnerability anywhere before a fix is released.

## What to include

- The product and its version: the controller, the endpoint application, the orcraft package, the website or the account service.
- The steps that reproduce it, and what an attacker gains.
- Anything you already know about the cause or the fix.
- Logs with other people's data removed.

## What happens next

We confirm that the report reached us, investigate it, and tell you what we found. A confirmed vulnerability is fixed in a new release of the orcraft package, or in a change to the website and the account service, and the release notes name it. We credit you in them if you want to be named.

## Scope

In scope: the orcraft package on PyPI (the controller, the endpoint application, the framework and the command line), orcraft.app and the account service behind it.

Out of scope: the services Orcraft is built on (GitHub, Clerk, Supabase, Paddle, PyPI and Zoho, each with its own programme), denial of service, social engineering, findings that need physical access to a machine or an already compromised account, and the test suites you write and run with Orcraft.

## Research in good faith

Use your own account, controller and machines; do not read, change or keep data that is not yours; stop at the proof and go no further; no denial of service and no social engineering. We take no legal action against research that follows these rules, and we do not ask you to stay silent once the fix is out.

## Supported versions

Security fixes ship as a new release of the orcraft package. Keep to the latest release to receive them.
