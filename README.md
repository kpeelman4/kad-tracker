# Kadoatery Timer

A simple timer for tracking Neopets Kadoatery refresh windows.

## Credit

**This entire project was created by Claude (Anthropic's AI assistant).** I provided feedback on design preferences and functionality requests. All code, styling, and features were written by AI.

## Features

- Tracks 10 refresh windows (first at +35 min, then 9 more at +7 min intervals)
- Alarms 30 seconds before each refresh window
- 5 different alarm sound options
- Countdown displayed in browser tab
- Copy/paste formatted times for posting on Neopets boards

## How to Use

1. Download the `kad-timer.html` file
2. Open it in your browser (Chrome, Firefox, Safari, etc.)
3. Enter the last refresh time (including seconds)
4. Pick an alarm sound
5. Click "Begin"
6. You will hear an alarm 30 seconds before each of the 10 refresh windows

## Alarm Sounds

- **Soft Beeps** - Default, gentle
- **Loud Alert** - Louder, triple beeps
- **Buzzer** - Harsh buzzing
- **Chimes** - Musical tones
- **Siren** - Alternating alarm

## Board Post Generator

Click "Copy for Board" to copy formatted text like:

```
last rf @ 9:05:27 AM

main pending rf @ 9:40, :47, :54, 10:01, :08, :15, :22, :29, :36, :43
```

Shows times up to 90 minutes after the main pending refresh.

## Technical Stuff

- Single HTML file, no installation needed
- Uses Web Audio API for alarms
- No data collection or storage
- Works on desktop browsers (has not been tested on mobile)

## Notes

- You need to click "Begin" for audio to work (browser security thing)
- The file works completely offline once you have it
- Bookmark it for easy access (don't change the file location after saving bookmark)
- Only tracks one feeding 'cycle' at a time per browser window.  If you want to track minis, open multiple browser tabs.

## Issues?

If the alarm doesn't sound, make sure:
1. Your browser allows audio
2. You clicked "Begin" (can't play sound without user interaction)
3. Your volume is up

---

**Again, all credit to Claude AI.** This was an iterative design process where Claude wrote all the code based on user feedback about colors, layout, and features.
