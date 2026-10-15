# Security policy

This file is the default security policy for every repository in the RostamVPN organisation that does not carry its own.

## Reporting a vulnerability

Write to **sina@redteam.net** with `SECURITY` in the subject line. Please do not open a public issue, discussion or pull request for a vulnerability.

Include what you can of the following:

- the repository and commit, or the app and version, you tested;
- what the issue is and what an attacker gains from it;
- steps or a proof of concept that reproduce it;
- how you would like to be credited, if at all.

## PGP

Public key fingerprint:

```
F6DF BB06 92DE F57F 970B  982E 2966 5CE0 835F ADAC
```

The key is published on [keys.openpgp.org](https://keys.openpgp.org/vks/v1/by-fingerprint/F6DFBB0692DEF57F970B982E29665CE0835FADAC).

Verify identity before transmitting sensitive information. All correspondence may be encrypted.

## What happens next

We confirm the report or ask questions, fix in the open in the affected repository, and name the fix commit in the published audit record where the item appears. Please give us a reasonable window to ship a fix before publishing details.

## Scope

The repositories under [github.com/RostamVPN](https://github.com/RostamVPN). The published penetration test reports for the system are in [sec-audit](https://github.com/RostamVPN/sec-audit); please check whether an item is already listed there as open before reporting it.
