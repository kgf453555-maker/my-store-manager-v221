# My Store Manager Android V2.0

This copy includes a GitHub Actions workflow for building a debug APK without Android Studio on your PC.

### Workflow
`.github/workflows/build-apk.yml`

It runs on pushes to `main`/`master` and can also be started manually from GitHub Actions.

### Output
The workflow uploads the generated debug APK as the artifact:

`My-Store-Manager-V2.0-debug-APK`

See `GITHUB_BUILD_GUIDE.txt` for step-by-step instructions.
