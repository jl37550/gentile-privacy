# Privacy Policy — Gentilé

_Last updated: {{PUBLICATION_DATE, e.g. 13 May 2026}}_

This policy describes how the **Gentilé** application ("the app"), published
by **{{PUBLISHER_NAME}}** ("we"), processes your data when you use it on an
Android device through the Google Play Store.

The app is designed to work **without a user account, without sign-up and
without any publisher-side server**. Virtually all data stays on your device.

---

## 1. Data processed locally (on your device)

| Data | Purpose | Storage | Retention |
|---|---|---|---|
| Score history (game mode, score, date, player names in multiplayer, rounds played) | Display the "Scores" screen and compute your statistics | Local Room database (`score_history`) | Until you tap "Clear history" or uninstall the app |
| Game configuration (mode, round count, players, zone) | Start a game from the setup screen | In-memory only | Cleared at the end of the session |
| Completed-games counter | Pace the display of interstitial ads | SharedPreferences (`ads_prefs`) | Until uninstall |
| Approximate or precise GPS position | Recenter the map on your location, only if you enable the "Locate me" button | In-memory only | Cleared as soon as the feature is disabled or the app is closed |

**None of this data is transmitted to our servers** (we don't have any).

---

## 2. Data processed by third parties

The app calls several third-party services to display content. Each applies
its own privacy policy.

### 2.1. Google Mobile Ads (AdMob)
- **Operator**: Google Ireland Ltd / Google LLC
- **Data collected**: Android Advertising ID (AAID), technical device info
  (model, OS, language), interactions with the ads, approximate location
  (derived from IP) for targeting.
- **Purpose**: display an interstitial ad between games.
- **Policy**: https://policies.google.com/technologies/ads
- **GDPR consent**: if you are in the EU, a Google UMP consent banner is
  shown on first launch so you can accept or refuse advertising
  cookies/identifiers.

### 2.2. Wikimedia Foundation (Wikipedia, Wikimedia Commons, Wikidata)
- **Operator**: Wikimedia Foundation, Inc.
- **Data exchanged**: your IP address and an application user-agent, when
  loading photos and Wikipedia pages.
- **Purpose**: display photo galleries (monuments, museums, municipalities)
  and related information.
- **Policy**: https://foundation.wikimedia.org/wiki/Privacy_policy

### 2.3. Map tile provider (CARTO / OpenFreeMap)
- **Data exchanged**: your IP address, the coordinates of the requested
  tiles (= the area you look at on the map).
- **Purpose**: render the basemap.
- **CARTO policy**: https://carto.com/privacy/

---

## 3. Android permissions requested

| Permission | Why |
|---|---|
| `INTERNET` | Load Wikimedia photos, map tiles and AdMob ads |
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Only if you tap the "Locate me" button in the Explore screen. The position is used locally to recenter the map. |

No other sensitive permission (camera, microphone, contacts, storage…) is
requested.

---

## 4. Data shown without collection

The app displays public data from open sources, **fetched on demand** and
**not combined with your personal data**:
- `data.gouv.fr` (Etalab Open License 2.0) — French municipalities' gentilés,
  historical monuments, Museums of France, "Maisons des Illustres", European
  heritage label, remarkable gardens, contemporary architecture, live
  performance, regional natural parks, national parks;
- `github.com/gregoiredavid/france-geojson` (MIT, underlying IGN data under
  Open License) — administrative boundaries for regions / departments /
  municipalities;
- Wikimedia photos (CC BY-SA, CC BY, public domain) with mandatory author
  and license credit shown in every photo carousel.

---

## 5. Your rights (GDPR)

Because the app does not build any user profile on our side, your GDPR
rights apply as follows:

- **Right to erasure**: "Clear history" button in the Scores screen, or
  uninstall the app (wipes everything, including the games counter).
- **Right of access / rectification**: all data is visible in the Scores
  screen; you can change it indirectly by clearing and replaying.
- **AdMob data**: to exercise your rights regarding data collected by
  Google, see your Google account dashboard and the
  [Google privacy policy](https://policies.google.com/privacy).
- **Complaint**: you may file a complaint with the
  [CNIL](https://www.cnil.fr/en/home) (French data-protection authority) or
  the supervisory authority of your country.

---

## 6. Minors

The app does not require sign-up, builds no profile and collects no
identifying data. Ads served by AdMob are, by contract, compliant with the
rules for general audiences; if you believe the app is used by a minor,
decline the AdMob consent on first launch to disable ad targeting.

---

## 7. Transfers outside the EU

We do not transfer data outside the EU — we don't collect any. Third parties
(Google, Wikimedia, CARTO) may host servers outside the EU; each applies
its own transfer safeguards (EU Standard Contractual Clauses).

---

## 8. Changes to this policy

We may update this policy to reflect technical or regulatory changes. The
"Last updated" date at the top of this document tracks the changes.
Previous versions are available in the git history of the repository
{{REPO_URL, optional}}.

---

## 9. Contact

For any question about this policy or your data:

**{{PUBLISHER_NAME}}**
{{POSTAL_ADDRESS, optional for an individual}}
Email: **{{CONTACT_EMAIL}}**
