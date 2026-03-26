# Animal Intrusion Detection Dataset (Duck Class Prototype)

## 📌 Project Overview
This project is a bounding-box annotated dataset designed to simulate animal intrusion detection scenarios in surveillance systems. 

The dataset focuses on duck detection as a prototype for identifying animals entering restricted or sensitive areas such as roads, farms, and industrial zones.

---

## 🎯 Objective
To create a structured and consistent dataset that demonstrates annotation quality, handling of real-world scenarios, and readiness for model training pipelines.

---

## 🧠 Scenarios Covered
- Single duck (clear visibility)
- Multiple ducks (crowded scenes)
- Occlusion (partially visible ducks)
- Small and distant objects
- Complex backgrounds (grass, water, clutter)
- Motion blur / low clarity cases

---

## 🏷️ Annotation Guidelines

### Object Definition
- Only real ducks are annotated
- Ignore reflections, drawings, or non-real objects

### Bounding Box Rules
- Boxes tightly enclose the visible head and body
- Minimal background included

### Occlusion Handling
- Partially visible ducks are annotated
- Only visible parts are boxed (no guessing hidden areas)

### Small Object Policy
- Small but identifiable ducks are annotated
- Extremely unclear objects are ignored

### Multiple Objects
- Each duck is labeled separately
- No grouping of multiple ducks in one box

---

## 🛠️ Tools Used
- CVAT (annotation)
- COCO / YOLO export formats

---

## 📸 Sample Annotations
Annotated samples demonstrating different scenarios are available in the `/samples` folder.-  

---

## 📂 Dataset Status
This is a prototype dataset. Currently, a curated set of annotated samples is provided in the `/samples` folder to demonstrate annotation quality and consistency.

Full dataset and annotation files will be added in future updates.
---

## 🚀 Future Improvements
- Expand dataset size (100+ images)
- Add more challenging real-world scenarios
- Improve annotation consistency across all samples
