# Discord Time Format Generator

A simple web tool that generates Discord timestamp format for time ranges on the current date.

## Overview

This tool allows you to quickly create Discord-compatible timestamp ranges that will display local times for all users. It takes two time inputs (start and end time) and converts them to Discord's `<t:timestamp:t>` format.

## Features

- Set custom start and end times through simple time picker inputs
- Default times of 8:00 AM and 4:00 PM for quick generation
- Single-click generation of formatted Discord timestamps
- Copy to clipboard functionality for easy pasting into Discord
- Clean, responsive interface that works on mobile and desktop devices
- No installation or dependencies required - runs entirely in the browser

## How to Use

1. Open the HTML file in any modern web browser
2. Set your desired start time using the "Start Time" input field
3. Set your desired end time using the "End Time" input field
4. Click the "Generate" button to create the Discord timestamp format
5. Click the "Copy to Clipboard" button to copy the result
6. Paste the copied text into your Discord message

## Discord Timestamp Format

This tool generates timestamps in the format: `<t:1234567890:t> - <t:1234567890:t>`

When pasted into Discord, this will display as a time range using each user's local time zone.

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses the browser's Date API to calculate Unix timestamps
- Leverages the Clipboard API for copy functionality
- No external dependencies or internet connection required
- Fully client-side - no data is sent to any server

## Compatibility

Works with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Credits

This tool was created based on a PowerShell script conversion to help Discord users easily create time ranges for events or schedules.
