# Editing Guide — Lantern Madurai (Dr. Rahul Vishnu G & Dr. Meghana E)

Customer customization for `lantern-madurai` (Madurai lanterns & temple theme with GSAP parallax, ring ceremony photo, Ghibli haldi illustration, and Ed Sheeran - Perfect audio).

## Customer Data

Configured in `editable/wedding-data.js`:
- **Couple**: Dr. Rahul Vishnu G & Dr. Meghana E
- **Events**:
  - Haldi: 11 December 2026 (10:00 AM)
  - Reception: 12 December 2026 (6:30 PM)
  - Muhartham: 13 December 2026 (9:00 AM)
- **Venue**: T.S. Rajam Auditorium, SH 72, Chinna Chokkikulam, Madurai, Tamil Nadu 625002
- **Audio**: Ed Sheeran - Perfect (`editable/assets/perfect.mp3`)
- **Photos**:
  - Ring ceremony photo: `editable/assets/couple-ring-ceremony.jpg`
  - Ghibli Haldi artwork: `editable/assets/haldi-ceremony-ghibli.png`

## Assets

Customer replacement files in `editable/assets/`:
- `editable/assets/aarav-ananya-opening.mp4` — Opening video gate
- `editable/assets/entrance-first-frame.png` — First frame poster for video
- `editable/assets/invitation-reference.png` — Hero illustrated scene
- `editable/assets/couple-ring-ceremony.jpg` — Ring exchange ceremony photo
- `editable/assets/haldi-ceremony-ghibli.png` — Haldi Ghibli illustration
- `editable/assets/og-aarav-ananya.png` — Footer art & social share image
- `editable/assets/perfect.mp3` — Ed Sheeran "Perfect" background music

## Testing

```bash
node --check editable/wedding-data.js
```
Open `http://localhost:9014/` in browser.
