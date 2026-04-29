# PhotoBeam

Send photos from your iPhone straight to your own computer over local WiFi —
no cloud account, no internet, no third party in the middle.

PhotoBeam is two pieces that work together:

- **PhotoBeam for iPhone** — picks photos from your camera roll and sends
  them to your computer.
- **PhotoBeam Receiver** — a small free app that runs on your Windows, Mac,
  or Linux computer. Shows a QR code, accepts incoming photos, drops them
  into a folder you choose.

## How it works

1. Run PhotoBeam Receiver on your computer. It shows a QR code.
2. Open PhotoBeam on your iPhone and scan the QR code (one time only).
3. Pick photos and tap **Send** — or turn on **Auto mode** and every new
   photo you take is forwarded automatically in the background.

Photos arrive at full resolution with their original filenames preserved,
into whichever folder you picked on your computer.

## Download

- **iPhone app:** *(TestFlight link goes here once your build is approved)*
- **Receiver for Windows / Mac / Linux:** see the
  [Releases](../../releases) page.

## Need help?

- **Bug reports & feature requests:** open an
  [issue](../../issues) — please include your iPhone model, your iOS
  version, your computer's operating system, and roughly when the problem
  happened.
- **Email:** `shulemfreund360@gmail.com`

We typically reply within a couple of days.

## Privacy

PhotoBeam never uploads anything to a server we control. Your photos travel
directly from your phone to your computer over your local WiFi network. We
collect no analytics, no telemetry, and no account information. There is no
sign-up.

## Requirements

- iOS 17 or later
- A Windows, Mac, or Linux computer on the same WiFi network as your phone
- Photo Library permission (full access recommended for Auto mode)
- Local Network permission (required to reach your computer)
- Notifications permission (optional — only used to confirm background syncs)

## Status

Currently in private beta on TestFlight. One-way (iPhone → computer) only.
Computer → iPhone is on the roadmap.
