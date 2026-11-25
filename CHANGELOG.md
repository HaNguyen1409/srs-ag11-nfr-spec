# Changelog

Mọi thay đổi đáng kể của skill ghi ở đây. Định dạng theo [Keep a Changelog](https://keepachangelog.com/vi/1.1.0/), phiên bản theo [SemVer](https://semver.org/lang/vi/).

## [Unreleased]

## [1.0.0] - 2026-11-25

### Added

- Tách thành repo độc lập (microservice skill): `skill.json` khai báo hợp đồng giao tiếp và skill phụ thuộc, CI kiểm tính nhất quán, Release tự đóng zip.
- Ẩn danh hoá: bỏ tham chiếu tới dự án áp dụng cụ thể; skill dùng được cho mọi dự án.

### Lịch sử trước khi tách repo

- Cập nhật 20/11/2026 (phương án C): B19 bỏ cột REQ, Áp dụng (NFR), REQ, Vấn đề mở (CON) và độ phủ REQ loại NFR, CON (RTM D11_NFR, 01_TongHop).
- Phiên bản: 1.0 · Đầu vào: REQ loại NFR/CON (Code Node B5, baseline sau vòng demo) + bối cảnh dự án (Bước 1) · Đầu vào tùy chọn: `cross_cutting` của AG-06 (Bước 9) · Đầu ra bàn giao cho Code Node B18 (lắp ráp SRS), AG-12 (Bước 20 · Rà soát ngữ nghĩa), Tech Lead (Bước 21).
