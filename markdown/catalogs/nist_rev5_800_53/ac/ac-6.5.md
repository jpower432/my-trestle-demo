---
x-trestle-set-params:
  ac-6.5_prm_1:
    values:
x-trestle-global:
  sort-id: ac-06.05
---

# ac-6.5 - \[Access Control\] Privileged Accounts

## Control Statement

Restrict privileged accounts on the system to {{ insert: param, ac-6.5_prm_1 }}.

## Control guidance

Privileged accounts, including super user accounts, are typically described as system administrator for various types of commercial off-the-shelf operating systems. Restricting privileged accounts to specific personnel or roles prevents day-to-day users from accessing privileged information or privileged functions. Organizations may differentiate in the application of restricting privileged accounts between allowed privileges for local accounts and for domain accounts provided that they retain the ability to control system configurations for key parameters and as otherwise necessary to sufficiently mitigate risk.
