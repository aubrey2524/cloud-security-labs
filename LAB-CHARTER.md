# Lab Charter

- Owner: Enoch Tetteh Quaye (GitHub: aubrey2524)
- Written: 17 October 2026
- Scope: every lab in this repository

## 1. Purpose
I only test systems I own, or systems whose owner has given me written permission.

## 2. Authorised systems (in bounds)

| System | What it is | What I may do |
|---|---|---|
| HP EliteBook 745 G6, Ubuntu Desktop | My laptop (the host) | Run labs on it. Do not break it. |
| Lab VMs in VirtualBox on Ubuntu Desktop | My test servers | Break and rebuild them, after a snapshot |

- Lab VM names and IP addresses: to be filled in after Step 4.

## 3. On my laptop, but not part of the lab
- Windows (dual boot): not a test target.
- Never change disk partitions or the boot menu (GRUB).
- Old Ubuntu Server VM inside Windows: retired. Delete after Step 4.

## 4. Out of bounds (never test)
- School or campus networks and computers
- Friends' and family devices
- MTN, Telecel, or any public Wi-Fi
- Any website, server or IP address I do not own
- The store's live Register and any real customer or debtor data
- My phone (it holds my passwords and important data)

Anything not in section 2 needs written permission from its owner first.

## 5. Credentials
- No passwords, private keys, tokens or .env files in this repository. Ever.
- Lab VMs use lab-only passwords, never my real ones.
- My SSH private key stays in ~/.ssh on my laptop. Only the .pub key is shared.
- My passwords are kept on my phone, never in this repository.

## 6. Snapshots
- Take a snapshot before any risky change.
- Location: VirtualBox default, ~/VirtualBox VMs/<VM name>/Snapshots
- Names: date-what, for example 2026-10-20-clean-install
- Delete old snapshots after each mini-gate. Keep at least 25 GB free on Ubuntu.

## 7. Law (Ghana)
- Electronic Transactions Act, 2008 (Act 772): unauthorised access and interference are offences.
- Cybersecurity Act, 2020 (Act 1038): check Cyber Security Authority licensing before any paid security work.
- These are learning notes, not legal advice.

## 8. If something goes wrong
- In my lab: stop, restore the last snapshot, write down what happened.
- If I ever touch an out-of-bounds system by mistake: stop at once, go no further, and tell the owner.

