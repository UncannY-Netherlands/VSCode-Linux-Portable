# VSCode Enterprise Portable

**VSCode Enterprise Portable** is a portable build of [Microsoft Visual Studio Code](https://code.visualstudio.com/).
It is designed for enterprise environments and is especially useful on systems such as **RHEL**, **SUSE**, and **Ubuntu Pro**, where system stability and minimal modifications are critical.

With this portable build, **no installation is required**, keeping the system clean. Updates and package management are not necessary, as everything is self-contained in a single directory.

---

## Features

* **Portable:** no installation required, runs directly from the folder.
* **Enterprise-ready:** tested on enterprise-grade Linux distributions.
* **Compatible:** works on RHEL, SUSE, Ubuntu Pro, and most modern Linux systems.
* **Self-contained:** ships with all necessary libraries and shared objects (`.so` files).
* **Stable:** does not modify system settings or package managers.

---

## Download

The version is 1.103.2-1755709794 from Microsoft.

You can download the source code and binaries from the link below or release tab.

The tarball (`.tar.xz`) includes:

* The executable binary (`code`)
* Required libraries and `.so` files
* Helper scripts for startup and configuration

[Download the source code](https://github.com/UncannY-Netherlands/VSCode-Enterprise-Portable/releases/download/1.103.2-1755709794/vscode_1.103.2-1755709794_portable.tar.xz)

---

## Usage

1. Download and extract the archive.
2. Navigate to the extracted folder.
3. Run the `code` executable.

```bash
./code
```

Or simply double-click the **code** binary in your file manager.

---

## Configuration

* All settings, extensions, and user data are stored in the local directory, leaving no traces on the host system.
* The folder can be moved to USB drives, network shares, or shared environments without losing configuration.
* Extensions are fully supported and stored locally in the portable environment.

---

## Use Cases

Portable VSCode is particularly useful in enterprise and restricted environments:

* **Air-gapped servers:** Run VSCode without requiring system-wide installation.
* **Strict IT policies:** Ideal where package installation is limited or restricted.
* **Testing environments:** Keep multiple isolated VSCode versions for testing without interfering with the system.
* **USB portability:** Carry your editor, settings, and extensions on a USB stick.
* **Cross-distro use:** Move the same portable build across different Linux distributions.

---

## Copyright and License

See the [LICENSE](LICENSE) file for details.

This project is **Visual Studio Code** by Microsoft.
The software is licensed under the **MIT License**.

###### &copy; 2025 UncannY Software Netherlands
###### &copy; 2025 Microsoft Corporation