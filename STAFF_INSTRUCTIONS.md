# How to Update Guest Names Daily

## Steps (takes under 2 minutes)

1. Open your phone or computer browser
2. Go to the motel website and add **/admin.html** at the end of the URL
   - Example: `https://yourmotelsite.com/rooms/admin.html`
3. Type the guest name next to each room number
4. Leave the box empty for vacant rooms
5. Tap **Save & Update Directory**
6. Done — the directory updates instantly for all guests

## Notes

- Works on any phone, tablet, or computer
- Multiple staff can update from different devices
- No login required (you can add one if desired)
- Changes appear immediately on the guest-facing page

## For the Host (one-time setup)

1. Upload all files in this folder to your existing hosted website in a subfolder (e.g. `/rooms/`)
2. Create a QR code pointing to `https://yoursite.com/rooms/index.html`
3. Print the QR code and place it at the front desk / room doors
4. Staff bookmark `https://yoursite.com/rooms/admin.html` on their phones

## Files in this project

| File | Purpose |
|------|---------|
| index.html | Guest-facing room directory (linked via QR code) |
| admin.html | Staff update page |
| r1.html – r10.html | Individual room pages (add your content here) |
