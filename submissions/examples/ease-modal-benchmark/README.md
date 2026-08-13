# Headless Chrome Puppeteer FPS Rendering Benchmark for Modals

This submission provides a Headless Chrome Puppeteer FPS Rendering Benchmark script for Modals. 

Due to repository rules preventing non-maintainers from modifying the `benchmarks/` folder or CI workflows directly, this benchmark script is provided as a submission. Maintainers can integrate this script directly into the CI pipeline.

## Features
- **Benchmark Script (`modal-fps-benchmark.mjs`)**: Uses Puppeteer to simulate fast touch swiping on a scroll-snap container and retrieves frame rate analytics.
- **Budget Thresholds**: Defined strict performance budget limits within the test to prevent regressions.

## Files included:
- `modal-fps-benchmark.mjs`: The Node.js benchmark script.
- `demo.html` & `style.css`: The HTML fixture used for testing modal rendering performance.

## Usage
To test the benchmark script locally:
```bash
npm install --no-save puppeteer
node submissions/examples/ease-modal-benchmark/modal-fps-benchmark.mjs
```
