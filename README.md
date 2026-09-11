# VNN Pay

Marketing website for Vietnam-based businesses establishing a digital presence in the United States.

- Live site: https://vnn-pay.pauucerino.workers.dev
- Source: download and extract `vnn-pay-source.zip`.
- Setup and limitations: see `EXPORT-GUIDE.md`.

## Cloudflare Builds

The `main` branch is connected to the dedicated `vnn-pay` Worker. Builds extract the archive, install locked dependencies, build the application and deploy it. Update the source ZIP to change the website; edits to files outside the ZIP do not change application content in this archive-based workflow.

The initial automated build is being verified. The custom domain is not connected yet.
