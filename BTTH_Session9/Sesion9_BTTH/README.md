# SmartCampus 🎓

**SmartCampus** là ứng dụng di động giúp sinh viên PTIT tra cứu *lịch học*, phòng học trống và nhận thông báo mới nhất từ nhà trường.

## Tính năng

- Tra cứu lịch học theo mã sinh viên.
  - Hiển thị lịch học tương ứng với mã sinh viên.
- Xem danh sách phòng trống theo tòa nhà.

[Trang chủ CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn)

![Logo SmartCampus](https://placehold.co/256x256?text=SmartCampus)

> ⚠️ Dự án đang trong giai đoạn phát triển, chưa dùng cho mục đích chính thức.

---

## Cài đặt

```bash
git clone https://github.com/clb-lap-trinh/smartcampus.git
npm install
npm start
```

## Tiến độ tính năng

- [x] Tra cứu lịch học theo mã sinh viên
- [x] Xem danh sách phòng trống theo tòa nhà
- [ ] Thông báo đẩy (push notification)
- [ ] Đăng nhập bằng tài khoản trường

## Thư viện

| Thư viện | Phiên bản | Mục đích |
|:---|:---:|:---|
| React Native | 0.74 | Xây giao diện đa nền tảng iOS/Android |
| Axios | 1.6 | Gọi API lấy dữ liệu lịch học |

## :rocket: Tài liệu API

API là thuật ngữ được dùng trong ứng dụng để lấy dữ liệu lịch học. Xem phần giải thích trong [`api_giai_thich.md`](api_giai_thich.md).

Trong Markdown, viết `\*` để hiển thị nguyên văn dấu \* thay vì dùng nó làm ký hiệu định dạng.
