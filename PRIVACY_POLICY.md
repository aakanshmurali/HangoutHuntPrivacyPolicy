# Hangout Hunt Privacy Policy

**Last updated: July 9, 2026**

This policy explains what Hangout Hunt collects, why, and what you can do about it. No filler — if something isn't listed here, we don't collect it.

## What we collect

**To create your account:** your email address and password. Your password is handled by our authentication provider (Supabase) and we never see or store it in plain text.

**To personalize suggestions:** whatever you type into your profile — first/last name, gender, city, state, zip code, and your stated interests (hobbies, music, movies/TV, sports/fitness, cuisines). All of this is typed by you; **we do not access your device's GPS or location services**, and the app has no code path that requests location permission.

**Favorite places:** if you add a "favorite place" (like a gym or restaurant you already go to), we send the name you typed to a mapping service (TomTom) to look up its address and coordinates, then store that alongside your profile.

**Group sessions:** if you host or join a group session, we store the room code, the display name you type in (which doesn't have to match your account name), your votes on suggested activities, and the group's final pick. **You can join a group session as a guest without creating an account at all** — in that case we only hold a temporary, randomly generated ID and whatever name you typed for that session.

**AI-generated suggestions:** to generate venue recommendations, we send your city/state, interests, group size, and outing type to Google's Gemini API through our own backend. We do not send your name, email, or account ID to Gemini — it only ever sees the context needed to suggest places, not who you are.

**On your device:** we cache your most recent set of suggested activities locally so the app loads faster, and we keep your login session so you don't have to sign in every time.

## Why we collect it

- Email/password: to create and secure your account
- Profile and interests: to generate relevant activity suggestions
- Zip code/city: to find venues near you (never your precise location)
- Favorite places: to personalize suggestions around places you already like
- Group session data: to run the shared swiping/voting experience and pick a winner
- AI prompt data: to generate the actual list of suggested venues

We don't use any of this for advertising, and we don't run analytics or tracking SDKs of any kind — there's nothing in the app collecting behavioral or usage data beyond what's listed above.

## Who we share it with

We use a small number of service providers to run the app. None of them get more than what they need to do their specific job:

| Provider | What it receives | What it's for |
|---|---|---|
| **Supabase** | Email, password (hashed), profile fields, session/group data | Our database, authentication, and backend hosting |
| **Google Gemini** | City/state, interests, group size, outing type — no name, email, or account ID | Generating venue suggestions |
| **Zippopotam.us** | The zip code you enter | Converting a zip code into a city/state and approximate coordinates |
| **TomTom** | The place name you type under "Favorite Places" | Looking up an address for that place |

We do not sell your data, and we don't share it with advertisers or data brokers.

## Location data

To be direct: **Hangout Hunt does not collect your device's GPS location.** Every location input in the app — zip code, city, state — is typed by you. We use that to estimate a general area (city-level) for finding nearby venues, never a precise, continuously-tracked location.

## How long we keep your data, and deletion

We keep your account and associated data for as long as your account exists. You can permanently delete your account at any time from **Account → Delete Account** in the app — this immediately and permanently removes your profile, favorite places, and session participation records, and deletes your login credentials entirely. This action cannot be undone.

If you'd rather not use the in-app option, email us at **aarushparikh999@gmail.com** and we'll delete your account and data for you.

Group session data (room codes, other members' votes, activity lists) that belongs to a shared group session is not deleted when you delete your account, since it's shared with other participants who may still be using it.

## Your rights

You can:
- **See and edit** your profile info anytime from the Account tab
- **Delete your account and data** anytime from Account → Delete Account, or by emailing us
- **Sign out** at any time, which clears your session from the device
- **Request a copy** of the data we hold on your account by emailing us

If you're in a region with specific data rights (like the EU/UK's GDPR or California's CCPA), these requests are handled the same way — through the app or by emailing us.

## Children's privacy

Hangout Hunt is not directed at children under 13, and we do not knowingly collect information from children under 13. The app's "Family" mode is meant for adults planning outings that include children, not for children to use the app themselves.

## Security

Account data is stored with Supabase, which encrypts data in transit and at rest. No method of storage or transmission is 100% secure, but we don't do anything unusual with your data beyond what's described above — no separate analytics pipeline, no third-party ad SDKs, no background trackers.

## Changes to this policy

If we change what we collect or how we use it, we'll update this page and change the "Last updated" date at the top. If a change is significant, we'll let you know in the app.

## Contact

Questions, data requests, or account deletion requests: **aarushparikh999@gmail.com**
