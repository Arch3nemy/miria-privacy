---
title: Miria Privacy Policy
---

# Miria Privacy Policy

**Last updated: 21 September 2026**

Miria is a wishlist and gift-coordination service. This policy explains what
information Miria uses, why it is needed, and who can see it.

## Who we are

Miria is made and operated by **FOP Chernukhin Ivan Serhiiovych** (ФОП Чернухін
Іван Сергійович), trading as **Alacrity**, Kyiv, Ukraine.

Contact: **[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)**

## The short version

Miria has no advertising, analytics or tracking pixels, and does not sell
personal information. List owners need an account; people opening a shared list
do not. Friends can coordinate reservations or pooled gifts, but the list owner
sees only how many gifts are taken — never which gifts, names, pledges or
amounts. Miria coordinates a pooled gift but never receives or processes money.

## If you make a list

Miria stores:

- your email address, used to sign in without a password
- whether the address has been verified
- the display name you choose, which is shown on lists you share
- your lists, including their names, occasions and archive status
- gifts and wishes, including titles, notes, prices, currency, product links,
  positions and copied product images
- the groups and private sharing links you create for a list

If you sign in with Google, Google provides your email address, name, profile
image, provider account identifier and the authentication tokens needed to keep
that connection working. Miria does not receive access to your Gmail, contacts,
Drive or other Google account information. Google sign-in is optional; email
magic links are available instead.

**Why:** to provide the service you ask for and keep your account secure. The
legal basis is performance of our contract with you (Article 6(1)(b) GDPR) and
our legitimate interest in protecting the service (Article 6(1)(f) GDPR).

## If you open a shared list

You can read a shared list without an account. To reserve a gift, organise a
pooled gift or pledge an amount, you first provide a display name. Miria stores:

- that display name
- which group you joined
- reservations you make and release
- pooled gifts you organise or close
- pledge amounts and their currency, including later changes or withdrawals
- a hash of a random guest secret kept by your browser or app

The random secret lets Miria recognise you again without asking you to make an
account. Only its SHA-256 hash is stored on the server; the original secret stays
on your device.

### Who sees gift coordination

People in the same group can see who reserved a gift and the names and amounts
within that group's pooled gifts. People in other groups only see that the gift
is unavailable.

**The owner of the list never receives reservation identities, gift identities,
pool organisers, pledge names or pledge amounts.** The owner receives only an
aggregate count of gifts that are taken. This separation is enforced in the
application's access layer and covered by automated tests.

A pledge is only a statement of intent between the people in the group. Miria
does not collect money, connect payment accounts, or learn whether anyone paid.

**Why:** to provide the coordination requested by the group while preserving
the surprise for the list owner. The legal basis is performance of the service
requested by you (Article 6(1)(b) GDPR).

## Product links and images

When an owner adds a product URL, Miria's server visits that page to read public
product details such as its title, image and price. The shop sees a request from
Miria's server, not from each friend who later views the list.

Miria stores its own processed copy of the product image. Shared-list pages load
that copy from Miria, so opening a list does not tell the shop who viewed it.

## Sessions, cookies and service protection

For signed-in owners, Miria stores a session with an expiry time and may retain
the IP address and browser user agent associated with it. A normal session lasts
30 days. A magic sign-in link lasts 15 minutes, works once, and is stored in a
hashed form. A short-lived token used to hand a session to the mobile app lasts
three minutes.

Miria uses first-party cookies or equivalent app storage for:

- the owner's signed-in session
- a guest secret for each shared list the person joins
- the selected light or dark appearance

There are no advertising or analytics cookies.

Short-lived rate-limit counters protect sign-in, joining and reservation
endpoints from abuse. They are keyed by a SHA-256 hash of an email address or IP
address rather than the address itself and expire within minutes.

**Why:** authentication, fraud prevention and service security. The legal basis
is our legitimate interest in operating a safe and dependable service (Article
6(1)(f) GDPR).

## Service providers and where data is processed

Miria uses a small number of providers acting on our instructions:

- **Neon**, for the PostgreSQL database in Frankfurt, Germany
- **Vercel**, for hosting the website and API in Frankfurt, Germany
- **Google**, for optional Google sign-in and delivery of sign-in email

These providers may process limited technical request information needed to
deliver and protect their services. Miria's own error reports use route patterns
rather than real shared-list URLs and do not include email addresses, session
headers or guest secrets.

Links to another website — for example, a shop — are governed by that site's
own privacy policy after you choose to open them.

## How long information is kept

- Lists and gifts remain until the owner deletes them. Archiving a list hides it
  but does not delete it.
- Reservations, groups, pooled gifts and pledges remain while needed for the
  associated list, including records marked as released, closed or withdrawn.
- Sign-in links and rate-limit counters expire automatically as described above.
- Sessions expire after 30 days unless ended earlier.
- A sharing link stops working when its owner turns it off or replaces it.

## Your choices and rights

Depending on where you live, you may have the right to access, correct, export
or delete personal information about you, restrict or object to processing, and
complain to your local data protection authority.

Signed-in owners can permanently remove their account and associated data
immediately from Miria's
**[account-deletion page](https://miria-xi.vercel.app/delete-account)**. The
page asks for the account email and requires a recent sign-in before deletion.

Email **[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)** to request a
copy or correction, or when you cannot sign in. Manual requests are answered
within 30 days. We may need to verify that the account or guest identity belongs
to you before acting.

You can also release your own reservations, withdraw your pledges, leave by
clearing the guest data stored on your device, or delete gifts and lists you
own. Clearing a guest secret means Miria can no longer recognise you as that
guest; it does not by itself erase the server record, so email us if you want it
removed.

## Security

Miria uses encrypted HTTPS connections, hashed sign-in and guest tokens,
restricted access rules and rate limits. No internet service can promise
absolute security, but personal information is limited to what the service
needs and is not used for advertising or profiling.

## Children

Miria is not directed to children under 13, and we do not knowingly collect
personal information from them. Contact us if you believe a child has provided
information to Miria.

## Changes

If this policy changes, the new version will be published on this page with a
new date. Material changes will be communicated in the service where practical.

## Contact

**Alacrity / FOP Chernukhin Ivan Serhiiovych**  
Kyiv, Ukraine  
[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)
