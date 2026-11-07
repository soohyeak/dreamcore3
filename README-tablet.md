Dreamcore Horror Skeleton for Tablet (Render Deployment)

This repo is configured to run on a tablet via cloud CI and Render deployment. The actual Unity WebGL build needs to be produced by CI and deployed to Render.

Steps:
1) Use your tablet to create a GitHub repo and push this skeleton (or fork).
2) Set up GitHub Actions to build WebGL on push to main.
3) Connect the repo to Render and deploy as a Docker-based web service.
4) Visit the Render URL to verify the WebGL game loads. Ensure Build/WebGL assets are present in the Docker image.
5) When you have the real Unity project, replace the placeholder assets/scenes and push again.
