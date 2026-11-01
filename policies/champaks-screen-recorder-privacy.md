# Champak's Screen Recorder — Privacy Policy

**Effective date:** 1 November 2026

Champak's Screen Recorder is an Android utility for recording software demonstrations and tutorials. The app starts screen recording only after the user approves Android's screen-capture permission prompt for each session.

## Screen and microphone recording

The app records the selected screen or app. If the user enables narration, it requests microphone permission and records the microphone audio into the local video. The user can disable narration. Screen and voice recordings may contain sensitive personal content, including notification previews; please hide passwords and private information before starting.

## Local storage and data collection

Recordings are saved as MP4 files in the device's **Movies/ChampaksScreenRecorder** folder. Version 1.0.0 has no user accounts, Internet permission, cloud uploads, analytics or advertising SDK. We do not collect, transfer or sell video and audio recordings to our servers. The user is responsible for the recordings they create.

## Sharing, retention and deletion

Recordings remain on the device until the user deletes them using the built-in Library or the device's media manager. A user can choose to share videos through Android's share sheet; the destination app or service then applies its own privacy policy. Deleting the local file does not remove copies previously shared.

## Permissions and limits

Screen recording requires Android's per-session MediaProjection consent. Microphone access is requested when narration is selected. Android may ask for notification permission for recording controls; it is optional. Android's foreground service permissions allow a visible, user-initiated recording to continue after switching apps. The app does not request contacts, location, camera or broad file-storage access.

Certain apps and sensitive content use Android protections that restrict screen recording. Users should avoid recording other people's private information without permission.

## Optional on-screen teaching annotations and visible taps

From version 1.2.0, the always-visible recording toolbar (red REC timer, Pause/Resume, Stop & Save, Pen, Circle and Arrow tools) requires Android's **Draw over other apps** special access. Recording does not start without this permission, and the toolbar is removed when recording ends. The drawing toolbar is mandatory during recording and may be moved vertically, but not hidden while recording. This permission allows a visible overlay for instruction; it does not read or upload information from other apps. Tap dots are controlled by the user's Android **Show taps** Developer options setting, not by a background accessibility or input-monitoring service. The user can disable the floating teaching tools at any time. Annotations are included in the screen video saved locally when they are visible to MediaProjection.

## Entire display recording in v1.2.3

This teaching-focused version requests Android's **entire default display** for each recording, so that app transitions, pop-ups, newly opened windows and other displayed apps can be captured together. Android asks for screen-recording consent each session. Display capture can include sensitive notifications or other private material; users should hide sensitive information before approving recording. Android may restrict or blank protected windows. Recording is saved locally unless the user chooses to share it.

## Hybrid recording and floating controls (v1.2.5)

The user can dock the floating recording controls at the top or bottom and collapse the editing tools. The red recording indicator, Pause/Resume and Stop remain accessible while recording. The control window no longer uses the secure-window exclusion that caused black output on some Android phones.

In full-display mode, video is cropped and resized along the toolbar edge so the controls are absent from the exported MP4. **This removes part of the top or bottom of the visible screen**, even though it remains visible to the user on the phone. An optional experimental smart-repair mode may insert recently captured unobstructed pixels into a covered region. It cannot reliably recover moving or previously unseen content and falls back to cropping. Users should review the exported video before sharing.

On Android 14 and later, the user may choose Android's selected-app capture, which records one chosen app rather than new windows from other apps. App sharing depends on the Android system's permission dialog. User-drawn pen, circle and arrow annotations are added to the encoded MP4 frames independently of the floating toolbar.

The app continues to process screen and optional microphone recordings locally, and protected Android windows remain subject to system restrictions.

## Future changes

If we add Internet services, ads, analytics, cloud storage or other data processing, we will update this policy before deploying those features.

**Developer:** Champak Roy — Programmer's Picnic / Learn With Champak.

**Contact:** https://www.learnwithchampak.live/p/contact.html
