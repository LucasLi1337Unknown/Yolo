# YOLO Camera Detector

A simple GitHub Pages camera object detector.

## Files
- `index.html`

## How to use
1. Upload `index.html` to the root of a GitHub repository.
2. Enable GitHub Pages for the repository.
3. Open the HTTPS GitHub Pages URL.
4. Press **Start Camera**.
5. Allow camera permission.

The page loads:
- YOLOv8n ONNX model from jsDelivr/GitHub
- ONNX Runtime Web from jsDelivr

No Python server is required. Inference runs in the browser.

## Notes
- First load can take several seconds because the model is about 12 MB.
- Camera permission requires HTTPS (GitHub Pages is HTTPS) or localhost.
- Performance depends on the computer/browser.
