# MFA Sign-In Recovery

**Service Desk Simulator | INC195698 | Critical | Resolved**

## Issue and impact

An Engineering employee could not sign in because the system repeatedly
rejected codes from their authenticator app. Retrying the codes and
restarting the phone did not help. The employee was locked out of company
systems and could not work.

## Resolution

I located the employee's account in the simulator's Directory tool,
opened the Authentication settings, and reset their multifactor
authentication (MFA) enrollment. The employee was able to sign in again,
and the simulator marked the ticket resolved.

## What I learned

Resetting MFA enrollment lets the employee set up their authenticator
again while keeping MFA required. In a production environment, I would
follow the organization's identity verification and approval process
before resetting MFA, then confirm that the employee can sign in with
the newly enrolled authenticator.
