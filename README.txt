# Face Detection with Viola-Jones (Webcam + Colab)

Real-time face, eye, and smile detection using OpenCV Haar Cascades.  
Saves each detected face as a 50×50 pixel image and records bounding boxes in `detections.txt`.

## Requirements
- Python 3.8+
- `opencv-python`
- OpenCV Haar cascade XML files (auto-downloaded in Colab)

## How to Run
1. Open in Google Colab
2. Run the notebook
3. Allow camera access
4. Click "Ambil Gambar & Deteksi"
5. Outputs:
   - `face_000.jpg`, `face_001.jpg`, ... (50×50)
   - `detections.txt` (format: `face x y w h`)