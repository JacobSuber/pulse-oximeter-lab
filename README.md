# Pulse Oximeter Lab — Interactive Clinical Simulator

A free browser-based learning activity for beginning healthcare students. The website is built from a seven-step introduction to using a fingertip pulse oximeter. It teaches basic procedure, patient safety, accuracy limitations, and documentation using **fictional** patient cases.

## Open the website

https://jacobsuber.github.io/pulse-oximeter-lab/

## Main sections

- **Learn:** Seven stages from device preparation through safety precautions, based on the provided guide.
- **Practice:** A hands-on virtual examination instead of a checklist. Participants inspect a device, install batteries, clean a sensor by dragging a pad, explain the procedure, obtain consent, prepare the patient, choose a finger, open and position the clip, power on the device, wait for a stable simulated reading, select a clinical response, enter a chart, remove the clip, and finish hygiene.
- **Quiz:** Ten questions about terminology, technique, accuracy, and safety.

## How the usability tester should use it

1. Open the website on a laptop or phone.
2. Select **02 Practice**, then choose **Routine wellness visit**.
3. Follow the screen prompts **without the creator telling you where to click**.
4. Complete each physical interaction and decision. The **Next stage** button stays disabled until required actions are successful.
5. Try an incorrect choice to see whether the guidance helps you recover.
6. Complete the patient chart, finish aftercare, and view your practice score.
7. Copy the session summary and describe any confusing or unclear directions.
8. Repeat with a cold-hands or low-oxygen scenario if desired.

**Dragging alternatives:** Focus a movable item using the keyboard, move it with the arrow keys, then press Enter to release over the highlighted target. Some steps require several clicks, such as dispensing and rubbing simulated hand sanitizer.

## Files

- `index.html` — complete standalone site with HTML, CSS, and JavaScript; no package installation required.
- `README.md` — project information and usability test directions.

## Publishing

To update the GitHub Pages site, upload/replace `index.html` in the root of the `main` branch of the `pulse-oximeter-lab` repository and commit the change. With Pages already enabled for `main` + `/(root)`, deployment will update automatically. Refresh the live site (Ctrl+Shift+R if the old file is cached).

## Safety and accuracy

**For education only.** All patient cases and monitor readings are simulated. This game does not measure a real person’s oxygen saturation or pulse, certify clinical competency, diagnose conditions, or replace hands-on supervision. Real patient assessments follow the device manufacturer’s instructions and clinical protocols; severe symptoms should be escalated immediately even when the number on a pulse oximeter looks normal.

Sources included on the website: FDA *Pulse Oximeter Basics* and MedlinePlus *Pulse Oximetry*.
