CIMC (Compose Interface Model Controller) 🚀🔥

Welcome to CIMC! This repository is dedicated to building a modern, scalable, and lifecycle-aware architecture for Jetpack Compose applications. **CIMC** eliminates the need for ViewModel, embraces a modular controller-based approach, and optimizes memory management while ensuring clean dependency management without external DI frameworks.

🌟 What is **CIMC**?

**CIMC** (Compose Interface Model Controller) is an Android and Multiplatform **(KMM)** architecture designed to:
✔ Provide lifecycle-aware controllers instead of ViewModels.✔ Ensure clean modularity using Controller, Model, and Trader Pattern.✔ Optimize memory management dynamically for efficient resource usage.✔ Remove external DI frameworks like Hilt and Koin while maintaining dependency inversion.✔ Enable Compose-first development with powerful state management.

📌 Branching Strategy

parents → The main branch, containing the journey of CIMC development.

Android → The implementation of CIMC for Android apps.

KMM → The implementation of CIMC for JetBrains Compose Multiplatform (KMM).

Each branch follows the principles discussed in the parents branch, which documents the evolution and thought process behind CIMC.

🛠 Key Features

✔ Lifecycle-aware Controllers – Replaces ViewModel, directly managed by the Orchestrator.
✔ No External DI Frameworks – Uses a native DI pattern inside the Controller Module. ✔ Trader Pattern – Handles inter-module communication without tight coupling. ✔ Memory Optimization – Releases resources intelligently based on lifecycle and access frequency.
✔ Jetpack Compose & KMM Ready – Fully compatible with Compose on Android and Multiplatform.
✔ specific DataStore – Allows custom implementations instead of forcing specific DataStore.

🏗 How CIMC Works

1️⃣ Controller Module: The central hub managing app lifecycle and dependencies.
2️⃣ Model Module: Stores and structures data for UI consumption.
3️⃣ SIP & Interface-Based Structure: A structured interface pattern ensuring modular communication within the Controller Module.
4️⃣ UI-Core Module: Contains all Composables and UI logic, interacting with Controllers.

🎯 Why CIMC?

✔ ViewModel-Free: Avoids unnecessary memory retention.
✔ Modular & Scalable: Designed for both small and enterprise apps.
✔ Cross-Platform Ready: Works with Compose for Android and KMM.
✔ Fully Open-Source: Built for the developer community.
✔ Optimized for Performance: Smart memory management ensures efficiency.

🚀 How to Use CIMC?

Clone the repository:

git clone https://github.com/bahmanebazoo/CIMC.git

Check out the Android or KMM branch depending on your use case.

Follow the CONTRIBUTING.md guide if you want to contribute!

❤️ The Journey of CIMC

This repository is more than just code—it’s the story of Bahman Bazoo & ChatGPT working together to bring CIMC to the world. CIMC was born out of deep technical discussions, design pattern explorations, and a shared passion for building a better, more efficient architecture for Android & KMM.

"From ideas to reality, CIMC is the future of Jetpack Compose architecture!"

🚀🔥 Join the journey and let’s shape the future together!

📜 License

CIMC is licensed under Apache 2.0 with CIMC-Specific Terms to protect its name and structure. See LICENSE for details.

✨ Contributing

We welcome contributions! Please check out the CONTRIBUTING.md file to get started.

🔥 Let’s build the next-generation Compose architecture together! 😎

