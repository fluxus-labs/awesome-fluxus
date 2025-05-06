# 🌊 awesome-fluxus

A curated list of **Fluxus** plugins, tools, sources, sinks, and ecosystem projects.

Fluxus is moving toward a modular, plugin-friendly architecture — with `fluxus-core` providing only the essential traits (`Source`, `Sink`, etc.) and leaving most concrete implementations to external crates.

This repo gathers official and community-maintained implementations to help you navigate the growing Fluxus ecosystem.

---

## 📦 Core Crates

* [`fluxus-core`](https://github.com/lispking/fluxus/tree/develop/crates/fluxus-core) — Core abstractions: `Source`, `Sink`, and essential types.
* [`fluxus-sources`](https://github.com/lispking/fluxus/tree/develop/crates/fluxus-sources) — Officially maintained common data sources.
* [`fluxus-sinks`](https://github.com/lispking/fluxus/tree/develop/crates/fluxus-sinks) — Officially maintained common sinks.

---

## 🌍 Community Sources & Sinks

We encourage specialized and niche implementations to live in independent repositories.

To help discovery:

* Use the GitHub topic tag **#fluxus** in your repository.
* Add your project as a comment in the [📌 Sources & Sinks tracking issue](https://github.com/lispking/fluxus/discussions/78).

We will regularly update this list!

---

## 🔍 Discover More

* [Search GitHub for #fluxus projects](https://github.com/topics/fluxus)
* Contribute to the [📌 Sources & Sinks tracking issue](https://github.com/lispking/fluxus/discussions/78)

---

## 💡 Why This Structure?

Inspired by the modular designs of systems like **Apache Spark** and the **Linux kernel**, Fluxus:

* Keeps the core minimal and clean
* Relies on Rust’s powerful dependency system for plugin management
* Avoids unnecessary runtime complexity like dynamic registries

---

## 🤝 Contributing

Want to add your Fluxus-compatible project here?

* Submit a PR to this README
* Or comment in the [📌 tracking issue](https://github.com/lispking/fluxus/discussions/78)
