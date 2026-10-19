# Puck View Privacy Policy

**Last updated: October 18, 2026**

Puck View uses your Apple Watch's motion sensors to support heads-up stickhandling practice. The app processes motion on your Watch and paired iPhone. It does not automatically upload your motion data or calibration recordings to the developer or a third-party service.

## Motion and calibration data

While a Watch session is active, Puck View measures wrist orientation, rotation rate, gravity and acceleration. Measurements include timestamps, sequence numbers and a session identifier. The app uses these measurements to calibrate and recognize wrist movements associated with the five training positions. It does not directly measure the puck's location or contact with the stick.

Calibration recordings are saved in the iPhone app's private Application Support storage. They include motion samples, requested positions, recording times, setup choices such as Watch wrist and stick hand, calibration rules and results, and unsuccessful or interrupted attempts. Imported recordings are also stored there. Display and timing preferences are stored locally.

The Watch and iPhone exchange motion measurements, calibration files, recognition results and training messages using Apple's WatchConnectivity framework. The Watch creates temporary recording files for queued transfers and attempts to remove them when a transfer finishes. This communication is between your own paired devices; Puck View does not operate a server that receives these recordings.

## Retention and deletion

Calibration recordings are kept until the app's local data is deleted. Starting another calibration or ending a training session does not delete earlier recordings. This version has no in-app control to delete individual recordings or clear the recording library, and recordings do not expire automatically.

To remove the iPhone app's local recordings and preferences, open **Settings → General → iPhone Storage → Puck View → Delete App**, then confirm deletion. **Offload App** keeps documents and data and does not delete the recordings. Deleting the app also removes the calibrations it needs for training.

Your device backup services may include app data, depending on your Apple settings. Deleting the app does not remove separately exported files, copies held by recipients or existing backups. Manage those copies through the destination app, service or backup settings. Puck View has no separate cloud-storage service.

## Exporting and sharing

When you choose **Export recordings**, Puck View creates a JSON file containing all retained calibration recordings, including failed attempts, and opens the system share sheet. You choose whether and where to save or share it. Opening the export does not automatically send it to the developer.

The app attempts to remove its temporary export file when the share sheet closes. Copies you save or send remain under your control or the recipient's control. The destination's privacy practices apply to those copies. If you send a recording to the developer for support, the developer receives the information included in that file. Do not include information you do not want to share.

## HealthKit

Puck View uses HealthKit to run an active hockey workout session on Apple Watch so wrist-motion updates can continue when you lower your wrist. It requests permission to write workouts, but this version does not save a workout to Health and does not request permission to read your Health records. It does not read heart rate, calories or other Health measurements.

Use **Stop** in the Watch app to end its session. Manage HealthKit access in Apple's Health or privacy settings. Apple's own health sensing, services and privacy choices are separate from Puck View's access.

## Accounts, analytics and tracking

Puck View does not require an account or sign-in. It contains no advertising or analytics services and does not track you across other apps or websites. The app does not automatically share your recordings with advertisers or other third parties, and it does not sell your data. Sharing occurs only when you choose an export destination, apart from device services such as backups that you control through Apple settings.

Development builds may keep local diagnostic logs of connection status, timing and errors. These logs are not automatically uploaded. The App Store release configuration excludes this diagnostic logging.

## Contact

For questions about this policy or the app, contact:

**cam.j.fitzpatrick@outlook.com**
