# Privacy Policy for Neon Trails

**Effective Date:** October 3, 2024

Neon Trails ("we", "our", or "us") is an offline-first game. This policy
describes the information handled by the Neon Trails Android application
(the "App").

## 1. Information stored on your device

The App stores settings, local game progress, achievements, replay data, and
local profile statistics on your device using Android DataStore and Room.
Offline matches do not require an account or network connection. You can
remove this local data by clearing the App's storage or uninstalling the App.

## 2. Optional online features

If you sign in or use online multiplayer, the App uses Google Firebase
Authentication, Cloud Firestore, and Realtime Database. These services may
process your Firebase account identifier, display name or profile details,
friend and invite information, game-room identifiers, match state, results,
ratings, leaderboard statistics, and reward/progression data. This
information is used to authenticate players, synchronize rooms, show
multiplayer results, and prevent invalid match updates. Online data is
retained while needed to provide these features and according to the
configuration of the associated Firebase project.

The App does not require online services for local gameplay. If Firebase is
not configured or unavailable, the App falls back to offline behavior.

## 3. Analytics and diagnostics

When Firebase is available, Firebase Analytics may receive gameplay and
feature events such as sign-in, match, achievement, friend, and invite
events. Events can include pseudonymous account or game identifiers and
basic app/device information supplied by the analytics SDK. Analytics is
used to understand feature usage and improve reliability. The App does not
use analytics to sell personal information.

## 4. Notifications

If you sign in and use online multiplayer, Firebase Cloud Messaging may
store a registration token associated with your account so the App can
deliver match and invite notifications. Android notification permission is
optional and can be denied in system settings. The App does not display a
notification when that permission is denied.

## 5. Permissions and device features

* Vibration is used for optional haptic feedback and can be disabled in
  Settings.
* Nearby Bluetooth and Wi-Fi permissions are requested only for the optional
  local-device multiplayer flow. They support discovery and connection to
  nearby players and are not required for offline single-device play.
* Internet and network-state permissions support optional Firebase features
  and Google Play in-app update checks.

The App does not access contacts, photos, microphone, camera, or precise
location for gameplay. Android may associate nearby-device permissions with
location-related controls on some OS versions; Neon Trails does not use
nearby access to track your location.

## 6. Sharing, security, and deletion

Firebase and Google Play services process data as service providers needed
to operate the features described above. Data may be processed on servers
outside your country. We use the access controls supplied by these
services, but no internet transmission can be guaranteed to be completely
secure.

You may stop online collection by signing out and stop local collection by
clearing App storage or uninstalling. To request deletion of online profile,
multiplayer, or analytics-associated data, contact us with the account
identifier or invite/game code needed to locate the data. We will respond
within a reasonable period and may need to retain limited records where
required for security, fraud prevention, or legal obligations.

## 7. Contact

**Email:** support@neontrails.app
