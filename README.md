# **OneCompiler**
💠  A Linux script designed to make cross-platform compiling easier
<br>Why ? Because I find it is better to have one universal command for all platforms and file extensions

<br>
Don't hesitate to reach me, or donate using the links on my profile, all donations are appreciated 😉

## 🖥️ Platforms
This script is Linux-only

## 🛠️ Installation
Manual installation:
```bash
git clone https://github.com/M4elstr0m/OneCompiler.git
cd OneCompiler
chmod +x onecompier
```
Debian (.deb) installation:
```bash
cd packages
sudo dpkg -i onecompiler.deb
```
**Please notice that the package will be accessible anywhere on your system with this install, so you don't need to put the ```./``` anymore before ```onecompiler```**
## 📚 Usage
Basic usage:
```bash
./onecompiler [Options] file
```

Create a Windows-compatible file from a .cpp (C++) file:
```bash
./onecompiler --windows mycode.cpp
```

Create a Linux-compatible file from a .go (Go) file:
```bash
./onecompiler --linux mycode.go
```
## 🧩 Modules
<div>
<table>
  <tr>
    <th>Language Name</th>
    <th>File Extension</th>
    <th>Supported</th>
    <th>Version</th>
  </tr>
  <tr>
    <td>C++</td>
    <td>.cpp</td>
    <td>✅</td>
    <td>v1.0</td>
  </tr>
  <tr>
    <td>Go</td>
    <td>.go</td>
    <td>✅</td>
    <td>v1.0</td>
  </tr>
  <tr>
    <td>C#</td>
    <td>.cs</td>
    <td>🚧</td>
    <td>?</td>
  </tr>
</table>
</div>

## 🗒️ Credits
Softwares/Codes used in this repository : g++, x86_64-w64-mingw32-g++, go
