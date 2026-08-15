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
2. **Only** double-click **`Open Glowie.command`**
   - Do **not** open `Python` or anything inside `_internal` first
     (that shows “Python is damaged” while Chrome quarantine is active)
   - If macOS blocks the `.command`: **Right-click → Open → Open** (once)
3. If you already saw “damaged”: click **Cancel**, then use `Open Glowie.command`
4. Paste your OpenRouter API key in the dashboard

Terminal alternative:
```bash
xattr -cr ~/Downloads/glowie-ai-solver
open ~/Downloads/glowie-ai-solver/Open\ Glowie.command
```

The app keeps content (prompts / pricing / models) up to date automatically.
Binary updates on macOS require re-downloading the zip and replacing the folder.
