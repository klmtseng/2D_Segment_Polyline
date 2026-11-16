# Segment Polyline 2D Demo

Interactive web demo for generating chained line segments with controllable parameters such as length **D**, point ratio *p/D*, segment count *n*, turning angle, line width and colour modes.

---

## ✨ Features

| Feature            | Description                                                                            |
| ------------------ | -------------------------------------------------------------------------------------- |
| **2-D polyline**   | Each new segment starts at a point *p* on the previous one and turns by a fixed angle. |
| **Ratio modes**    | Fixed, alternating, or random ratio between `ratio_min` and `ratio_max`.               |
| **Colour schemes** | Rainbow gradient, reverse gradient, or totally random.                                 |
| **Save as PNG**    | Download the current drawing as `polyline.png`.                                        |
| **Reset button**   | Instantly restore the defaults listed below.                                           |

---

## 🖥 Live Preview

Open `index.html` in any modern browser — no build step required.

---

## 🔧 Default Parameters

| Parameter               | Value         | Notes                                      |
| ----------------------- | ------------- | ------------------------------------------ |
| `D`                     | **100**       | Length of every new segment in pixels.     |
| `ratioMode`             | **fixed**     | `fixed`, `random`, `alternating`.          |
| `ratioMin` / `ratioMax` | **0.5 / 0.5** | Position of *p* along *AB* (0 → A, 1 → B). |
| `n`                     | **5**         | Number of segments.                        |
| `angle`                 | **30°**       | 2-D turning angle (counter-clockwise).     |
| `lineWidth`             | **2 px**      | Stroke thickness.                          |
| `colorMode`             | **rainbow**   | `rainbow`, `reverse`, `random`.            |

In `fixed` mode only `ratioMin` is used.

---

## 📂 Project Structure

```
├── index.html          # the whole demo (HTML, CSS and JS in one file)
├── README.md
└── LICENSE             # MIT
```

---

## 🛠 Development

No external dependencies are required.

```bash
git clone https://github.com/klmtseng/2D_Segment_Polyline.git
cd 2D_Segment_Polyline

# open index.html in your browser
```

Feel free to edit `index.html`; refresh the page to see your changes.

---

## 🤝 Contributing

Pull requests are welcome. For major changes please open an issue first to discuss what you would like to change.

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.
