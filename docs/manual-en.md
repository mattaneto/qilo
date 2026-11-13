# Qilo user manual

App version: **0.5.3** · [Português](manual-pt-BR.md)

> **Wellness notice.** Qilo only records the values sent by the scale. It is not a medical device and does not diagnose, treat, cure, or prevent any medical condition. For any health question, consult a healthcare professional.

## 1. Getting started

1. Install the APK and open Qilo. On first launch the **wellness notice** appears; tap **Got it** to continue.
2. Tap **Create profile** and fill in name, **Name on the display**, sex, date of birth, height, unit and mode.
   - The **Name on the display** is what the scale shows: up to 6 lowercase letters or digits. Accents become the plain letter (Antônio → `antoni`). If you leave it empty, the app uses the first name.
3. On the **Measurement** tab, tap **Connect** and allow Bluetooth access.
4. Tap the scale or step on it to wake it up. When it says **Connected**, the app sends the profile to the scale.
5. Step on the scale barefoot. Your name shows on the display and the weighing arrives in the app.

The app keeps waiting for the scale: every time it wakes up, the app reconnects by itself. To save battery, it stops looking after 3 minutes without finding the scale and while the app is in the background (it looks again when you open the app). To stop right away, tap **Disconnect**; to shut everything down, use **Close app** in the ☰ menu.

A reconnection without changes writes nothing to the scale. The app only writes to it when you change a profile or a goal, and to set the clock on the first connection, after a reset or every 7 days (the clock is needed for body composition).

## 2. Measurement screen

- **Date and time** of the latest weighing.
- **Weight**, large, with **body fat** and **muscle** below it.
- **Face and 7-day change**: compares the current weight with the one from at least 7 days ago.
  - Happy (green) when weight went down, neutral when it stayed about the same (less than 0.1 kg apart) and sad (orange) when it went up.
  - If your goal is to **gain** weight, the rule flips: going up makes the face happy.
  - With less than 7 days of history, the face stays neutral.
- **Goal**: the button opens the goal screen of the selected profile.
- **BMI** colored by band (underweight, normal, overweight, obese), with the bar and marker.
- **Add note »**: see section 6.
- With more than one profile, the name buttons at the top switch the profile shown.

## 3. Several people on one scale

- Each app profile is written to the scale, which recognizes who is weighing by weight.
- When unsure, the scale shows the profiles and **guest** on its display. Tap the scale with your foot to change the option; it is taken after a few seconds without taps. The app mirrors the same list, with the current option highlighted.
- **Guest weighings are not saved** and do not appear in the app.
- To fix a weighing saved for the wrong person: **History › List**, tap it and choose **Change profile**.

## 4. Goals

Tap **Set a goal** (or the **Goal** button) on the Measurement screen.

- **Target weight**: the app shows the healthy range for your height (BMI 18.5–24.9) and warns if the target is below BMI 18.5.
- **Pace**: 0.25, 0.5, 0.75 or 1 kg per week, no pace, or **By a date** — the app then computes the pace and warns above 1 kg per week.
- The **Goal progress** card shows this week's target, how much is left, the planned date, whether you are ahead or behind, the estimated date at the current pace and the weekly trend (from the last 28 days of weighings).
- The goal is also sent to the scale, which uses it in Smart Feedback mode.
- Pregnancy mode has no goal.

## 5. History

- **Chart**: weight, BMI, body fat, water, muscle and bone (only those with data), for 30 days, 90 days, 1 year or everything. The goal is a dashed line.
- **List**: every weighing. Tap one to see its details in a sheet that slides up from the bottom, with the values in alternating rows; the **X** in the corner closes it. From there you can edit the note, change profile or delete it.
  - **Compare**: tap **Compare**, tick two weighings and tap **View**. The screen shows the values side by side (oldest first, dates as mm/dd/yyyy), the difference for each in the **Δ** column and how many days apart they are. Ticking a third one replaces the first.
  - Details show each percentage in kg too, the **lean mass** (weight − fat) and the **basal metabolic rate** (Mifflin-St Jeor equation, from weight, height, age and sex; not shown under 18 or in pregnancy mode).
  - Body fat, water, muscle and bone are the scale's own bioimpedance estimates.
- **Calendar**: weigh days are marked with ✓, today is outlined and **upcoming reminder days** show a clock. It also shows the number of weigh days in the month and your streak. Tap a marked day to see its weighings.
- **+**: adds a weight typed by hand.

## 6. Notes

In **Add note »** (Measurement screen or a weighing's details) pick ready-made tags — fasting, after a meal, before or after workout, after the bathroom, with clothes, slept badly, stress, sick, alcohol, travel, period — and/or write up to 280 characters. Notes show in the details and in the CSV.

## 7. Reminders

On the **Reminders** tab, tap **New reminder**:

- **Time**.
- **Repeat**: daily; weekly (choose the days); every 2 weeks (one weekday, every other week); monthly (day 1–31 — day 31 becomes the last day of shorter months); or every N days.
- **For**: everyone or one profile. Optional **label**.

The first time, Android asks for notification permission. Reminders may arrive a few minutes late because the app does not use the exact-alarm permission. Use the switch next to each reminder to turn it on or off.

## 8. Scale

Open it with the Bluetooth icon at the top or menu ☰ › **Scale**. The people icon next to it opens **Profiles**.

- **Device**: model, firmware, battery and Wi-Fi.
- **Turn Wi-Fi off**: always visible, enabled only with the scale connected. Without the Qardio cloud, Wi-Fi on can lock the scale. **The app never turns Wi-Fi on.**
- **Profiles on the scale**: each profile stored on it. From each one's menu: **Update on the scale** or **Remove from the scale**.
- **Unknown profile** (created on another phone or the old app): use **Link to a profile** to attach it to an existing or new profile. The scale only stores a code, so you fill in the data; the display name appears as soon as that person weighs. The code is kept and the scale keeps recognizing the person.
- **Restore profiles on the scale**: appears after a reset, to write the app's profiles again with the same codes.
- **Set the scale clock**: writes the current time to the scale, if body composition stops showing.
- **Factory reset**: erases profiles, Wi-Fi and clock on the scale. The app history is kept. Asks twice.
- **Forget this scale**: to use another scale.

**Locked scale** (stuck on the start emoji, does not weigh): Wi-Fi is on without the cloud. Reset it with the button under the scale and set it up again in the app.

## 9. Profiles

Menu ☰ › **Profiles**. Tap a profile to edit it; changes go to the scale right away (or on the next connection). To delete, tap the trash icon — the app asks twice and also deletes that profile's history.

## 10. Settings

Menu ☰ › **Settings**:

- **Language**: phone language, Portuguese (Brazil) or English.
- **Theme**: phone setting, light or dark.
- **Lock with biometrics**: asks for fingerprint, face or the phone's screen lock when opening the app and after 30 seconds in the background.
- **Health Connect**: choose **one** profile (the phone owner). Each new weighing of theirs (from the scale or typed in) is sent to Health Connect **automatically** as soon as it is saved, where Google Fit, Samsung Health and other apps can read it. **Send history** is only needed once, for older weighings; sending again does not duplicate.
- **Export data (CSV)**: one profile or all, in the standard format or the Excel pt-BR format.


## 11. Side menu

At the bottom of the ☰ menu:

- **Log (testing)**: only in test versions. Shows everything the app exchanged with the scale, the connection flow and errors, with filters. Use **Copy log** to copy the text (or **Share log** to send it as a file) when something goes wrong. Each saved weighing gets a line explaining what the scale sent and, if body composition is missing, the likely reason. Wi-Fi passwords never appear.
- **About**: version, wellness notice, formula sources, credits and a link to the developer's GitHub.
- **Close app**: stops looking for the scale, turns off the app's Bluetooth and closes the screen. Android may keep the app idle in memory, as it does with any app, but it does not look for the scale or use battery. Reminders still arrive.

## 12. FAQ

- **The scale is not found**: check Bluetooth is on and tap the scale to wake it. On Android 11 or older, location must be on too.
- **My name does not show on the display**: check the profile's **Name on the display** (lowercase letters and digits only, up to 6).
- **No body fat/muscle**: the profile is in "Weight only" or "Pregnancy" mode, or you weighed with socks or shoes.
- **Why no visceral fat, metabolic age or protein?** Those depend on closed vendor formulas with no published study. Qilo only shows what the scale sends, simple arithmetic on those values and published equations.
- **The weighing has no body fat/muscle**: the scale did not measure impedance (socks, dry feet or feet off the metal plates). Weigh again barefoot, feet on the plates.
- **Where is my data?** Only on the phone. Uninstalling erases it; export a CSV first.
