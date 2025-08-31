# DarkNpp

[![Trạng thái build](https://img.shields.io/github/actions/workflow/status/ozone10/Npp-DarkNpp/build.yml?branch=master&logo=Github)](https://github.com/ozone10/Npp-DarkNpp)  
[![Phiên bản mới nhất](https://img.shields.io/github/v/release/ozone10/Npp-DarkNpp?include_prereleases)](https://github.com/ozone10/Npp-DarkNpp/releases/latest)  
[![Tổng lượt tải xuống](https://img.shields.io/github/downloads/ozone10/Npp-DarkNpp/total.svg)](https://github.com/ozone10/Npp-DarkNpp/releases)  
[![Giấy phép](https://img.shields.io/github/license/ozone10/Npp-DarkNpp?color=9cf)](https://www.gnu.org/licenses/gpl-3.0.en.html)  

## 📢 LƯU Ý: Notepad++ 8.0 đã có hỗ trợ chế độ nền tối  

Hiện tại plugin chủ yếu được dùng để **thử nghiệm hiệu ứng mica**.  

---

Plugin [Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus) cho phép sử dụng **chế độ nền tối một phần**.  
Hỗ trợ: **thanh tiêu đề chính, một số tooltip, thanh cuộn và menu chuột phải**.  

Trên **Windows 11** có thể bật hiệu ứng **mica** trên cửa sổ chính.  

👉 Chủ yếu dùng cho mục đích **thử nghiệm**.  

---

<p align="center">
  <img src="https://i.imgur.com/sJm0Kke.png">
  <img src="https://i.imgur.com/UDTmTzj.png">
  <img src="https://i.imgur.com/fxBvFdi.png">
</p>

---

## ⚙️ Tuỳ chọn

- **useDark** – Chọn chế độ hiển thị  
  - **0** → chế độ sáng  
  - **1** → chế độ tối (mặc định)  

- **micaType** – Áp dụng hiệu ứng mica hoặc khác cho cửa sổ chính  
  👉 Khuyến nghị dùng `useDark=1` khi bật mica  

  - **0** → hệ thống tự chọn (mặc định, chỉ trên thanh tiêu đề)  
  - **1** → không dùng mica  
  - **2** → mica  
  - **3** → mica acrylic  
  - **4** → mica thay thế (dùng trong ứng dụng tab)  
  - **5** → hiệu ứng acrylic (ẩn, chạy trên Windows 10 nhưng có thể giật khi kéo/thay đổi kích thước)  

> [!QUAN TRỌNG]  
> - `micaType` khác `0` **không nên dùng** cùng với HDR và ACM (Auto Color Management).  
> - Có thể gây **lỗi hiển thị** (đặc biệt với HDR/ACM → có thể mất control).  
> - Nếu dùng `micaType=1` → nên tắt:  
>   **Cài đặt → Cá nhân hoá → Màu sắc → "Hiển thị màu nhấn trên thanh tiêu đề và viền cửa sổ"**.  

---

## 📝 Cấu hình mẫu

- **Mặc định:** Chế độ nền tối, không dùng Mica  

```ini
[DarkNpp]
useDark=1
micaType=0
