- **Effective date:** 4 October 2026 (version 1.4); the policy for earlier versions was dated 17 September 2026
- **Last updated:** 4 October 2026
- **App:** ConfPulse for iOS (`com.valenso.confpulse`)
- **Provider:** Valentin Ranshakov ("we", "us")
- **Contact:** valentin.ranshakov@gmail.com

ConfPulse shows a curated list of developer conferences, their schedules, and the speakers
giving the talks. This policy explains what the app does with your data, and what it shows
about the people who speak.

The short version: **ConfPulse has no accounts, collects nothing about you, and sends us
nothing. There is no analytics SDK, no advertising identifier, and no server we operate.**
Some features open pages run by other services (Apple Maps, Google Calendar, a speaker's
newsletter); section 3 says exactly which, and what each one receives.

---

## 1. What ConfPulse collects about you

**Nothing.**

There are no user accounts, no sign-in, and no profile. The app does not ask for or receive
your name, phone number, contacts, photos, calendar contents, location, or advertising
identifier. It contains no analytics, attribution, crash-reporting, or advertising SDK.

We do not receive any data from the app, because there is no server of ours for it to send
data to.

The one thing you can type into the app is an email address, in the newsletter box on a
speaker's page, and only if you choose to subscribe. **We never receive or store it**: it is
handed straight to the speaker's own newsletter page (section 3, "Newsletters").

---

## 2. Information about speakers

The app shows information about the people who speak at conferences: a **name**, and, for
many, a **photo**, a **job title and company**, a **short biography**, **links** to their
public profiles (for example GitHub, X, LinkedIn, a website), and the **talks** they give.

This information comes from two public sources:

- **Profiles that speakers publish themselves.** A speaker adds their own profile to a public
  repository, [`valenso/confpulse-speakers`](https://github.com/valenso/confpulse-speakers),
  and is the only person who can change it. They decide what it contains.
- **Profiles made from a conference's published programme.** When a conference's own website
  lists a speaker who has no profile yet, we create one containing **only the name** (and a
  job title and company only if the conference's site states them). We add no photo,
  biography, or links. The app marks such a profile as unclaimed and does not show a GitHub
  photo or link for it.

Talk titles, times, and rooms come from the conference's published programme.

**Claiming, correcting, and removing.** If you are listed and want to take over your profile,
see [Claim your profile](https://github.com/valenso/confpulse-speakers#claim-your-profile).
If you want something corrected or your profile removed, email **valentin.ranshakov@gmail.com**
and we will do so promptly. A removed profile disappears from the app on its next refresh.
Because the repository is public, a copy of an earlier version may still exist in its
history or in a cache outside our control.

For people in the EU or UK: we publish this information on the basis of our legitimate
interest in providing a directory of publicly announced conference programmes, and you have
the rights in section 6.

---

## 3. Network connections the app makes

ConfPulse makes network requests only to display content. As with any internet request, the
service that answers it receives your device's IP address and standard request metadata, and
its own privacy policy governs what it does with them. We send none of these services
anything about you.

**Content the app downloads**

- **GitHub** (`api.github.com`) — the conference list and the session schedules the app
  displays. These are read-only requests for data files.
- **GitHub Pages** (`valenso.github.io`) — the speaker directory, a single public file.
- **GitHub avatars** (`github.com`, served from `avatars.githubusercontent.com`) — the photo
  of a speaker whose profile has no photo of its own, for speakers whose profile id is their
  own GitHub account. See the
  [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement).
- **Images hosted elsewhere** — a conference's icon, or a speaker's photo, is fetched from
  wherever its owner hosts it, and that host sees your IP address.
- **Conference websites** — when you open a conference, the app may fetch that conference's own
  home page, only to find its icon. Nothing about you is sent beyond the request itself.

**Maps**

- **Apple Maps** — the venue map on a conference page, and the map of conference cities on a
  speaker's page, use Apple's MapKit. The app asks Apple to look up a venue's address, and
  Apple handles that under its own
  [privacy policy](https://www.apple.com/legal/privacy/). The app does not use your location.

**Calendars** ("Add to Calendar" on a conference page; the app never reads your calendars)

- **Apple Calendar** — opens the system's event editor with the conference's name, dates, and
  place filled in. You save it there; the app does not receive anything back.
- **Google Calendar** — opens Google's own "add event" page in an in-app browser with the
  conference's name, dates, and place. Google's privacy policy applies from there.
- **Other Calendar App** — hands a calendar file to the app you pick in the share sheet.

**Newsletters** (only if a speaker has one, and only if you tap Subscribe)

- If a speaker publishes a newsletter, their page offers a box for your email address. When
  you tap Subscribe, the app opens that newsletter's own subscribe page (currently on
  Substack) in an in-app browser, with the address you typed in the page's address. You
  finish subscribing there. **The app does not send the address anywhere itself, and does not
  keep it.** Substack and the newsletter's author handle it under
  [Substack's privacy policy](https://substack.com/privacy).

**Links that leave the app**

Tapping a conference's **Visit** link, a speaker's profile links, or a talk's **Slides** or
**Recording** opens that page in your browser or an in-app browser. Once you are there, that
site's own privacy policy applies; we have no involvement in what it does.

---

## 4. What ConfPulse stores on your device

| Data | What it is |
| --- | --- |
| **Cached conference list, schedules, and speaker directory** | Copies of the data the app last downloaded, saved to the app's private cache so it opens instantly and still works offline. |
| **Saved conferences** | The list of conferences you chose to save (their identifiers only), kept in the app's private storage. It is used only inside the app and is never sent anywhere. |

The cached data is the public conference and speaker information the app displays; it holds
nothing about you. Both items are removed when you delete the app.

---

## 5. Tracking

ConfPulse does **not** track you. It does not collect data for advertising, does not build a
profile of you, and does not share, sell, or disclose any personal information about you,
because it does not collect any in the first place. No App Tracking Transparency prompt
appears because the app has nothing to ask permission for.

---

## 6. Children and your rights

ConfPulse is not directed at children and collects no personal information from anyone,
including children under 13.

Since the app holds no data about you, there is nothing for us to provide, correct, export,
or delete about *you as a user*; everything it stores is local to your device and removed
when you delete the app. If you are a **speaker**, the information in section 2 is about you,
and you can ask us to show you what we hold, correct it, or remove it, using the contact
below. If you are in the EU or UK you may also lodge a complaint with your local data
protection authority.

---

## 7. Changes to this policy

If this policy changes, the updated version is published at this URL and the "Last updated"
date above changes with it. Material changes will be reflected before or alongside the app
update that causes them.

---

## 8. Contact

Questions about this policy, or requests about a speaker profile: **valentin.ranshakov@gmail.com**
