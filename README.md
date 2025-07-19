

# 🐊 croc-lib

> A fork of [`schollz/croc`](https://github.com/schollz/croc) that exposes core functionality as a reusable Go library.

This repository transforms the original `croc` CLI application into a Go library, enabling developers to integrate secure, end-to-end encrypted file and message transfer into their own Go applications.

## 🔧 What is `croc`?

[`croc`](https://github.com/schollz/croc) is a tool that allows any two computers to securely and easily transfer files and folders. It uses relay-assisted, end-to-end encrypted connections based on PAKE (Password-Authenticated Key Exchange) and offers cross-platform support, resumable transfers, and fast performance.

This fork **converts the CLI tool into a Go package** that can be embedded in other applications.

---

## ✨ Features

* ✅ Send and receive files or messages programmatically
* ✅ End-to-end encryption using PAKE (via `pake/v2`)
* ✅ Custom relay support
* ✅ Works across NATs with peer relay
* ✅ Based on the battle-tested `croc` core



## 📄 License

This fork inherits the **MIT License** from the original `croc` project by @schollz.

---

## 🙏 Credits

* [Original croc repo](https://github.com/schollz/croc) by @schollz
* Relay and PAKE implementation inspired by `croc` and its dependencies

