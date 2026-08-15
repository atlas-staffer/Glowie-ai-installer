# Glowie AI Solver

AI-powered captcha solving module.

## Download

**Windows:** [Download Latest](https://github.com/atlas-staffer/Glowie-ai-installer/releases/latest/download/glowie-ai-solver.zip)

**macOS (Apple Silicon):** [Download Latest](https://github.com/atlas-staffer/Glowie-ai-installer/releases/latest/download/glowie-ai-solver-macos-arm64.zip)

_Current release: v0.2.64_

## Usage

### Windows

1. Download `glowie-ai-solver.zip`
2. Right-click the zip and **Extract All** (keep the whole folder together)
3. Open the extracted `glowie-ai-solver` folder and run `glowie-ai-solver.exe`
   (the `_internal` folder must stay next to it)
4. Paste your OpenRouter API key in the dashboard
5. Set your concurrent solve count and you're ready

### macOS (Apple Silicon)

1. Download `glowie-ai-solver-macos-arm64.zip` and unzip — keep `_internal/` beside the binary
2. **Double-click `Open Glowie.command`** (in the unzipped folder)
   - If macOS says it cannot verify the file: **Right-click → Open → Open** (once)
   - That clears Apple's download quarantine and launches the solver
3. If you still see **“Python Not Opened”**:
   **System Settings → Privacy & Security** → scroll down → **Open Anyway**,
   then run `Open Glowie.command` again
4. Paste your OpenRouter API key in the dashboard

Terminal alternative (same fix):
```bash
xattr -cr ~/Downloads/glowie-ai-solver
cd ~/Downloads/glowie-ai-solver && ./glowie-ai-solver
```

The app keeps content (prompts / pricing / models) up to date automatically.
Binary updates on macOS require re-downloading the zip and replacing the folder.
