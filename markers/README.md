# Live circuit screen scan

The game no longer uses an AR.js `.patt` marker. It opens the device camera and uses OpenCV.js to detect a large rectangular circuit image displayed on a second computer screen in real time.

Recommended scan setup:

- Display the complete circuit image at high brightness.
- Keep the image flat and avoid screen glare.
- Keep the phone camera nearly parallel to the screen.
- Use an image with clear, non-repeating circuit details.
- Serve the game through HTTPS or localhost so the browser can access the camera.
- Press `เปิดกล้องและสแกน`, then point the camera at the circuit image.
