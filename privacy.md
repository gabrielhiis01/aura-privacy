# Aura Privacy Policy

**Effective date:** July 10, 2026

Aura is a migraine log. This policy is short because the honest answer to
almost every privacy question about Aura is: *we don't collect it.*

## Your log lives on your phone

Everything you record in Aura is stored in a local database on your device:
attacks, pain levels, symptoms, medications, check-in answers, notes, and
settings. There is no account, no sign-in, no cloud copy, and no server of ours
that holds any of it. We are technically incapable of reading your log.

## Nothing is collected

Aura contains no analytics, no advertising, no third-party trackers, and no
crash reporters. The app makes no network requests to us. We don't operate a
backend at all.

## Notifications are local

The optional daily reminder and medication check-ins are scheduled on your
device, by your device, using the operating system's local notification
feature. No push notification servers are involved, and notification content
never leaves your phone.

## Exports leave only when you send them

The PDF report and CSV export are generated on your phone. They contain your
health log. When you share one, for example with your doctor, it travels
by whatever method you choose (mail, messages, airdrop), under that service's
terms, not ours. Aura never transmits an export anywhere on its own.

<!--
Gated on PLUS_ENABLED (constants/featureFlags.ts), like the matching section
in screens/settings/PrivacyScreen.tsx — the policy copies must stay in sync
(three of them: this file, PrivacyScreen.tsx, and the hosted copy in the
public aura-privacy repo — see the AGENTS.md invariant). v1 ships free: no
purchase infrastructure runs or is contacted, so this section would describe
data processing that doesn't happen. Restore it (all three copies, plus the
effective date above) in 1.1 when Aura Plus ships.

## Purchases (Aura Plus)

The optional Aura Plus unlock is processed by Apple (App Store) and
RevenueCat, our purchase infrastructure provider. To make the purchase work
and be restorable, they process:

- the transaction itself (handled by Apple, under Apple's privacy policy);
- an anonymous, randomly generated app-install identifier and purchase
  record (handled by RevenueCat, under RevenueCat's privacy policy at
  https://www.revenuecat.com/privacy).

Your migraine log is never attached to, or transmitted with, any purchase
data. Neither Apple nor RevenueCat receives anything you logged. If you never
buy anything, no purchase infrastructure is contacted with any identifier of
yours beyond what the operating system itself does.
-->

## Purchases

There are none. This version of Aura is entirely free, with no in-app
purchases, so there is no purchase data, no payment processor, and no
purchase identifier of any kind.

## Deleting your data

Settings → Delete all data erases your entire log immediately and
permanently. Deleting the app from your phone does the same. There is no
server-side copy to linger. When it's gone from your device, it's gone.

## Children

Aura is not directed at children under 13 and collects no data from anyone,
including children.

## Changes to this policy

If a future version of Aura changes what happens with your data, such as an
optional encrypted backup feature, this policy will be updated
first, the change will be opt-in, and the app will say so plainly. The
current version of this policy always lives at this URL and inside the app
under Settings → Privacy.

## Contact

Questions about privacy in Aura: aura.app.migraine@gmail.com
