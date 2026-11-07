Tablet-only deployment and operation guide

- How to set up: Use GitHub in the browser to create a repository and push the skeleton/template files.
- CI/CD: Connect to GitHub Actions to build WebGL; artifact gets produced at Build/WebGL.
- Render: Connect your repo to Render; choose Docker deployment and point to Dockerfile.
- Tablet UX: Use on-screen joystick placeholders; actual UI to be implemented in Unity for WebGL build.
- Verification: After deployment, load the URL and verify WebGL assets load; ensure the first-run cutscene placeholder appears.
