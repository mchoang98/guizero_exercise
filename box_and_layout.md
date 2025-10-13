

## **Bài 1: Bảng danh sách học sinh (GUI mô phỏng chi tiết)**

```
+---------------------------------------------------------------+
|                     Danh sách học sinh                        | <- column span 6
+--------+-----+---------+-----+-----------+-------------------+
| Tên    | Tuổi| Trường  | Lớp | Giới Tính | Sở Thích          |
+--------+-----+---------+-----+-----------+-------------------+
| An     | 12  | THCS A  | 6A  | Nam       | Bóng đá           |
| [ảnh]  |     |         |     |           |                   |
+--------+-----+---------+-----+-----------+-------------------+
| Bình   | 11  | THCS B  | 5B  | Nam       | Đọc sách          |
| [ảnh]  |     |         |     |           |                   |
+--------+-----+---------+-----+-----------+-------------------+
| Cường  | 12  | THCS C  | 6C  | Nam       | Âm nhạc           |
| [ảnh]  |     |         |     |           |                   |
+--------+-----+---------+-----+-----------+-------------------+
```

**Giải thích:**

* Mỗi học sinh có thể thêm **[ảnh]** vào cột đầu (hoặc bên cạnh).
* Tiêu đề bảng **column span 6**.
* Học sinh có thể hình dung vị trí Box + Grid trước khi lập trình.

---

## **Bài 2: Album cầu thủ bóng đá (GUI mô phỏng chi tiết)**

```
+---------------------------------------------------------------+
|           Album cầu thủ bóng đá nổi tiếng                     | <- column span 3
+----------------+----------------+----------------------------+
| [ảnh Messi]    | [ảnh Ronaldo]  | [ảnh Mbappe]               |
| Messi          | Ronaldo        | Mbappe                     |
| Argentina      | Bồ Đào Nha     | Pháp                       |
| Tiền đạo       | Tiền đạo       | Tiền đạo                   |
+----------------+----------------+----------------------------+
```

**Giải thích:**

* Mỗi thẻ cầu thủ là 1 cột trong Grid.
* Dòng đầu là **[hình ảnh]**, sau đó là tên, quốc gia, vị trí.
* Tiêu đề album **column span = 3** (nối 3 cột).

