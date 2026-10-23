# Armies-of-Starbies

## About my Starbie:

My Starbie is a tiny handheld pet inspired by The Amazing World of Gumball's episode: The Console. Instead of the guide's star shape, I designed my PCB as a rounded rectangular board with a direction pad, a "Player HD" logo (my username sometimes) under the screen, and a cool pattern at the back of the circuit board.

It runs on a XIAO ESP32-C3 and has:
- A 0.96" OLED screen where my pet lives.
- An MPU6050 motion sensor so the pet reacts when you move it.
- A DHT11 sensor that measures temperature and humidity.
- A custom 32x32 pixel sprite that I drew myself.

# Controls

| Control | What it does |
|---|---|
| Button 1 (SW1) | Opens the action menu. Press again to choose the highlighted action. |
| Tilt (in the menu) | Rolls the ball toward an action: up = NAP, right = PLAY, down = FEED, left = PET |
| Button 2 (SW2) | Shows or hides the stats screen (Joy, Energy, Fullness, temperature and humidity) |
| Shake | Wakes the pet if it's napping, and gives it a little boost of joy |

# Actions

| Action | What happens | Stats |
|---|---|---|
| NAP | The pet sleeps for 48 seconds with floating Zs | Energy ↑↑, Fullness ↓ |
| PLAY | The pet runs two fast laps, with hearts | Joy ↑↑, Energy ↓, Fullness ↓ |
| FEED | The pet wiggles and jumps | Fullness ↑↑ |
| PET | The pet jumps and shows hearts | Joy ↑ |

When you're not doing anything, the pet wanders across the screen with a
little sparkle behind it.


# What I used:
- KiCad's PCB editor
- KiCad's Schematic editor
- Piskel (to make sprite)
- Image2cpp

# Images:
<img width="870" height="574" alt="Screenshot 2026-10-11 at 00 35 44" src="https://github.com/user-attachments/assets/8ad9e9da-a6c3-44f2-b219-2594b4b80364" />
<img width="478" height="648" alt="Screenshot 2026-10-11 at 00 35 59" src="https://github.com/user-attachments/assets/51e53fc5-fd8f-4792-8013-03476562196e" />
<img width="469" height="633" alt="Screenshot 2026-10-11 at 00 36 13" src="https://github.com/user-attachments/assets/7093e688-dd34-425f-96ff-0e1bb9781a29" />
<img width="469" height="509" alt="Screenshot 2026-10-11 at 00 36 49" src="https://github.com/user-attachments/assets/03190009-a487-42dc-b672-237d8b416354" />
<img width="399" height="641" alt="Screenshot 2026-10-21 at 10 49 06" src="https://github.com/user-attachments/assets/f77b7c94-d137-42f4-8fb9-f545d4401041" />
<img width="389" height="601" alt="Screenshot 2026-10-21 at 10 50 02" src="https://github.com/user-attachments/assets/642c22b4-9288-4ff7-b035-b054433a1a16" />
<img width="509" height="593" alt="Screenshot 2026-10-21 at 10 50 31" src="https://github.com/user-attachments/assets/a77204a9-f7e9-49f0-ae51-111a84461ddd" />


# Sprite I made:
<img width="480" height="564" alt="Screenshot 2026-10-21 at 10 44 50" src="https://github.com/user-attachments/assets/41e092cb-69af-49d5-bd60-7a55c3a57b6b" />


# BOM Table:
Item,Qty,Supplier,Cost/item,Total Cost,link
XIAO ESP32 C3,1,Seeedstudio,$4.90,$4.90,https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html
0.96 OLED,1,Amazon,$5.99,$5.99,https://www.amazon.com/dp/B0GBVWBWCR
MPU6050,1,Amazon,$2.19,$2.19,https://www.amazon.com/dp/B0943SGP34
DHT11,1,Amazon,$3.78,$3.78,https://www.amazon.com/dp/B0BLG7R99R
MX Switches,1,Amazon,$4.99,$4.99,https://www.amazon.com//dp/B0FQP8VYX4
Keycaps,1,Amazon,$2.88,$2.88,https://www.amazon.com/dp/B0CQ2VLMVY
PCB,1,JLCPCB,$7.36,$7.36,https://www.jlcpcb.com/
Estimated total shipping,1,,,$0.00,
