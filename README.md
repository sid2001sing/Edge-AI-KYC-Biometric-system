# Edge-AI-KYC-Biometric-system
A serverless, privacy-first KYC module built on AngularJS. It utilizes Edge AI (Tesseract.js &amp; Face-API.js) to perform instant Aadhaar OCR extraction, Verhoeff validation, and biometric face matching entirely within the browser, eliminating backend costs and data risks.

A privacy-first, serverless Identity Verification system. It performs OCR extraction, data validation, and biometric face matching entirely within the browser using Client-Side AI.

## Features
* **Edge AI:** No data is sent to the cloud. All processing happens on the user's device.
* **Aadhaar OCR:** Uses Tesseract.js (LSTM) with custom High-Contrast Binarization.
* **Pattern Logic:** Implements regex-based spatial analysis to extract the 12-digit UID.
* **Biometric Liveness:** Uses `face-api.js` (TensorFlow) to match the ID card photo against a live selfie.

## Tech Stack
*  AngularJS 1.8
* HTML5 Canvas
*  Tesseract.js
* Face-API.js
* CSS3 (Grid/Flexbox)
