# Editing Guide — Lantern Madurai (Dr. Rahul Vishnu G & Dr. Meghana Kattimani)

Customer customization for `lantern-madurai` (Madurai lanterns & temple theme with GSAP parallax, ring ceremony photo, Ghibli haldi illustration, and Annul Maelae background music).

## Customer Data

Configured in `editable/wedding-data.js`:
- **Couple**: Dr. Rahul Vishnu G & Dr. Meghana Kattimani
- **Events**:
  - Haldi: 11 December 2026 (5:30 PM) · Sangeeth Wedding Village, Madurai
  - Reception: 12 December 2026 (6:30 PM) · T.S. Rajam Auditorium, Madurai
  - Muhartham: 13 December 2026 (9:00 AM) · T.S. Rajam Auditorium, Madurai
- **Venue**: T.S. Rajam Auditorium, SH 72, Chinna Chokkikulam, Madurai, Tamil Nadu 625002
- **Audio**: Annul Maelae - Violin Cover from 0:16 (`editable/assets/bgm.mp3`)
- **Footer**: "Rahul and Meghana" · 13 December 2026 · Madurai
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
