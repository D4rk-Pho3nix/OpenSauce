<div align="center">

![Banner Placeholder](https://rqecqirwmpmowvpezhki.supabase.co/storage/v1/object/generated-banners/final-banner-3d554fc7-eb01-4807-b893-5faba45445e3/finalbanner.png)

![Version](https://img.shields.io/github/v/release/D4rk-Pho3nix/OpenSauce?style=flat-square&label=version&color=blue)
![Last Commit](https://img.shields.io/github/last-commit/D4rk-Pho3nix/OpenSauce?style=flat-square&label=last%20commit&color=purple)
![Followers](https://img.shields.io/github/followers/D4rk-Pho3nix?style=flat-square&logo=github&color=yellow)
![License](https://img.shields.io/github/license/D4rk-Pho3nix/OpenSauce?style=flat-square&color=orange)
![Contact](https://img.shields.io/badge/Contact-manish.srmist23@gmail.com-cyan?style=flat-square)


**made with 🩷 by [D4rk-Pho3nix](https://github.com/D4rk-Pho3nix)**
*(if you like my work, consider ⭐ starring the repo!)*

</div>

---

## 📑 Table of Contents

| Section | Description |
|---------|-------------|
| [💡 Why this exists](#-why-this-exists) | Purpose and background of the project |
| [✨ Features](#-features) | Key capabilities and highlights |
| [🏗️ Architecture](#-architecture) | Codebase structure and organization |
| [🚀 Quick Start](#-quick-start) | Get up and running in minutes |
| [📖 Usage](#-usage) | Detailed usage instructions |
| [🤝 Contributing](#-contributing) | Guidelines for contributors |
| [👤 Maintainers](#-maintainers) | Project maintainers |
| [🤝 Contributors](#-contributors) | Project contributors |
| [💖 Support](#-support) | How to support the project |
| [📄 License](#-license) | Licensing information |

---

## 💡 Why this exists

> Centralized, multi-language repository for high-performance DSA implementations with automated quality gating.

**Background:** Designed to centralize efficient implementations of common algorithms with mandatory complexity analysis and automated quality validation via GitHub Actions. It serves as a learning tool and a platform for Hacktoberfest participation.

---

## ✨ Features

- 🚀 **Multi-Language Support**: Covers 15+ languages including C++, Rust, Go, Haskell, and Swift with idiomatic implementations.
- 🤖 **Automated PR Validation**: Integrated GitHub Actions verify documentation, syntax, complexity analysis, and length requirements before auto-merging valid contributions.
- 📊 **Mandatory Complexity Analysis**: Every implementation is required to include Time and Space complexity in Big O notation within the comments.
- 🎃 **Hacktoberfest Integration**: Automated labeling ('Hacktoberfest', 'good first issue') and PR management tailored for Hacktoberfest contributors.
- 📁 **Categorized Algorithmic Modules**: Organized by algorithmic topics like Graphs, Trees, DP, and Arrays for easy navigation.

---

<div align="center">
  <img src="https://rqecqirwmpmowvpezhki.supabase.co/storage/v1/object//generated-banners/showcase-3d554fc7-eb01-4807-b893-5faba45445e3/showcase1.png" alt="Main Showcase" width="1000">
  <p><i>Main Showcase</i></p>
  <details>
    <summary><b>View Gallery</b></summary>
    <table style="width: 100%; border-spacing: 15px; border-collapse: separate;">
      <tr>
        <td align="center" style="vertical-align: top; width: 50%;">
          <b>2</b><br>
          <img src="https://rqecqirwmpmowvpezhki.supabase.co/storage/v1/object//generated-banners/showcase-3d554fc7-eb01-4807-b893-5faba45445e3/showcase2.png" alt="2" width="100%">
        </td>
        <td align="center" style="vertical-align: top; width: 50%;">
          <b>3</b><br>
          <img src="https://rqecqirwmpmowvpezhki.supabase.co/storage/v1/object//generated-banners/showcase-3d554fc7-eb01-4807-b893-5faba45445e3/showcase3.gif" alt="3" width="100%">
        </td>
      </tr>
    </table>
  </details>
</div>

---

## 🏗️ Architecture

```
OpenSauce/
├── .github/workflows/    # CI/CD Automation
├── C++/                  # C++ Solutions
├── Python/               # Python Solutions
├── Java/                 # Java Solutions
├── PHP/                  # PHP Challenges & Tests
├── Rust/                 # Rust Solutions
└── CONTRIBUTING.md       # Quality Guidelines
```

| Directory | Purpose |
|-----------|---------|
| `.github/workflows` | Contains GitHub Actions for automated testing and labeling. |
| `C++` | Topic-organized C++ implementations including arrays, trees, and graphs. |
| `Java/subarrays` | Comprehensive subarray problem set using Kadane's, Sliding Window, and Prefix Sum. |
| `PHP/test_karunia` | Standalone PHP challenge solutions with local test server support. |

---

## 🚀 Quick Start

> [!IMPORTANT]
> All implementations MUST include Time and Space complexity analysis in Big O notation to pass automated validation.

### Prerequisites

| Requirement | Version | Notes |
|-------------|---------|-------|
| GCC/G++ | 9.0+ | Required for C++17 implementations |
| Python | 3.8+ | For Python algorithm scripts |
| Node.js | 14+ | Required for JavaScript/TypeScript modules |
| Rust/Cargo | Latest | For Rust implementations |

> [!WARNING]
> Ensure your environment has the specific compiler or runtime for the language you intend to contribute to or run.

### Clone & Setup

```bash
git clone https://github.com/D4rk-Pho3nix/OpenSauce.git
cd OpenSauce
```

### Build

```bash
# Example: Compiling a C++ solution
g++ -std=c++17 C++/arrays/169-Majority_Element.cpp -o solution
```

### Run

```bash
# Example: Running a Python solution
python3 Python/arrays/1248-count-number-of-nice-subarrays.py

# Example: Starting PHP local test server
php -S localhost:8000
```

> [!NOTE]
> For PHP modules, you can open http://localhost:8000/tests/run_all_tests.php in your browser after starting the server.

---

## 📖 Usage

Users navigate to the directory of their chosen language, locate the algorithm by topic (e.g., `/sorting`), and execute the file using the appropriate language runtime or compiler. 

### Examples:

**Running a C++ algorithm with complexity analysis**
```bash
g++ "C++/arrays/169-Majority Element.cpp" -o majority && ./majority
```

**Executing the PHP test suite**
```bash
php -S localhost:8000
# Navigate to the test runner URL in your browser
```

---

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Quick contribution flow:**

```bash
# Fork the repo
# Create your feature branch
git checkout -b feature/add-new-algorithm

# Make your changes (Ensure Big O notation is included)
# Commit with conventional commits
git commit -m "feat: add merge sort implementation in Go"

# Push and create PR
git push origin feature/add-new-algorithm
```

> [!NOTE]
> All PRs must pass automated CI checks (syntax, complexity analysis, and documentation) before merging.

---

## 👤 Maintainers

<table align="left">
  <tr>
    <td align="left">
      <a href="https://github.com/D4rk-Pho3nix">
        <img src="https://github.com/D4rk-Pho3nix.png?size=100" width="100px;" alt="D4rk-Pho3nix"/>
      </a>
    </td>
  </tr>
</table>

---

## 🤝 Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

| Name | Contributions |
|------|---------------|
| [D4rk-Pho3nix](https://github.com/D4rk-Pho3nix) | 💻 📖 💡 |

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

---

## 💖 Support

If this project helped you, consider buying me a coffee, any donation is appreciated and goes towards my caffeine addiction :p

<a href="https://buymeacoffee.com/hf2p">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExem14OW1tanN3eHlyYmR4NW1sYmJkOTZmbmJxejdjZXB6MXY5cW12MSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/TDQOtnWgsBx99cNoyH/giphy.gif" width="80">
</a>

---

## 📄 License

This project is licensed under the [MIT](LICENSE).

```
Copyright (c) 2025 OpenSauce Contributors. Licensed under the MIT License.
```

---

[![Star History Chart](https://api.star-history.com/svg?repos=D4rk-Pho3nix/OpenSauce&type=Date)](https://star-history.com/#D4rk-Pho3nix/OpenSauce&Date)

---

<div align="center">

**[⬆ Back to Top](#-opensauce)**

</div>

<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║  README TEMPLATE v2.0 - Closing Subagent                                      ║
║  Auto-generated by closing-subagent                                           ║
║                                                                               ║
║  Variables are wrapped in <DOUBLE_BRACES>                                   ║
║  Conditionals use <#IF_CONDITION>...</IF_CONDITION>                       ║
║  See bottom of file for variable reference                                    ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->
