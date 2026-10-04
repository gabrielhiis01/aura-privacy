# Aura Privacy Policy

**Effective date:** October 4, 2026

Aura is a migraine log. This policy is short because the honest answer to
almost every privacy question about your health log is: *we don't collect it.*
Optional weather and purchase processing are described below.

This policy covers Aura 1.2, including optional Aura Plus features. In versions where Aura Plus is unavailable, those Plus features remain locked and purchase processing is inactive.

## Your log lives on your phone

Everything you record in Aura is stored in a local database on your device:
attacks, pain levels, symptoms, medications, check-in answers, notes, and
settings. There is no account, no sign-in, no automatic cloud copy created by Aura, and no server of ours
that holds any of it. We are technically incapable of reading your log. You can explicitly export a copy as described below.

## Personalization (optional)

Your optional first name or nickname and chosen focus are stored in the local database. They personalize the Home greeting and suggested starting point. They are not sent to us or included in PDF or CSV reports. They are included when you explicitly create an encrypted backup. Change or clear them in Settings > Personalization. Delete all data also clears these answers.

## No advertising or app-usage tracking

Aura contains no app-usage analytics, advertising, advertising trackers or
crash reporters. We don't operate a backend, and the app makes no network
requests to us. The optional weather lookup uses the network. Purchase-enabled versions also use Apple and RevenueCat as described under Purchases. Export and backup destinations you choose may use their own network services.

## Weather patterns (optional, off by default)

Aura can compare air pressure changes with your attacks. This is off until you
turn it on in Settings. Weather lookups use the network.

When it is on, Aura asks for your approximate location. It never asks for a
precise one. While the app is open, it sends that approximate location, rounded
to about a kilometre, together with a range of dates to Apple's WeatherKit
service, and receives the air pressure, temperature, and humidity for those
dates. Those numbers are stored on your phone next to your log.

Weather lookups send nothing about your attacks, medications or anything else you log. Aura keeps no history of where you have been: it uses your current
approximate location for each lookup and does not store it. Apple's handling of
these requests is described in Apple's privacy policy.

Turn the feature off at any time in Settings and Aura stops looking up weather.
Delete all data removes the stored weather along with your log.

## Sleep patterns (Aura Plus, optional)

Sleep patterns are an optional Aura Plus feature. They stay off until you turn them on in Settings and allow Aura to read Sleep Analysis from Apple Health.

Aura reads time asleep only. It does not use time in bed and never writes to
Apple Health. It initially reads the last 90 completed days, then refreshes
sleep while the app is open. Aura stores nightly sleep totals and the start
and end times of the sleep used for each night in its local database, to
compare sleep before attacks with sleep before days without an attack.
Raw sleep samples and source identifiers are not retained.

This processing happens on your phone. Aura does not automatically transmit imported sleep or its comparisons or use them for advertising. Imported sleep is included when you explicitly create an encrypted backup. Sleep observations can also be included when you select them for the detailed doctor report. Both are shared only through a destination you choose. Sleep remains excluded from the existing free PDF and CSV exports.
Your device's existing backup settings are unchanged.

Turn sleep patterns off to stop reads and hide the comparison. Previously
imported sleep stays in Aura until you delete it. Delete all data removes
Aura's imported sleep and turns sleep import off. It does not change the
original records in Apple Health or your Health permissions.

## HRV patterns (Aura Plus, optional)

HRV patterns are an optional Aura Plus feature. They stay off until you turn them on in Settings and allow Aura to read heart rate variability (SDNN) from Apple Health. Sleep and HRV are enabled separately. Aura never writes to Apple Health.

Aura initially reads the last 90 completed days from one selected Apple Health source, excluding readings marked as manually entered. It stores daily averages in milliseconds, reading counts, dates, time zones, the selected source identifier and name, and refresh status and timestamps in its local database. Raw readings and sample identifiers are not retained. Source identifiers may identify a recording app or device. They stay in the local database and are included in an encrypted backup you explicitly create.

Aura refreshes while the app is open or when you request a refresh. It periodically reconciles accumulated history within the last 12 months. It compares the previous day's HRV before days when an attack started and before days with no attack logged. Missing or unavailable days do not become zero. Cached summaries are retained after empty or failed reads, but unavailable days are excluded from comparisons. Summaries from previous sources or time zones stay stored and are excluded from the current comparison.

This processing happens on your phone. Aura does not automatically transmit HRV or its comparisons or use them for advertising. Stored HRV is included when you explicitly create an encrypted backup. HRV observations can also be included when you select them for the detailed doctor report. Both are shared only through a destination you choose. HRV remains excluded from the existing free PDF and CSV exports. Your device's existing backup settings are unchanged.

Turn HRV patterns off to stop reads and hide results. Imported summaries and the selected source remain until you delete all data. Delete all data removes imported HRV and resets HRV import and source selection. It does not change original Apple Health records or Health permissions.

## Period tracking (Aura Plus, optional)

Period tracking is an optional Aura Plus feature and is off by default. Choose manual logging or Apple Health in Settings. Only one mode is active. Switching preserves inactive records but hides them and excludes them from comparisons. Completeness must be confirmed again after switching.

Manual entries contain a start date and optional end date. Apple Health mode reads Menstrual Flow from one selected source over the last 12 months, including manually entered Health records. Aura uses explicit period-start markers and does not infer starts or ends from gaps. Imports refresh while the app is open or when requested. Aura never writes to Apple Health.

Aura stores period dates, original Health sample identifiers and timestamps, source identifiers and names, date time zones, refresh status, local corrections or exclusions, and the comparison range and time when you confirmed completeness. Imported originals are preserved so local corrections can be undone. Missing or failed reads preserve cached records and mark uncertainty. Changes to period dates or the selected source require completeness confirmation again.

This information stays in the local database on your phone. Aura does not automatically transmit period data or comparisons or use them for advertising. Stored period data is included when you explicitly create an encrypted backup. Period observations can also be included when you select them for the detailed doctor report. Both are shared only through a destination you choose. Period data remains excluded from the existing free PDF and CSV exports. Your device's existing backup settings are unchanged.

Turning period tracking off stops imports and hides comparisons while retaining records. Delete all period data removes manual entries, imports, local corrections and completeness confirmations, including inactive sources, and turns tracking off. Delete all data does the same along with the rest of your log. Neither changes original Health records or Health permissions.

## Encrypted backup and restore

Creating encrypted backups is an optional Aura Plus feature. Restoring an existing backup is free. Settings > Data management > Backup and restore creates a password-protected file containing your local log, preferences, preventative history, weather, imported sleep and HRV summaries, and all period records, including inactive histories, source information and local corrections. Purchase access and device permissions do not transfer.

Aura encrypts the file on your phone with the password you choose. Passwords are not saved and cannot be recovered. Only you choose where to send the encrypted file through the iOS share sheet. Its destinations may include AirDrop, Files or other services, which have their own terms. Aura does not automatically upload backups or operate a backup server.

Restoring replaces the current log after you review and confirm. Health imports, weather and reminders are off afterward until you enable them again. Period completeness must be confirmed again. Temporary working files and a recovery copy stay in protected app storage, are excluded from device backups, and are removed after completion or recovery. Your live database location and existing device backup settings are unchanged.

Deleting data in Aura does not delete files you exported. Manage those copies at their chosen destinations.

## Notifications are local

Optional daily reminders, medication check-ins and preventative reminders are scheduled on your device using local notifications. Aura does not send their contents to a push notification server. iOS controls how notifications appear, including on paired devices and notification previews.

## Exports leave only when you send them

The PDF report and CSV export are generated on your phone. They contain your
health log. When you share one, for example with your doctor, it travels
by whatever method you choose (mail, messages, airdrop), under that service's
terms, not ours. Aura never transmits an export anywhere on its own.

The detailed doctor report is an optional Aura Plus feature. It includes a selected-date attack and medication summary and preventative history. Free-text notes, sleep, HRV, period and weather observations are optional choices for each export. These choices are off by default and are not saved. PDFs are not encrypted. Aura attempts to remove its temporary detailed-report files when sharing finishes or fails. An interruption can leave temporary files in the app cache. Copies saved at your chosen destination remain there.

## Purchases (Aura Plus)

Apple and RevenueCat process Aura Plus subscriptions and restore access. RevenueCat receives a randomly generated anonymous app identifier, purchase history and receipt information, and app, device and storefront information needed for purchase processing. It also receives activity timestamps and provides subscription reporting. Purchase checks can contact RevenueCat when you open Aura, return to the app, load prices, purchase, restore or manage a subscription, even if you have not subscribed.

Aura does not send health records, your nickname or personalization focus to RevenueCat. Aura supplies no advertising identifiers or customer contact attributes. Apple handles payment details. RevenueCat processes purchase information on our behalf. Its privacy information is at https://www.revenuecat.com/privacy and Apple's is at https://www.apple.com/legal/privacy/.

Deleting your local log does not cancel an Apple subscription or erase purchase records held by Apple or RevenueCat. Manage or cancel subscriptions through Apple. For a request concerning purchase data processed for Aura, contact aura.migraine.app@gmail.com. We may need information to locate the anonymous purchase record. Applicable legal retention requirements may limit deletion. Do not send your health log or backup password with a request.

## Deleting your data

Settings → Data management → Delete all data erases your entire log immediately and
permanently, including stored weather, imported sleep and HRV, and all period data. It also turns
sleep, HRV and period imports off. Deleting the app from your phone removes Aura's local
database. Original sleep, HRV and menstrual records in Apple Health are not changed. Aura keeps
no server-side copy of your log. Files you exported remain at their chosen destinations until you delete them there.

## Children

Aura is not directed at children under 13. It has no account. Optional weather and subscription processing are described above.

## Changes to this policy

If a future version of Aura changes what happens with your data, this policy will be updated
before the change takes effect. We will explain material changes and request permission where required. The current version of this policy is available at https://auramigrainelog.com/privacy and inside the app
under Settings → Privacy.

## Contact

Questions about privacy in Aura: aura.migraine.app@gmail.com
