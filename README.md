# 🏍️ HIGHWAY RUSH – MOTO RIDER

**HIGHWAY RUSH – MOTO RIDER** is a next-gen, photorealistic 3D motorcycle traffic racing simulator built entirely in a single, self-contained HTML5 file using **Three.js (WebGL 2.0)** and the **Web Audio API**. 

Experience high-speed highway weaving across iconic Indian expressways and mountain passes with physically based rendering (PBR), dynamic weather systems, authentic Indian multi-axle traffic, and an unobstructed rider-eye-level cockpit view.

---

## 🎮 Play Live
👉 **[Click Here to Play in Your Browser](https://dhairymakwana26.github.io/highway-rush/)**  
*(Replace `yourusername` with your actual GitHub username after enabling GitHub Pages)*

---

## ✨ Key Features

### 🏁 1. Dual Camera System
* **First-Person Cockpit View:** True rider eye-level camera featuring functional clip-on handlebars, armored leather racing gloves, sculpted fuel tank, side wing mirrors, and a live digital TFT instrument cluster (real-time KM/H speedometer, RPM bar, and 6-speed gear indicator).
* **Third-Person Chase Camera:** Dynamic chase perspective showcasing full motorcycle aerodynamics, rotating alloy rims, suspension travel, cornering lean physics, and an articulated 3D racing rider.

### 🏍️ 2. Interactive 3D Garage (8 Unlockable Motorcycles)
Inspect bikes with 360° touch/mouse rotation and zoom, compare performance stats (Speed, Acceleration, Braking, Handling), and unlock upgrades using earned coins:
1. **Sport Bike** – Balanced entry-level highway tourer
2. **Street Bike** – Agile urban commuter
3. **Naked Bike** – High-torque streetfighter
4. **Adventure Bike** – Tall-stance tourer built for rough mountain passes
5. **Superbike** – Aerodynamic track-ready machine
6. **Racing Bike** – High-revving circuit build
7. **Premium Superbike** – Carbon-fairing flagship with radial Brembo-style calipers
8. **Extreme Racing Bike** – Ultimate hyper-velocity prototype

### 🛣️ 3. Three Playable Indian Highway Worlds
* **City Highway (Mumbai–Pune Expressway):** Glass-curtain skyscrapers, elevated concrete flyovers, overhead green highway sign gantries (*Mumbai / Pune / Nashik*), and dense expressway traffic.
* **Mountain Road (Grand Peak / Malshej Ghat):** Displaced 3D granite rock cliffs, conifer pine forests, rock-bored illuminated highway tunnels, and sharp hillside barriers.
* **Snow Highway (Rohtang Alpine Pass):** Snow-capped peaks, icy specular road surfaces, and alpine winter visibility.

### 🚛 4. 18 Authentic 3D Traffic Vehicles
Smart AI traffic with lane-changing behavior, turn indicators, illuminated night headlights, and active brake lights across 4 vehicle classes:
* **5 Cars:** Indian Hatchback, Metallic Executive Sedan, Muscular Highway SUV, Luxury Saloon, and GT3 Sports Coupe.
* **3 Full-Size Indian Buses:** Multi-axle AC Sleeper Coach (*Zingbus Maxx* style), Intercity Express (*Shivneri* style), and Luxury Charter Coach (*Gujarat Travels* style).
* **5 Heavy Cargo Trucks:** White Tilt-Cab Container Truck (*Eicher Pro* style), National Permit Tarpaulin Truck, Timber Log Flatbed Carrier, Cylindrical Fuel Tanker, and 4-Axle Heavy Trailer.
* **5 Traffic Motorcycles:** Sport, Naked, Cruiser, Adventure (with aluminum panniers), and Commuter bikes with 3D riders.

### 🌧️ 5. Dynamic Time of Day & Weather Engine
* **Time Modes:** Sunny Day, Golden-Hour Sunset, Soft Sunrise, and Night Mode (active streetlights & vehicle headlight beams).
* **Weather Presets:** Clear Sky, Rain (wet asphalt reflections & tire spray mist), Heavy Storm (lightning flashes & dense downpour), Volumetric Fog, and Falling Snow.

### ⚙️ 6. Graphics & Performance Presets
* **4 Scalable Presets:** `LOW`, `MEDIUM`, `HIGH`, and `ULTRA` (adjusting shadow map resolution, pixel ratio, draw distance, and particle density).
* **PBR Rendering Pipeline:** `ACESFilmicToneMapping`, procedural HDRI environment reflections, 4K-style procedural asphalt bump/roughness maps, and zero external asset dependencies.

---

## 🕹️ Controls

### Desktop (Keyboard)
| Key | Action |
| :--- | :--- |
| **W** / **Up Arrow** | Accelerate (Throttle) |
| **S** / **Down Arrow** | Brake / Slow Down |
| **A** / **Left Arrow** | Steer / Lean Left |
| **D** / **Right Arrow** | Steer / Lean Right |
| **Spacebar** | Emergency Dual-Disc Brake |
| **C** | Switch Camera (1st-Person Cockpit / 3rd-Person Chase) |
| **P** / **ESC** | Pause Game |

### Mobile / Touchscreen
* **Bottom-Right Button:** Hold **THROTTLE** to accelerate.
* **Bottom-Left Button:** Hold **BRAKE** to decelerate.
* **On-Screen Steering:** Left / Right directional controls.

---

## 🛠️ Tech Stack
* **3D Engine:** [Three.js](https://threejs.org/) (WebGL 2.0, `MeshPhysicalMaterial`, `PMREMGenerator`, `ExtrudeGeometry`)
* **Audio Engine:** Native Web Audio API (procedural multi-oscillator engine RPM synthesis, gear shifts, wind rush, brake screech, and crash acoustics)
* **Storage:** `localStorage` persistence for coins, unlocked bikes, high scores, level progression, and user settings
* **Architecture:** 100% self-contained single-file `index.html` (no build step or external server required)

---

## 🚀 Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/highway-rush-moto-rider.git](https://github.com/yourusername/highway-rush-moto-rider.git)
