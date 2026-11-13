# ⚔️ VĨNH KIẾP — Roguelike Sinh Tồn Offline

Game sinh tồn kiểu *Vampire Survivors* chạy ngay trên trình duyệt, gói gọn trong **một file `index.html`**. Không cần cài đặt, không cần mạng, tối ưu cho cả điện thoại (cảm ứng) lẫn máy tính (bàn phím).

## Lối chơi

Bạn chọn một anh hùng, bước vào một ải kéo dài khoảng 5 phút và phải sống sót trước làn sóng quái vật ngày càng đông.

- **Vũ khí tự động tấn công** — việc của bạn là di chuyển, né đòn và lùa quái.
- Nhặt **ngọc kinh nghiệm** để thăng cấp. Mỗi cấp chọn 1 trong 3 cường hóa, có thể đổi lựa chọn hoặc bỏ qua.
- Mỗi anh hùng dùng **vũ khí độc quyền** của mình, nhặt thêm **Ngũ Hành Châu** (vũ khí dùng chung) và tối đa **5 bí pháp**, kèm độ hiếm Thường / Hiếm / Truyền thuyết.
- **Tinh anh** rơi rương báu; **trùm** nhiều giai đoạn, hạ trùm để thắng ải trùm.
- Chết hay thắng đều nhận **Tinh Hoa** — giữ lại để nâng cấp vĩnh viễn.

## Nội dung

| | |
|---|---|
| Anh hùng | 12, mỗi người một vũ khí khởi đầu và một kỹ năng riêng (phím E / nút to) |
| Vũ khí | 13 — 12 vũ khí độc quyền của từng anh hùng + Ngũ Hành Châu dùng chung |
| Bí pháp | 8 |
| Ải | 60 ải qua 6 vùng đất: Rừng Sương, Mộ Địa Hồn Treo, Sa Mạc Tàn Tro, Đỉnh Băng Vĩnh Cửu, Hỏa Ngục Tận Thế, Vực Hư Không — cộng chế độ **Vực Vô Tận** |
| Đền Luân Hồi | 11 nâng cấp vĩnh viễn bằng Tinh Hoa |
| Thành tựu | 17 |
| Tốc độ | ×1 / ×2 ngay trong trận |

## Điều khiển

**Máy tính**

| Phím | Tác dụng |
|---|---|
| `WASD` / phím mũi tên | Di chuyển |
| `Space` | Lướt né (bất tử trong khoảnh khắc) |
| `E` | Kỹ năng riêng của anh hùng |
| `1` `2` `3` | Chọn cường hóa khi thăng cấp |
| `R` | Đổi lựa chọn thăng cấp |
| `Esc` | Tạm dừng |

**Điện thoại**: chạm và kéo ở nửa trái màn hình để hiện joystick; nút 💨 lướt né và nút to ⚔️ kỹ năng nằm bên phải; nút ⏸ ở góc trên phải để tạm dừng. Game tự tạm dừng khi bạn rời tab.

## Cách chạy

1. Giải nén, mở `index.html` bằng trình duyệt (Chrome, Safari, Edge, Firefox).
2. Hoặc đưa lên GitHub Pages / bất kỳ hosting tĩnh nào — chỉ cần phục vụ file `index.html`.

Tiến trình (anh hùng, Tinh Hoa, nâng cấp, thành tựu) lưu trong `localStorage` của trình duyệt với khóa `vinhkiep_save_v1`. Xóa tiến trình bằng nút Reset trong game.

## Thay đổi ở bản này

- Sửa lỗi Chưởng Lực không gây sát thương (biến `ang` chưa khai báo).
- Khóa vũ khí độc quyền: vũ khí khởi đầu của mỗi anh hùng không còn lọt vào lựa chọn thăng cấp của anh hùng khác (chỉ Ngũ Hành Châu dùng chung).
- Giao diện màn dọc: nút ×1/⏸ không còn tràn hay bị nút âm thanh che, chip ải gọn lại, thanh trùm và radar dời vị trí.
- Thẻ thăng cấp xếp gọn hơn trên điện thoại; hàng nút của màn Tạm dừng dính ở đáy.
- Chữ hướng dẫn và toast đổi theo thiết bị (cảm ứng / bàn phím).

## Chưa kiểm chứng

Bản này mới được kiểm tra bằng trình duyệt giả lập; chưa thử trên máy thật nên cảm giác cầm tay, FPS thực và âm thanh chưa được xác nhận.
