# PrintPrep

Built with **Modern Angular** (Standalone Components, Signals), **NgRx**, **Angular Material** and **SCSS**.

---

### Real-World Purpose & Problem Solved

Built specifically to streamline operational workflows and eliminate bottlenecks in our family print shop. During peak hours, long customer queues are delayed by manual file picking, dark-mode mobile screenshots wasting expensive toner, and complex PDF handling. PrintPrep accelerates the prepress workflow by providing instant screenshot cropping, ink-saving color inversion when needed, PDF merging, and unified file queuing—all directly in the browser.

---

## Features

* **Unified Multi-File Print Queue:** Automatically parses attached images and PDFs from Gmail or local storage into a single sequential A4 preview carousel.
* **Ink-Saver Color Inversion:** Offloads pixel manipulation to an Angular **Web Worker** to instantly convert dark UI backgrounds to white without blocking the UI thread.
* **Canvas Screenshot Cropping:** Integrated tool to crop out unwanted parts of an image.
* **OS Share Target Integration:** Registered as a native mobile/desktop Share Target (`share_target`) to ingest shared files directly into IndexedDB.
* **Image-to-PDF & PDF Merging:** Tools for reordering images and merging distinct PDF files using drag-and-drop mechanics.

---

## Tech Stack & Architecture

* **Frontend:** Angular 22
* **State Management:** NgRx (Store / Component Store)
* **UI & Styling:** Angular Material, SCSS
