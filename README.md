# Motion-Analysis-Python
Pose estimation and movement visualization of Kalaripayattu martial art using MediaPipe and Python

This project analyzes **Kalaripayattu**, the ancient Indian martial art, using **MediaPipe Pose** and **Python**.  
It extracts body landmarks from video, generates **movement trajectories**, and creates professional **visualizations (plots, overlay video, GIFs)**.


---

## 📌 Features
- 🎥 **Pose Landmark Tracking** using MediaPipe
- 📝 Save trajectories to **CSV**
- 📊 **Plan and Elevation view** motion plots
- 🎬 Generate **overlay video** with tracked landmarks
- 🎨 Create **animated GIFs** showing trails of movement
- ⚡ Runs entirely **offline** once dependencies are installed

---

## 📂 Project Workflow
1. **Input Video** → `kalaripayattu.mp4`
2. **Pose Estimation** → Extract Nose, Wrists, and Ankles
3. **Trajectory CSV** → `kalaripayattu_trajectories.csv`
4. **Visualizations**:
   - Overlay video with skeleton (`kalaripayattu_overlay.mp4`)
   - Movement contour plots (`kalaripayattu_contours.png`)
   - Animated GIF with trails (`kalaripayattu_trails.gif`)

