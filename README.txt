========================================================================
CST WebAR Challenge 3 - Waving Animated 3D Model
========================================================================

Model Specifications:
- Name: Waving
- Primary S3 Asset: https://cst-lan.s3.eu-north-1.amazonaws.com/Waving.fbx
- Local Fallback: Waving.fbx (110.0 MB)
- Native Scaled GLB: models/waving.glb (tabletop 25 cm, 1 to 143 frames)
- Native Scaled USDZ: models/waving.usdz (tabletop 25 cm with Apple Quick Look anchoring)
- Theme: Neon Purple / Violet (#a855f7) Cyber-HUD Glassmorphic UI

AR Viewing Modes Supported:
1. Native WebXR 6-DoF Session:
   - Full ARCore table anchoring, real surface hit-testing, and dynamic placement.
2. Universal Live Camera AR Pass-Through (getUserMedia):
   - Works over LAN HTTP, desktop browsers, and non-HTTPS mobile devices.
   - Hides virtual grid to place the character directly on the real table.
3. Apple AR Quick Look:
   - iOS 12+ Safari native AR via models/waving.usdz#allowsContentScaling=1
4. Android Google Scene Viewer:
   - Android Intent fallback via models/waving.glb
