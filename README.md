# Hi, I'm Ritesh 👋

Full-Stack & Systems Engineer focused on verifiable, client-side first architectures, high-performance tooling, and systems programming. I build applications that compute locally, respect user privacy, and ship with comprehensive automated test suites.

---

## 🚀 Featured Engineering Projects

| Project | Tech Stack | Highlights & Architecture | Live / Source |
| :--- | :--- | :--- | :--- |
| **[PixelForge](https://github.com/Prompt-0/PixelForge)** | React 19, TypeScript, Vite, WASM, Vitest, Playwright | **Privacy-First In-Browser Image Studio & Forensics Suite**<br>• 100% client-side: zero server image uploads.<br>• Local AI background removal (`@xenova/transformers` RMBG-1.4 model) and OCR (`Tesseract.js`).<br>• Forensic tools: LSB steganography, Error Level Analysis (ELA), and EXIF scrubbing.<br>• Automated verification: 89 unit tests (Vitest) + Playwright E2E coverage. | [Live Demo](https://prompt-0.github.io/PixelForge/) • [Repository](https://github.com/Prompt-0/PixelForge) |
| **[AetherChess](https://github.com/Prompt-0/chess-engine)** | Rust, C++, WebSockets, React, TypeScript | **High-Performance Bitboard Chess Engine & GUI**<br>• Bitboard-accelerated move generation and evaluation with alpha-beta pruning.<br>• Universal Chess Interface (UCI) protocol bridge communicating over low-latency WebSockets.<br>• Interactive React interface with live analysis boards and move history trees. | [Repository](https://github.com/Prompt-0/chess-engine) |
| **[Sudoku Zenith](https://github.com/Prompt-0/kudosu)** | TypeScript, React, Algorithms | **Grandmaster Puzzle Engineering Studio**<br>• Exact cover solver powered by Donald Knuth's Dancing Links (DLX) Algorithm X.<br>• Step-by-step logical deduction hint engine (Hidden Pairs, X-Wing, Swordfish).<br>• Fully responsive canvas board with customizable difficulty generator. | [Repository](https://github.com/Prompt-0/kudosu) |
| **[Clerestory](https://github.com/Prompt-0/clerestory)** | Rust, Linux KVM/QEMU, Hypervisor | **Hardware-Adaptive Windows 11 KVM Provisioning Engine**<br>• Automated host topology detection (NUMA nodes, core pin assignments, hugepages).<br>• Generates optimal QEMU/KVM XML definitions for near-bare-metal GPU passthrough.<br>• Strict safety gates and validation against misconfigured IOMMU groupings. | [Repository](https://github.com/Prompt-0/clerestory) |
| **[Fold-It](https://github.com/Prompt-0/fold_it)** | Rust, WebAssembly, Next.js, TypeScript | **AST-Driven Universal PDF Compression Engine**<br>• Client-side PDF stream parsing and object graph structural deduplication.<br>• WebAssembly-compiled Rust core processing megabyte-scale documents in sub-second timeframes.<br>• Zero external service dependency; preserves fonts, vectors, and metadata integrity. | [Repository](https://github.com/Prompt-0/fold_it) |
| **[Cargo-Light](https://github.com/Prompt-0/cargo-light)** | Rust, Ratatui, TUI | **Rust Binary Bloat & Macro Expansion Analyzer**<br>• Interactive terminal treemaps inspecting transitive dependency disk weight and compile times.<br>• Macro weight profiling isolating procedural macro expansion costs.<br>• Actionable prune suggestions detecting duplicate transitive crate versions. | [Repository](https://github.com/Prompt-0/cargo-light) |

---

## 🛠️ Technical Stack & Core Competencies

- **Languages:** Rust, TypeScript, JavaScript (ESNext), Python, C, C++, SQL
- **Frontend & Web:** React 19, Next.js, Vite, Tailwind CSS, Web Workers, HTML5 Canvas, WebGL
- **Systems & Infrastructure:** Linux (Fedora/Ubuntu), KVM/QEMU, Git, Docker, Meson, Bash
- **Verification & Testing:** Vitest, Playwright, Jest, Testing Library, Cargo Test, Cargo Clippy, GitHub Actions CI/CD
- **Data & Algorithms:** Graph algorithms, Dancing Links (DLX), Bitboards, AST parsing, Scikit-Learn

---

## 📐 Engineering Principles

1. **Local-First & Privacy by Default**: Heavy computation belongs on the client whenever possible. User data never touches a remote server unless explicitly requested.
2. **Verification Before Shipping**: Features are verified with unit tests and automated end-to-end regression suites. No code ships with failing assertions or unhandled linter warnings.
3. **Deep Modules with Narrow Interfaces**: Interfaces are designed to hide implementation complexity and state management behind clear, intuitive APIs.

---

## 📬 Contact & Links

- **GitHub:** [@Prompt-0](https://github.com/Prompt-0)
- **Workspaces:** [Coding Portfolio Catalog](https://github.com/Prompt-0/Prompt-0)
