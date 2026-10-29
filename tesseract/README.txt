Self-hosted Tesseract.js 5.1.1 files for the screenshot import in index.html (Apache-2.0, see LICENSE-tesseract.js.txt).
Upload this whole folder next to index.html. Files:
  tesseract.min.js, worker.min.js           from the npm package tesseract.js@5.1.1 (dist/)
  tesseract-core-lstm.wasm.js               from tesseract.js-core@5.1.1 (older browsers)
  tesseract-core-simd-lstm.wasm.js          from tesseract.js-core@5.1.1 (modern browsers)
  eng.traineddata.gz                        from @tesseract.js-data/eng (4.0.0_best_int)
To upgrade, replace all of them with the same version of each package.
