# 🌱 Garter: Python for the Browser

**Garter** is a lightweight, sandboxed dialect of Python designed for client-side execution in the browser.  
It runs inside the [Serpentes VM](https://github.com/serp-hq/serp-serpentes), enabling end-to-end Python — from server to client.

---

## ✨ Features
- **Strict Subset of Python 3.13** – familiar syntax, safe sandbox.  
- **Browser-Native Modules**:
  - `dom` – work with the Document Object Model  
  - `events` – async-first event handling  
  - `storage` – client-side persistence  
  - `server` – built-in RPC to Python backends  
- **Async by Default** – first-class support for modern async code.  
- **Sandboxed Profile** – enforced at the VM level via Serpentes.

---

## 📖 Motivation
The web has long been split:  
- Python dominates servers.  
- JavaScript rules browsers.  

**Garter** eliminates this “two-language problem” by letting developers use Python everywhere.  
Write once, run across environments.

---

## 📚 Resources
- [Draft PEP: Garter](https://github.com/serp-hq/serp-garter/blob/main/PEP_XXXX_Garter.pdf)  
- [Org Home (Serp-HQ)](https://github.com/serp-hq)  

---

## 🤝 Contributing
We welcome contributions in:  
- Spec design for browser modules  
- Security sandboxing  
- Browser ↔ server demo apps  

👉 Start a thread in [Discussions](https://github.com/serp-hq/serp-garter/discussions).  

---

## 📜 License
MIT License. See [LICENSE](LICENSE) for details.
