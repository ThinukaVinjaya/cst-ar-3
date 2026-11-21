========================================================================
CST WebAR Challenge 3 - Waving Animated 3D Model
========================================================================

Model Specifications:
- Name: Waving
- Primary Asset: models/waving.glb (3.0 MB high-speed asset, 1 to 143 frames)
- Apple Quick Look USDZ: models/waving.usdz (5.3 MB tabletop-baked asset)
- S3 Asset URL: https://cst-lan.s3.eu-north-1.amazonaws.com/Waving.fbx
- Local FBX Fallback: Waving.fbx
- Tabletop Target Height: 25 cm (0.25 m)
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
