# HSA-BETAROVE
# 🏎️ Haosea RC Project 

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Platform: iNav](https://img.shields.io/badge/Platform-iNav-green.svg)](https://github.com/iNavFlight/inav)
[![RC Link: ExpressLRS](https://img.shields.io/badge/RC%20Link-ExpressLRS-orange.svg)](https://www.expresslrs.org/)
[![ESC Firmware: AM32](https://img.shields.io/badge/ESC%20Firmware-AM32-emerald.svg)](https://github.com/am32-firmware/AM32)

---

### 🇻🇳 TIẾNG VIỆT

## 🌟 Giới thiệu Dự án
Chào mừng anh em đến với **Haosea RC Project** – dự án xe RC mã nguồn mở! 

Dự án này sinh ra với một tinh thần duy nhất: **Chia sẻ và cùng tiến**. Toàn bộ file thiết kế cơ khí 3D (CAD), sơ đồ mạch điện (PCB) và cấu hình phần mềm đều được chia sẻ miễn phí

Nếu bạn đam mê chế tạo, có một chiếc máy in 3D và muốn sở hữu một con xe tốc độ cao (mục tiêu 70km/h) với tư duy "sai đâu sửa đó", đây chính là sân chơi dành cho bạn!

### 🛠️ Thông số Kỹ thuật & Hệ sinh thái
* **Cơ khí chính xác:** Bản vẽ tối ưu cho in 3D (vật liệu khuyên dùng: PETG)
* **Bộ não điều khiển:** Mạch điều khiển tích hợp STM32 chạy **iNav Flight**.
* **Hệ thống sóng:** Tích hợp bộ thu **ExpressLRS (ELRS)** cho độ trễ cực thấp và khoảng cách điều khiển vô cực.
* **Động cơ & ESC:** Sử dụng firmware **AM32** tùy chỉnh giúp motor chạy mượt mà, phản hồi ga tức thì.

---

### 🇬🇧 ENGLISH

## 🌟 Project Overview
Welcome to **Haosea RC Project** – the pioneer open-source RC car project!

This repository is built on the spirit of **pure open-source collaboration**. All 3D mechanical designs (CAD), schematic files (PCB), and software configurations are shared 100% free for the maker community

If you love engineering, own a 3D printer, and want to build a high-performance RC car (targeting 70km/h) with a "fail-fast, fix-faster" mindset, you are in the right place!

### 🛠️ Tech Specs & Ecosystem
* **Precision Mechanics:** Fully optimized 3D-printable chassis and suspension parts (recommended materials: PETG)
* **Flight Controller (FC):** STM32-based custom board powered by the **iNav Flight** ecosystem
* **RC Link:** Integrated **ExpressLRS (ELRS)** for ultra-low latency and long-range reliability
* **ESC Firmware:** Powered by **AM32** custom firmware for smooth throttle response and efficient motor control

---

## 📁 Cấu trúc Thư mục / Repository Structure

* **🇻🇳 Tiếng Việt:**
  * `📁 File 3D` (Mechanics): Chứa file CAD gốc (`.f3d`, `.step`) thiết kế trên Autodesk Fusion.
  * `📁 hardware` (Hardware): Chứa sơ đồ nguyên lý (Schematics) và file Gerber thiết kế mạch PCB.
  * `📁 Firmware` (Firmware): Chứa file `.hex` compiled sẵn, file CLI cấu hình iNav, và sơ đồ chân `.json` cho ELRS.
  * `📁 Documentation` (Documentation): Sách hướng dẫn lắp ráp 3D bóc tách chi tiết (PDF) và video hướng dẫn.

* **🇬🇧 English:**
  * `📁 File 3D` (Mechanics): Contains original CAD source files (`.f3d`, `.step`) designed in Autodesk Fusion.
  * `📁 hardware` (Hardware): Contains circuit schematics and Gerber files for PCB manufacturing.
  * `📁 Firmware` (Firmware): Includes pre-compiled `.hex` files, iNav CLI configurations, and ELRS pinout `.json` files.
  * `📁 Documentation` (Documentation): Step-by-step 3D assembly manuals (PDF) and video guides.

---

## 🤝 Tham gia Đóng góp / Contributing

* **🇻🇳 Tiếng Việt:**
  Mọi đóng góp nâng cấp thiết kế cơ khí, tối ưu mạch PCB hoặc căn chỉnh PID trên iNav đều được chào đón nhiệt tình. Hãy tạo một **Pull Request** hoặc tham gia thảo luận cùng chúng mình qua các kênh bên dưới nhé!

* **🇬🇧 English:**
  Any contributions to improving mechanical designs, optimizing PCB layouts, or fine-tuning iNav PID settings are highly welcome. Please feel free to open a **Pull Request** or join our community discussions!

### 💬 Liên kết Cộng đồng / Community Links

* **👾 Discord Server:** [Join our Discord] https://discord.gg/BWj3YDgcD (Nơi thảo luận kỹ thuật và hỗ trợ / Technical discussions & support)
