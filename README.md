# Marker Link – bản cài

Panel After Effects: tạo marker trong comp con (vd: Sfx), rồi ở comp ngoài chọn layer precomp,
đặt kim → bấm tên marker là đoạn đó chạy đúng tại kim (Time Remap). Gọi bao nhiêu lần cũng được.

Repo này chỉ chứa gói cài ở mục **Releases**.

## Cài trên Windows

1. Vào **Releases** → bản mới nhất → tải `Cai-dat-Marker-Link.bat`.
2. Thoát After Effects, nhấp đúp file `.bat` (Windows hỏi SmartScreen thì bấm *More info › Run anyway*).
3. Mở lại After Effects → **Window › Extensions › Marker Link**.

Cần có Creative Cloud desktop (file `.bat` dùng trình cài plugin của Adobe).

**Không có Creative Cloud / cài lỗi?** Cài tay:
1. Tải `MarkerLink-win.zxp`, đổi đuôi thành `.zip` rồi giải nén.
2. Chép thư mục vừa giải nén vào `%APPDATA%\Adobe\CEP\extensions\` và đặt tên `com.sun.markerlink`.
3. Mở lại After Effects.

## Cài trên macOS

Tải `Cai-dat-Marker-Link.command` → chuột phải › **Open** (lần đầu) → mở lại After Effects.

## Dùng

- **Trong comp con:** gõ tên → **+ CTI** để thêm marker tại kim (hoặc chọn layer → *Tạo từ layer đang chọn*).
- **Ở comp ngoài:** chọn layer precomp → đặt kim → bấm tên marker. Cmd/Ctrl+Z để hoàn tác.

Yêu cầu: After Effects 2022 trở lên.
