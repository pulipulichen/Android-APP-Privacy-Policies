# Privacy Policy for Share to Clip

**Effective date: September 27, 2026**

Share to Clip is an Android application that lets users save text and web links shared from other apps and synchronize them to a Private Clipping Vault (PCV) server selected and configured by the user.

## Information handled by the app

Share to Clip may handle the following information when you provide or share it:

- PCV server address.
- PCV username and password.
- Text, URLs, titles and notes that you share to the app.
- Local synchronization queue and synchronization history, including timestamps, status messages and HTTP status codes.

## How information is used

This information is used only to provide the app's core functions: connecting to the PCV server you configure, authenticating to that server, saving pending shared items, synchronizing those items, displaying synchronization status and allowing retries.

## Local storage

The current version stores app settings, PCV credentials, queued items and synchronization history locally on the Android device using app-private SharedPreferences. Synchronization history is retained for up to 90 days by the app.

Uninstalling the app normally removes its app-private local data according to Android platform behavior.

## Network transfers

When synchronization or connection testing is requested, Share to Clip sends authentication information and clipping content to the PCV server address configured by the user. The developer does not operate an intermediary Share to Clip cloud service for this transfer.

The app supports both HTTPS and cleartext HTTP because some PCV installations operate on trusted private networks. HTTPS encrypts data in transit and is recommended. If you configure an `http://` server, credentials and clipping content may travel over the network without transport encryption.

The privacy practices of a PCV server are controlled by the operator of that server. Users should review the policies and security practices of any server they choose to configure.

## Third parties, advertising and analytics

The current version does not include advertising SDKs or analytics SDKs and does not sell user data.

Android and Google Play may process ordinary platform or store information independently under their own terms; this policy describes data handling performed by Share to Clip itself.

## Permissions

Share to Clip requests Internet access so it can connect to the PCV server configured by the user. It does not currently request location, contacts, camera, microphone or broad file-storage permissions.

## Children

Share to Clip is a general-purpose productivity utility and is not designed specifically for children.

## Security

The app uses Android app-private storage for its local data. Users are responsible for choosing and securing the PCV server they configure. Use HTTPS when communicating over networks that are not fully trusted.

## Changes to this policy

This policy may be updated when the app's features or data practices change. The effective date above will be revised when material changes are made.

## Contact

For privacy questions, contact:

Pulipuli Chen
Email: pulipuli.chen@gmail.com

---

## Publishing note

Publish this policy at a stable, publicly accessible web URL and enter that URL in Play Console. Keep this source file synchronized with the published version.
