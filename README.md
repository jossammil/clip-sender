# CrowPanel Clip Sender

A single-page Web Bluetooth sender for a CrowPanel knob pad running the CLIP firmware: paste text, send it to
the board over Bluetooth, and the board types it out (on its USB or Bluetooth keyboard) when you press its knob.

Open **https://jossammil.github.io/clip-sender/** in Chrome or Edge (Windows, macOS, ChromeOS, Android),
in Chromium on Linux with `chrome://flags/#enable-experimental-web-platform-features`, or in the Bluefy
browser on iPhone/iPad.

The page talks only to the board over Bluetooth; it has no server side and stores nothing but the board's
sender token in your browser. A new browser has to enter the 6-digit code shown on the board once.
