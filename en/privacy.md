---
layout: default
lang: en
doc: privacy
title: Privacy Policy
permalink: /en/privacy.html
---

# Privacy Policy

<p class="date">Effective {{ site.effective_date_en }}</p>

Nozik is a menstrual cycle calendar. You trust us with information about your health, so we collect only what the app needs to work, and we never sell your data.

This policy explains what data the Nozik app for Android and iOS (the "app") processes, why, where it is stored, and how to delete it.

## 1. Who is responsible for your data

Data controller: {{ site.developer_en }}, Republic of Uzbekistan.
For any question about your data, write to [{{ site.email }}](mailto:{{ site.email }}).

## 2. What data we process

**Data you enter:**

- answers on first launch: language, goal (track the cycle or get pregnant), usual period and cycle length, start date of the last period;
- calendar marks: period days;
- diary: flow, symptoms, mood and short notes;
- app settings (for example, whether to show cycle days and fertile days).

Cycle, symptom and mood data are health data. We treat them as especially sensitive.

**Account data:**

- on first launch the app creates an anonymous Firebase account: a random identifier that cannot identify you;
- if you sign in with Google, we receive your name, email address and Google account identifier. We never see your Google password.

**Technical data:**

- crash reports (Firebase Crashlytics): device model, system and app version, technical description of the error;
- usage statistics (Google Analytics for Firebase): which screens are opened and which actions are taken, such as "period marked" or "diary entry saved", plus language, approximate country and an app installation identifier.

Your cycle dates, symptoms, moods and note texts are **never** included in statistics or crash reports. We send only the fact of an action and counts.

**Advertising.** The free version of the app may show ads from Google AdMob. AdMob may use your device's advertising identifier. Your health data is never shared with ad networks. You can turn off personalized ads in your phone settings.

## 3. Why we use data

- to show the calendar, the forecast of periods, ovulation and fertile days, statistics and the report for your doctor;
- to back up your history in the cloud and restore it on a new phone if you are signed in;
- to find and fix bugs;
- to understand which features are useful and improve the app;
- to show ads in the free version.

We process health data based on your consent, which you give when you start using the app. You can withdraw consent at any time by deleting your data (section 7).

## 4. Where data is stored

All data is stored on your phone first. The app works without the internet.

So that your history is not lost, cycle marks, diary entries and first-launch answers are copied to Google Cloud Firestore. The servers are in Frankfurt (Germany, European Union). Crash reports and statistics are processed on Google servers that may be located in other countries. By using the app, you agree to this cross-border transfer.

Data is sent over an encrypted connection. Only your account can access your records in the cloud: the database security rules enforce this.

## 5. Who we share data with

We do not sell or rent your data. We share it only with:

- Google LLC and its affiliates, which run Firebase (authentication, database, Crashlytics, Analytics) and AdMob. Google processes data on our behalf and under its own rules: [policies.google.com/privacy](https://policies.google.com/privacy);
- public authorities, when the law expressly requires it.

The PDF report for your doctor is created on your phone. Only the people you send it to will receive it.

## 6. How long we keep data

- cycle and diary data are kept until you delete them or your account;
- crash reports are kept for up to 90 days;
- usage statistics are kept for up to 14 months;
- if you delete the app without signing in with Google, the data on your phone is deleted with it. We delete the cloud copy linked to the anonymous account on request.

## 7. Your rights and data deletion

You can:

- view and correct your data in the app;
- export your history as a PDF report;
- opt out of statistics and personalized ads in your phone settings;
- delete your account and all cloud data.

To delete your account, choose account deletion in the app's "Profile" section (if your version has it) or write to [{{ site.email }}](mailto:{{ site.email }}). Write from the address linked to your account, or say that you used the app without signing in. We will delete the data within 30 days and confirm it.

## 8. Children

The app is intended for users aged 16 and over. If you are under 16, use the app only with your parents' consent. If you learn that a child has given us data without such consent, write to us and we will delete it.

## 9. Medical disclaimer

Nozik is not a medical device and does not diagnose. Forecasts are approximate and are not suitable for contraception. See the [Terms of Use]({{ site.baseurl }}/en/terms.html).

## 10. Changes to this policy

We may update this policy. The new version is published on this page with a new date. We will tell you about significant changes in the app.

## 11. Contact

{{ site.developer_en }}<br>
Email: [{{ site.email }}](mailto:{{ site.email }})
