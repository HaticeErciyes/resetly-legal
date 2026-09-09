---
layout: default
title: Privacy Policy
description: What Resetly records, where it stays, and how advertising is kept separate from it.
lang: en
---

Last updated: 9 September 2026

## 1. Who we are

Resetly is published by an individual developer based in Türkiye:

- **Name:** Hatice Ertuğrul
- **Address:** Beşiktaş, İstanbul, Türkiye
- **Contact:** haticeerciyes_7@hotmail.com

The address is given at district level. That is a deliberate choice for an
individual publisher — a full street address beside a personal email in a
permanently public document carries its own risk — and whether it satisfies
KVKK's aydınlatma requirement and both stores' controller-address expectations
is an open question for counsel (this question is open and under review).

Because Resetly is published from Türkiye, **Law No. 6698 on the Protection of
Personal Data (KVKK)** applies to us as data controller, in addition to the
rules of the markets the app is sold into. See §10.

The launch markets are the United States, the United Kingdom, Canada and
Australia. Because they sit outside the EEA, the EU GDPR is not the primary
regime, but the UK GDPR applies to users in the United Kingdom. Whether
offering the app there from Türkiye triggers the UK representative requirement
— and whether the absence of any transfer of user records changes that
analysis — is open for counsel (this question is open and under review).

## 2. The short version

Resetly is a wellness and self-reflection app. It has no account and no server
of its own. What you record in it — how you felt, which exercise you were
offered, the two intensity numbers — is written to storage on your own device
and is not uploaded to us. We cannot read it, because it never reaches us.

The app is free and is funded by advertising. Advertising is the only part of
Resetly that communicates with anyone outside your device, and it never
receives anything you record.

Those two sentences are the whole design. The rest of this policy explains
them precisely.

## 3. What Resetly records, and where it goes

When you **finish** a check-in, the app writes one record to local storage on
your device containing:

- the mood word you picked
- the context you picked, if you picked one
- the reset you were offered
- whether you ran it
- the two intensity numbers, if you gave them
- the date and time

There is no account and no server, so this record is not uploaded and not
synced. It stays in the app's own storage on the device until you delete it or
uninstall the app.

The app also stores a small number of settings on the device: whether you have
completed onboarding, whether reminders are on and at what time, your
appearance choice, any resets you have marked as less preferred, and your
advertising choice. These are settings, not a record of you.

## 4. What Resetly deliberately does not record

- **Nothing before you finish a check-in.** If you open the app, pick a mood
  and leave, nothing is written.
- **Nothing about the support screen.** The app keeps no record that you
  opened it and no count of how often. This is deliberate and is enforced in
  the code: there is no analytics event for it to emit.
- **No free-text profile of you.** There is no name, no email, no date of
  birth, no contacts, no location, no photos, no health-app integration.
- **No age.** The app asks you to confirm you are 18 or older. It records only
  that you confirmed — not a date of birth, which would be new personal data.

## 5. Analytics

Resetly's analytics record **that** something happened, never what it was
about. An event may say a mood was selected; it does not record which mood. The
event names are fixed in the code and no event carries a mood word, a context,
an intensity number, an exercise identity, or anything to do with the support
screen. Tests enforce this.

As shipped, there is in fact **no analytics provider at all**. The
implementation is a no-op: it prints event names in debug builds and does
nothing whatsoever in a release build, so no event leaves your device either.
The structure described above exists so that the guarantee holds if a provider
is ever added — and if one is, this section must be rewritten and the provider
named before that build ships.

## 6. Advertising

Resetly is free and is funded by advertising, served by Google AdMob.

**What the advertising system never receives:** your mood words, contexts,
intensity numbers, reset history, anything you write, and anything to do with
the support screen. This is not a promise about intent — the advertising code
and the code that records check-ins are separate systems with no connection
between them, and there is no parameter through which any of it could be
passed.

**What may be shared:** when advertising is on, an advertising identifier from
your device may be passed to Google to choose which ads to show, along with the
ordinary technical information any ad request carries. Google's own handling of
that identifier is governed by their policies, not this one:
https://policies.google.com/technologies/partner-sites

**Your choice.** The app asks you, once, after your first completed journey,
whether advertisers may use an advertising identifier from your device. It is
never assumed. Until you answer, no advertising is shown at all. In Settings
you can change the answer at any time, including refusing advertising entirely.

**Where advertising never appears:** onboarding, the support screen, the
privacy and legal screens, the data-deletion screen, the check-in entry, and
during a running exercise or timer. If you open the support screen, advertising
is switched off for the rest of that session.

## 7. Notifications

If you turn reminders on, the app schedules them on your device using the
operating system's own local notification system. Nothing is sent to a server
and no push service is involved. Reminders are off until you turn them on, and
the app asks for notification permission only at that moment.

## 8. Deleting your data

Settings → Privacy has a control that erases every recorded check-in from the
device. History and Insights become empty at the same moment, because both are
read from that record and nothing is kept in a summary. It cannot be undone.

Uninstalling the app also removes everything it stored.

Because we never receive your records, there is nothing for us to delete on
your behalf and no request you need to send us to have it done.

## 9. Your rights

Depending on where you live you may have rights to access, correct, delete,
or port your personal data, to object to or restrict its processing, and to
complain to a supervisory authority.

In Resetly's case, access and deletion are in your hands directly: the data is
on your device, the app shows it to you in History, and the deletion control
erases it. We hold no copy to produce or erase.

This section is written generically because the four launch markets are not
uniform, and because one question sits underneath all of them: whether
on-device-only processing of possibly-special-category data, by a controller
that never receives it, creates obligations at all — and if so, which. That
question is recorded in our own legal review and needs a
jurisdiction-specific answer before publication.

### California (CCPA/CPRA)

We do not sell your personal information, and we have not sold or shared it in
the preceding twelve months other than as described here: when advertising is
on, an advertising identifier from your device may be shared with our
advertising provider for advertising purposes, which California law may treat
as "sharing" for cross-context behavioural advertising.

You can stop that at any time. In the app: **Settings → Privacy → Do Not Sell
or Share My Personal Information**. Choosing it stops the identifier being
shared and turns off personalised advertising.

Nothing you record in a check-in is ever sold or shared, under any setting.

Three points here are open for counsel (these questions are open and under review):
whether the in-app control is sufficient on its own, whether a separate "Limit
the Use of My Sensitive Personal Information" link is required, and whether the
twelve-month statement above can stand for a product that has not yet
launched.

## 10. Türkiye (KVKK — Law No. 6698)

Because Resetly is published from Türkiye, KVKK applies to us as **veri
sorumlusu** (data controller). This section is the aydınlatma metni — the
disclosure KVKK Article 10 requires — for users in Türkiye.

**Controller identity.** As stated in §1: an individual developer, named and
contactable there.

**What personal data is processed, and where.** The check-in records described
in §3 and the settings listed there. All of it is written to storage on your own
device. None of it is transmitted to us, and we hold no copy. The only data
that leaves your device is the advertising identifier described in §6, and only
when advertising is switched on.

**Purpose.** To provide the app's own function: to show you what you recorded,
and to fund the app through advertising.

**Legal basis (Article 5).** For the check-in records, processing takes place
entirely on your own device under your own control, and we receive nothing —
see the note to counsel below on how this should be characterised. For the
advertising identifier, the basis is your **explicit consent (açık rıza)**,
which the app asks for separately and never assumes; until you answer, no
advertising is shown and no identifier is shared.

**Sensitive personal data (Article 6).** Self-reported information about how
you feel may qualify as **özel nitelikli kişisel veri** (data concerning
health). Resetly's design response is that such information never leaves your
device and never reaches us or any third party — including the advertising
provider, which is separated from it in code.

**Transfers abroad (Article 9).** We transfer no check-in data anywhere. The
advertising identifier is processed by Google as our advertising provider,
which involves processing outside Türkiye; this happens only with your consent
and never alongside anything you recorded.

**Retention.** Your records stay on your device until you erase them or
uninstall the app. We keep nothing, so there is no retention period on our
side.

**Your rights under Article 11.** You have the right to learn whether your
personal data is processed, to request information about it, to learn its
purpose, to know any third parties it is transferred to, to have incomplete or
incorrect data corrected, to request erasure or destruction, to object to
results produced solely by automated analysis, and to claim compensation for
damage caused by unlawful processing.

In practice, for the data Resetly holds, most of these are exercised directly:
the records are on your device, History shows them to you, and the deletion
control in Settings → Privacy erases them. We hold no copy to produce, correct
or destroy. For anything else, or to make a formal application, contact the
address in §1. KVKK gives us 30 days to respond.

You may also complain to the **Kişisel Verileri Koruma Kurumu (KVKK Authority)**.

Three KVKK questions remain open and are set out in full, with the research
already done, in our own legal review: whether VERBİS registration is
required of a publisher who receives no user data; whether we are the
controller of records we never receive; and whether Article 6 explicit consent
is required for on-device sensitive data that is never transmitted. None can be
answered from the code, and this section may need to change once they are.

## 11. Children

Resetly is intended for adults and asks you to confirm you are 18 or older
before you can finish onboarding. It is not directed to children, is not listed
in a children's category on either store, and knowingly collects nothing from
children.

Whether a self-declared confirmation is sufficient in each launch market, or
whether a verified age gate is required, is open for counsel
(this question is open and under review).

## 12. Changes to this policy

If this policy changes, the updated version will be posted at
<https://haticeerciyes.github.io/resetly-legal/privacy> with a new date at the top. Material changes will also
be surfaced in the app.

## 13. Where each claim comes from in the code

Included so a reviewer can verify rather than trust. Line references will drift;
the file and symbol names are the stable part.

| Claim | Where it is made true |
|---|---|
| No account, no server, no sync | `lib/data/sessions/session_store.dart` — local storage only; no network dependency in `pubspec.yaml` other than the ad SDK |
| The exact fields recorded | `SessionRecord` in `lib/data/sessions/session_store.dart` |
| Nothing recorded before a check-in finishes | The record is written only on completion; see the reflection flow in `lib/features/reflection/` |
| No record of opening the support screen | `lib/services/analytics/analytics_service.dart` — there is no `safety_*` event constant to emit |
| Analytics carry no wellness data | `ProductAnalyticsEvents` + `SafeAnalyticsService`; enforced by `test/features/analytics_flow_test.dart` |
| Analytics are a no-op in release | `NoopAnalyticsService` in `lib/services/analytics/analytics_service.dart` |
| Wellness data cannot reach the ad layer | `lib/services/consent/ad_consent.dart` — no domain import is possible; `AdConsentDecision.forbiddenSignals`; enforced by `test/architecture/consent_separation_test.dart` |
| No advertising until you answer | `AdConsentStatus.unknown` is the default and `AdPolicy` refuses every placement under it — `lib/services/ads/ad_policy.dart` |
| A regional refusal actually stops advertising | `AdPolicyState.platformAdsAllowed`, fed by `syncPlatformAdsGate` — `lib/services/consent/platform_ads_gate.dart` |
| Ad-free surfaces | `AdPlacement.isSensitive` — `lib/services/ads/ad_placement.dart` |
| Advertising stops after the support screen | `AdService.suppressForCrisis` — session latch, not cleared by navigation |
| Notifications are local only | `flutter_local_notifications`; `lib/services/notifications/` — no push service |
| Deletion erases everything derived | `SessionStore.deleteAll`; History and Insights read from the same record |
| The age confirmation stores no date of birth | `lib/features/onboarding/widgets/age_confirmation.dart` |
| The CCPA control acts on the same consent record | `lib/features/privacy/widgets/opt_out_controls.dart` |
