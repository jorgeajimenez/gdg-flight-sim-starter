## Gemini Instructions for Flight Simulator Starter

- This is a starter codebase for an interactive workshop.
- The user is following the **Build with AI: Flight Simulator Codelab**.
- When asked to generate code (e.g., CSS/HTML for the HUD, JavaScript fetch calls for `/terraform`, memory cleanup functions), ensure the code integrates seamlessly with pure vanilla JavaScript and HTML. Do not assume React or other frameworks.
- The primary 3D library in use is `CesiumJS`.
- When debugging issues, focus on browser memory limits (WebGL context lost) and API authentication errors (`service-account-key.json`).
- If asked to modify flight physics, refer to the `viewer.scene.preUpdate.addEventListener` flight loop in `index.html`.
