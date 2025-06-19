# Segment Polyline 2D/3D Demo

Interactive web demo for generating chained line segments with controllable parameters such as length **D**, point ratio *p/D*, segment count *n*, turning angle, colour modes and (optionally) 3‑D rotation.



---

## ✨ Features

| Feature                                           | Description                                                        |
| ------------------------------------------------- | ------------------------------------------------------------------ |
| **2‑D mode**                                      | Draws a poly‑line on the *XY* plane only.                          |
| **Optional 3‑D mode**                             | Toggle to extrude each new segment in 3‑D, drag mouse to rotate.   |
| \*\*Flexible \*\*\`\`                             | Fixed, alternating, or random ratio between two bounds.            |
| **Randomised ****\`\`**** & angle** (3‑D version) | Per‑segment length and yaw/pitch chosen from user‑supplied ranges. |
| **Colour schemes**                                | Rainbow gradient, reverse gradient, or totally random.             |
| **Animation**                                     | Optionally render segments one‑by‑one for a drawing effect.        |
| **Reset button**                                  | Instantly restore the defaults listed below.                       |

---

## 🖥 Live Preview

Open \`\` in any modern browser — no build step required.

---

## 🔧 Default Parameters

| Parameter               | Value         | Notes                                      |
| ----------------------- | ------------- | ------------------------------------------ |
| `D`                     | **100**       | Length of every new segment in pixels.     |
| `ratioMode`             | **fixed**     | `fixed`, `random`, `alternating`.          |
| `ratioMin` / `ratioMax` | **0.5 / 0.5** | Position of *p* along *AB* (0 → A, 1 → B). |
| `n`                     | **5**         | Number of segments.                        |
| `angle`                 | **30°**       | 2‑D turning angle (counter‑clockwise).     |
| `lineWidth`             | **2 px**      | Stroke thickness.                          |
| `colorMode`             | **rainbow**   | `rainbow`, `reverse`, `random`.            |

---

## 📂 Project Structure

```
├── index.html          # main demo (English UI)
├── assets/
│   └── screenshot.png  # optional screenshot for README
└── LICENSE             # choose your licence (MIT by default)
```

> **Note**: Chinese‑language versions of the demo are kept in the *canvas* history for reference.

---

## 🛠 Development

No external dependencies are required.

```bash
# clone
$ git clone https://github.com/<your‑user>/segment‑polyline.git
$ cd segment‑polyline

# open index.html in your browser
```

Feel free to edit `index.html`; changes are hot‑reloaded on refresh.

---

## 🤝 Contributing

Pull requests are welcome. For major changes please open an issue first to discuss what you would like to change.

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

