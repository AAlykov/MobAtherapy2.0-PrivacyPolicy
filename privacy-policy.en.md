# Privacy Policy for MobAtherapy 2.0

**Version:** 1.1 — draft for review, 6 November 2026. Not yet published. The effective date will be set when the final version is published.

## 1. Who is responsible for your information

This policy explains how information is handled when you use the MobAtherapy 2.0 Android application and when authorised healthcare staff use its companion DeskAtherapy application to work with patient records, consultations and reports.

**Data controller:** Cardiology Research Institute, Tomsk NRMC (НИИ кардиологии Томского НИМЦ).

**Developer:** Alexey Alykov (Алексей Алыков, Tomsk). This is the developer name used for Google Play.

**Privacy and account deletion contact:** [mobatherapy@mail.ru](mailto:mobatherapy@mail.ru).

MobAtherapy 2.0 helps patients record medication intake and symptoms, complete questionnaires and communicate with healthcare staff. It does not make diagnoses or replace medical care.

## 2. Information used by the application

| Category | Information | Purpose |
|---|---|---|
| Account | Email address, username, account identifier and authentication information | Create and access your account, recover access and associate records with you. Password authentication is handled by Firebase Authentication; passwords are not stored in patient records. |
| Profile | Full name, date of birth, sex, telephone number; optional city, medical organisation and diagnosis | Identify the patient and support healthcare communication. Full name, date of birth, sex and telephone number are required to complete the profile. |
| Consent | Consent status, acceptance time, document identifier, version and checksum | Record which separate in-app consent document was accepted. |
| Medication | Medicine names, dosage, form, schedule, course dates, intake or missed-intake status, actual intake time and notes | Reminders, intake history, adherence statistics and reports. |
| Health diary and questionnaires | General condition, pulse, blood pressure, INR where entered, symptoms, bleeding and thromboembolic complication responses, event dates and free-text notes | Record changes over time and provide information to healthcare staff. |
| Consultations | Consultation subject, messages, photographs you send, participants, timestamps and read status | Patient–clinician communication. |
| Notifications and device status | Notification tokens, account identifier and email in device-status records, device model/manufacturer, Android and app versions, last-contact time, notification titles/text, recipients and delivery results | Deliver notifications, show whether a device has contacted the service and investigate delivery problems. |
| Diagnostics and support | Crash information, installation identifiers, device/app information, technical logs, and correspondence you send to support | Investigate failures, maintain the application and handle requests. Infrastructure providers may also process connection information such as IP addresses. |

Information is obtained from what you enter or send, your actions in the application, healthcare communication, and the technical services used by the application. Do not include information about other people unless it is necessary and you are authorised to provide it.

The application has no advertising and does not sell user information for advertising. It does not request permission to read contacts, obtain device location or record microphone audio. Photographs are taken or selected through Android and are sent when you choose to attach them. You do not need to send a photograph to use the diary or medication features.

## 3. Separate in-app consent

Before registration, the application asks you to accept a separate personal data processing consent. You can read that document through “More about consent” on the registration screen and in your profile, including without an internet connection.

That consent and this Privacy Policy are separate documents. This policy describes information handling; opening it or viewing a consent document does not itself select the consent checkbox. The current in-app consent identifies the controller and provides its own withdrawal procedure, including the contact alykov_ab@mail.ru. You may also send questions or requests to the privacy contact above.

## 4. Access and recipients

- You use your account to view and manage the records available to you in the application.
- Registered doctors can view patient profiles, medication information, diaries and questionnaires. Patient cards are not restricted to the assigned doctor. Assignment determines the handling of consultations; an unassigned consultation enters the shared doctor queue.
- Healthcare staff use consultations and photographs to communicate with patients and can generate patient reports. Authorised exports can include PDF, Word and Excel files. Files saved or shared outside the application are handled separately by their recipients and are not automatically recalled by deleting an app account.
- Project administrators and technical support may access information when necessary to administer the service, address support requests and investigate problems.
- Google Firebase and Google Cloud process information to provide authentication, storage, notifications, server operations and diagnostics.

The application does not make patient records publicly searchable. Please protect your account and review which information you send in messages and attachments.

## 5. Firebase services and processing locations

The application uses Firebase Authentication, Cloud Firestore, Cloud Storage for Firebase, Realtime Database, Cloud Functions, Firebase Cloud Messaging and Firebase Crashlytics.

The project uses Europe (eur3) for its primary Firestore database, US-EAST1 for consultation photographs, us-central1 for Realtime Database and europe-west1 for its server functions. Firebase Authentication operates from the United States. Other Firebase services use Google's infrastructure and may process information in additional countries. Information can therefore be stored and processed outside Russia; selecting a storage region does not mean that every related service operates only in that region.

For the provider's service-specific handling information, see [Privacy and Security in Firebase](https://firebase.google.com/support/privacy) and the [Google Privacy Policy](https://policies.google.com/privacy).

## 6. Data on your phone and Android backup

Medication records, diary entries, questionnaire responses and some settings are stored in the application's private storage. Records synchronise with Firebase when a connection is available. Local offline records can include changes that have not yet reached the server.

For the version covered by this draft, Android cloud backup and direct phone-to-phone transfer are configured to include only the selected appearance theme. The local database, login state, technical files and installation-related settings are excluded. On a new installation, sign in and download synchronised records again. Changes not sent to Firebase before the application is removed or the phone is lost cannot be recovered through this process. These settings do not remove older Android backups made by previous versions.

Notifications and exact-alarm access support medication reminders. Android settings control the permissions you grant. Refusing notification permission can prevent reminders from appearing; it does not delete your existing records.

## 7. Retention

Account information and patient records are retained while the account is in use, unless you request deletion or the controller is required to handle particular information differently. If a specific retention requirement applies to information held outside the application as part of medical care, the controller must explain it separately; this policy does not establish a blanket exemption from deleting app data.

**Agreed rule for processed notification requests:** delete or irreversibly de-identify them 30 days after processing. This rule applies to processed requests, not unprocessed requests awaiting delivery or investigation. The automatic cleanup implementing this rule has not yet been added; it must be implemented before this draft is published as an effective policy.

Notification-delivery records and server logs can contain account/recipient identifiers, timestamps, notification text and results. The current account deletion function does not automatically clear all of those records. The controller's retention periods and deletion process for server logs and support correspondence must be finalised before publication; we do not describe these records as anonymous or as already erased.

Firebase Crashlytics retains crash reports and associated identifiers for 90 days before beginning removal from live and backup systems, according to the provider's published information. Deleting an application account does not by itself guarantee immediate deletion of every provider diagnostic record.

## 8. Delete your account and request deletion of information

You can start the patient account deletion process in **Profile → Delete account and all data** and confirm with your password. The server process removes the patient profile and its stored records, consultation messages and photographs, notification/device-status entries covered by that process, and the authentication account. Local records on the phone are cleared after the server reports success.

Doctor and administrator accounts use the email request route. You can also use email if you no longer have the application, cannot sign in, or cannot complete deletion in the application.

Send a request to [mobatherapy@mail.ru](mailto:mobatherapy@mail.ru) with the subject **MobAtherapy 2.0 — account deletion**. Send it from your registered email when possible and identify the account to be deleted. If you cannot access that mailbox, explain the situation so that account ownership can be checked. Do not send your password or unnecessary medical documents.

Email deletion requests are handled within **30 days**. We will tell you if additional information is necessary to verify ownership and confirm the result. Requests concerning remaining service records or exported medical records must identify the information concerned; the controller will explain the scope of deletion and any applicable retention requirement.

Deleting the application from your phone does not delete the server account. If deletion fails, you can retry or contact support; an error does not establish that no server data changed. **[Open the account deletion instructions](delete-account.html).**

## 9. Other requests and consent withdrawal

Contact us to request access to your information, corrections, deletion, or an explanation of its use. For withdrawal of the separate consent, follow the procedure in that document or contact us for assistance. Withdrawal can affect functions that require processing your information; the controller will explain the consequences and any information that must be retained.

## 10. Security

The application uses account authentication, private application storage and encrypted network connections. Access controls and administrative procedures are intended to restrict information to permitted uses. We cannot guarantee absolute security. Protect your password and phone, and do not include passwords in consultation messages or support requests.

## 11. Intended audience

The application is intended for adult patients and healthcare professionals, not children. If you believe that a child has supplied information through the application, contact us so that the controller can review the situation and take appropriate action.

## 12. Updates and contact

The published policy will identify its version and effective date. Material changes will be communicated through the application or the registered contact details when appropriate. The separate consent has its own version; changing this policy does not record acceptance of a different consent document.

**Controller:** Cardiology Research Institute, Tomsk NRMC. **Developer:** Alexey Alykov. **Contact:** [mobatherapy@mail.ru](mailto:mobatherapy@mail.ru).
