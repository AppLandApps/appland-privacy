# VISCERA: Privacy Policy and Support

Developer: Stefan Almqvist (AppLand)

App: VISCERA

Last updated: 2026-11-01

Contact: viscera@applandapps.com

## Privacy Policy

### Short version

VISCERA does not collect, store, or transmit any personal data. There are no accounts, no analytics, no advertising, and no third-party tracking. Everything you make stays on your device unless you choose to share it.

### What we collect

Nothing. VISCERA does not collect personal information, usage data, device identifiers, or location. There are no servers behind the app, and it does not send your data anywhere.

### Microphone

VISCERA can record sound through your device microphone so you can use your own voice or surroundings as source material. Microphone access is used only while you are actively recording, and only after you grant permission. Recorded audio is written to local storage on your device and is never uploaded or shared by the app. You can deny or revoke microphone access at any time in the iOS Settings app, in which case recording features are simply unavailable. You can still import audio files.

### Motion

VISCERA reads your device's motion sensors so that tilting the device can change the sound. Motion readings are used live while you play and are never stored or sent anywhere.

### Bluetooth

VISCERA uses Bluetooth only to connect wireless MIDI keyboards and controllers that you pair in its MIDI settings. It does not store or send anything about your Bluetooth devices.

### Network MIDI

Network MIDI is off until you turn it on in the MIDI settings. While it is on, devices on your local Wi-Fi network can connect to VISCERA and play it. MIDI stays on your local network and never goes to the internet. Turn it off to stop accepting connections.

### Your audio and configs

Any sounds you record or import, configs you save (each with its audio, settings, and loop or MIDI file), and audio you export stay on your device, and in your own iCloud or Files backups if you choose to save them there. VISCERA has no server access and cannot see or retrieve this content.

The VISCERA Audio Unit, installed together with the app, opens your saved configs from a folder on your device that the app and the plugin share. When you use VISCERA inside a music app, that app saves VISCERA's sounds and settings in its own project.

### Purchases

VISCERA is a paid app with a one-time price. There are no in-app purchases and no subscriptions. The purchase is processed entirely by Apple through the App Store. VISCERA never sees or stores your payment information. Apple's handling of your purchase is governed by the Apple Privacy Policy.

### No tracking or advertising

VISCERA contains no advertising, no analytics or measurement SDKs, and no third-party trackers. It does not use the Advertising Identifier (IDFA) and does not request permission to track you across apps or websites.

### Children

VISCERA does not collect data from anyone, including children. It is not directed at children under 13, and it produces loud, intense audio. Headphones and adult discretion are recommended.

### Data retention and deletion

All of your content lives only on your device, so you are in full control of it. Clearing a slot or deleting a config in the app removes it. Exported WAV files are kept in the Files app, under On My iPhone (or On My iPad) → VISCERA, until you delete them there. Deleting the app removes all of its local data, including the folder it shares with the Audio Unit. Copies you have shared or saved elsewhere stay where you put them.

### Third parties

The only third party involved is Apple, which distributes the app and processes the purchase. VISCERA integrates no other third-party services. When you use VISCERA as a plugin, the music app you use it in has its own privacy policy.

### Changes to this policy

If this policy changes, the updated version is posted at this URL with a new Last updated date. Material changes are also noted in the app release notes.

### Privacy contact

viscera@applandapps.com

---

## Support and FAQ

Need help, found a bug, or have a feature request? Email viscera@applandapps.com and include your device model and iOS or macOS version so we can help faster. We aim to reply within a few business days.

### I do not hear anything

Check these in order:

1. Turn up the volume and check which output the sound goes to (speaker, headphones or Bluetooth).
2. Load or record a sound first. VISCERA plays back a sound you provide, so with nothing loaded there is nothing to hear.
3. Touch and hold the pad. Sound is generated as you play.
4. If you are recording, confirm you granted microphone permission in Settings → VISCERA → Microphone.
5. In a music app, load a sound in the plugin first (tap an empty slot, or CONFIGS), and check that its track gets notes: select or arm it, or route your keyboard to it.

### How do I get a sound into the app?

Tap the red mic in the middle of the bottom bar to record, and tap it again to stop. The take goes into the first empty slot, or replaces the selected one when all four are full. Or tap an empty slot (X1 to X4) at the top to import an audio file. You can also send an audio file to VISCERA from another app with Share or Open In. Up to four sounds, one per slot.

### How do I record my own voice?

Grant microphone permission when prompted, or later in Settings → VISCERA → Microphone. Tap the red mic in the middle of the bottom bar, make your sound, and tap it again to stop. It becomes the source you play and transform.

### How do I play it?

Touch and hold the pad. Left to right is where in the recording you are, and up and down moves whatever that slot's Y lane controls. Tilting the device left and right drives each slot's two TILT lanes. Use as many fingers as you like. Tap a loaded slot to choose what its lanes control, and tap i at the bottom right for the full guide.

### How do I export what I make?

Tap the red cassette to the right of the mic to record everything you hear, and tap it again to stop. VISCERA saves a 24-bit, 48 kHz WAV file and opens the share sheet, so you can save it to Files or send it to another app. The file is also kept in the Files app, under On My iPhone (or On My iPad) → VISCERA.

### How do I save my setup?

Tap SAVE at the top to keep all four slots, with their audio, settings, and loop or MIDI file, as a config. You can keep up to 12. OPEN brings one back, and swiping left on a config deletes it. In the plugin, CONFIGS opens the same configs inside your music app.

### How do loops and MIDI files work?

Tap LOOP at the bottom left of the pad and play, then tap it again to close the loop. What you played is recorded as sound, tilt and all, and repeats while you play over it. Tap LOOP to stop it and again to play it, and tap × to clear it. Loops can be up to a minute long.

Tap MIDI next to LOOP to open a MIDI file (.mid): it plays your loaded sounds. Press and hold LOOP to record a new loop or, for a MIDI file, to pick a Part (one instrument from it; a melody or bass line works best, since VISCERA plays six MIDI notes at once), set its Speed or turn off Loop the file.

### How do I connect a MIDI keyboard?

- USB: plug it in, with an adapter if your device needs one.
- Bluetooth: tap the keys button at the top, then Bluetooth MIDI devices.
- Wi-Fi: turn on Network MIDI (Wi-Fi) in the same place, then connect from your computer (on a Mac, in Audio MIDI Setup → MIDI Network Setup).

Every key plays all loaded slots at that note. Velocity, pitch bend, sustain, the mod wheel, aftertouch, breath control and MPE all work, and the keys button shows the full MIDI map.

### How do I use VISCERA in GarageBand, Logic Pro or another music app?

The VISCERA Audio Unit comes with the app; there is nothing else to install. Open VISCERA once after installing or updating, then add it as an instrument:

- GarageBand: New song → swipe to External → Audio Unit Extensions → VISCERA.
- Logic Pro for iPad: New track → Software Instrument → tap the instrument → Audio Units (at the bottom of the list) → AppLand → VISCERA.
- AUM: Tap + on a channel → Audio Unit Extensions → Instruments → AppLand: VISCERA.
- Cubasis: Add an instrument track → instrument → AU Instruments → VISCERA.
- Loopy Pro: Add an Audio Unit → Instruments → VISCERA.

In the plugin, tap an empty slot to load a sound, or CONFIGS to open a config you saved in the app. Play it from your music app's keyboard, a MIDI keyboard, or the pad. Your project remembers VISCERA's sounds and settings.

Not in the list? Open VISCERA once, close the music app completely (swipe it away) and open it again. Still missing: restart the device.

### Does VISCERA work on a Mac?

Yes, on a Mac with Apple silicon (M1 or later). Get VISCERA from the Mac App Store with the same Apple ID (it is the same purchase) and open it once. It then works as an instrument in Logic Pro, GarageBand, MainStage, Ableton Live (11.3 or later) and REAPER:

- Logic Pro, GarageBand, MainStage: Add a Software Instrument track → AU Instruments → AppLand → VISCERA.
- Ableton Live: Turn on Audio Units v3 in Settings → Plug-Ins, then Browser → Plug-Ins → Audio Units → AppLand → VISCERA. For MPE, right-click the device and choose Enable MPE Mode.
- REAPER: Insert a virtual instrument → AU → AppLand: VISCERA.

Cubase, Pro Tools and Bitwig Studio cannot load Audio Units from App Store apps, and VISCERA does not run on Intel Macs or Windows.

### Is there a subscription or in-app purchase?

No. VISCERA is a one-time purchase with everything included. On a new iPhone, iPad or Mac, download it again from the App Store with the same Apple ID at no charge.

### Does VISCERA work offline?

Yes. VISCERA runs entirely on the device and needs no internet connection. Network MIDI uses only your local Wi-Fi network.

### Does VISCERA collect my data or send my recordings anywhere?

No. See the Privacy Policy above. Nothing is collected, and your audio never leaves your device unless you choose to export and share it yourself.

### It is very loud

VISCERA is built to produce intense sound. Start at a low volume, especially on headphones, and raise it gradually. Each slot also has its own Gain: tap a loaded slot and pull Gain down if that slot is much louder than the rest.

### Bug reports and feature requests

Email viscera@applandapps.com with a short description, your device model, and your iOS or macOS version. For the plugin, include the music app and its version too. Screenshots or a short screen recording help a lot.
