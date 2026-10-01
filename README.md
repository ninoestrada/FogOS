<h3 align="center" style="font-size: 2.1em; font-weight: bolder;">FogOS</h3>

  <p align="center">
    An educational operating system built on xv6, featuring <strong>Tosh</strong>, a custom Unix-like command-line shell implemented in C.
    <br />
    <a href="https://github.com/ninoestrada/FogOS/tree/main/docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ninoestrada/FogOS/issues/new?labels=bug&template=bug-report.md">Report Bug</a>
    ·
    <a href="https://github.com/ninoestrada/FogOS/issues/new?labels=enhancement&template=feature-request.md">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## 📖 About the Project
![FogOS](docs/fogos.gif)

FogOS is an educational operating-system project built on xv6, MIT's teaching operating system. The project explores operating-system concepts and Unix-like systems programming in C.

## 🐚 **Tosh — The Operating Shell**

Tosh is a custom Unix-like command-line shell implemented in C. It supports command execution, built-in commands, pipes and I/O redirection, background job management, command history, scripting with shebang support, dynamic prompts, and custom path execution.

[**Explore the Tosh documentation »**](docs/TOSH.md)

### **🛠️ Tech Stack**
[![C][C.com]][C-url]
<br />
[![Unix-like][Unix-like.com]][Unix-like-url]
<br />
[![Xv6][Xv6.com]][Xv6-url]
<br />
[![QEMU][QEMU.com]][QEMU-url]
<br />

<!-- GETTING STARTED -->
## 📦 Getting Started

### **💾 Installation**
1. **Install QEMU**
   <br />
   QEMU is required to emulate and test FogOS on your local machine. https://www.qemu.org/download/
2. **Clone the repo**
    ```sh
    git clone https://github.com/ninoestrada/FogOS.git
    ```

### **▶️ Running the Program**
1. **Build FogOS**
   ```sh
   make
   ```
2. **Run FogOS with QEMU**
   ```sh
   make qemu
   ```
3. **Run Tosh**
   ```sh
   tosh
   ```

<!-- LICENSE -->
## 📜 License
Distributed under the xv6 License. See [`xv6-LICENSE`](xv6-LICENSE) for more information.

<!-- RESOURCES -->
## 📚 Resources
[Man](https://www.man7.org/linux/man-pages/index.html), 
[QEMU](https://www.qemu.org/docs/master/),
[Stack Overflow](https://stackoverflow.com/),
[W3Schools](https://www.w3schools.com/),
[Geeks for Geeks](https://www.geeksforgeeks.org/)

<!------- MARKDOWN LINKS & IMAGES ------->
[C.com]: https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white
[C-url]: https://www.iso.org/standard/74528.html
[Unix-like.com]: https://img.shields.io/badge/Unix-like-4285F4?style=for-the-badge&logo=unix-like
[Unix-like-url]: #
[Xv6.com]: https://img.shields.io/badge/Xv6-100000?style=for-the-badge&logo=xv6
[Xv6-url]: https://pdos.csail.mit.edu/6.828/2012/xv6.html
[QEMU.com]: https://img.shields.io/badge/QEMU-EE0000?style=for-the-badge&logo=qemu
[QEMU-url]: https://www.qemu.org/
