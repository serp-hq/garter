# 🌱 Garter: Python for the Browser

**Garter** is a lightweight, sandboxed dialect of Python designed for client-side execution in the browser.  
It runs inside the [Serpentes VM](https://github.com/serp-hq/serpentes), which is compiled to WebAssembly for secure, portable execution.

---

## ✨ Features
- **Strict Subset of Python 3.13** – familiar syntax, safe sandbox.
- **Browser-Native Modules**:
  - `dom` – work with the Document Object Model
  - `events` – async-first event handling
  - `storage` – client-side persistence
  - `server` – built-in RPC to Python backends
- **Async by Default** – designed around async-first bytecode from Serpentes.
- **Sandbox Profile** – enforced by Serpentes VM in WASM.

---

## 📖 Motivation
Web development today requires two languages: Python on the server, JavaScript in the browser.  
Garter eliminates this “two-language problem” by enabling Python directly in the browser, sandboxed and async-first.

Paired with **Serpentes VM**, Garter:
- Shares a unified bytecode with server-side Python
- Calls securely into backend APIs using sRPC
- Runs natively in the browser via WASM

---

## 📚 Resources
- [Org Home (Serp-HQ)](https://github.com/serp-hq)

---

## 🤝 Contributing
We welcome contributions in:
- Designing browser modules
- Sandboxing and security
- Demo apps using client ↔ server sRPC
- Documentation and examples

👉 Start a thread in [Discussions](https://github.com/serp-hq/garter/discussions).

---

## 📜 License
MIT License. See [LICENSE](LICENSE) for details.