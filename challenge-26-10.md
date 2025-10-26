## PROBLEM 1: TRẮC NGHIỆM MỘT CÂU HỎI

### Problem Description

Tạo ứng dụng GUI bằng `guizero` hiển thị câu hỏi:
"Thủ đô của Việt Nam là gì?"

Có 3 nút lựa chọn:

* "Hà Nội"
* "TP.HCM"
* "Đà Nẵng"

Khi người dùng bấm một nút:

* Nếu chọn "Hà Nội" thì in ra "Đúng!"
* Nếu chọn lựa chọn khác thì in ra "Sai!"

Kết quả in ra bằng `print` trong console.

### GUI Layout Requirements

* Sử dụng `App(title="Quiz App")`.
* Dùng `Text` để hiển thị câu hỏi ở đầu cửa sổ.
* 3 nút được sắp theo hàng ngang (layout="auto" hoặc `Box` chứa 3 `PushButton`).
* Mỗi nút có độ rộng bằng nhau, căn giữa trong cửa sổ.
* Kích thước cửa sổ: khoảng 300x200.

**Sơ đồ bố cục (mô tả bằng chữ):**

```
-----------------------------------
| Thủ đô của Việt Nam là gì?      |
| [Hà Nội] [TP.HCM] [Đà Nẵng]     |
-----------------------------------
```

---

## PROBLEM 2: QUAY SỐ NGẪU NHIÊN

### Problem Description

Tạo ứng dụng GUI bằng `guizero` có một nút duy nhất “Quay số”.
Khi bấm nút, in ra một số ngẫu nhiên từ 1 đến 100 trong console.

### GUI Layout Requirements

* Dùng `App(title="Random Number")`.
* Một `PushButton` duy nhất đặt giữa màn hình.
* Có thể căn giữa bằng `Box` hoặc dùng `align="top"` và `align="bottom"` hợp lý.
* Kích thước cửa sổ: khoảng 200x150.
* Nút nên có kích thước vừa phải (width=10, height=2).

**Sơ đồ bố cục:**

```
---------------------
|                   |
|     [Quay số]     |
|                   |
---------------------
```

---

## PROBLEM 3: THAY ĐỔI HÌNH ẢNH

### Problem Description

Tạo ứng dụng GUI bằng `guizero` hiển thị một hình ảnh và 3 nút:
“Mèo”, “Chó”, “Chim”.
Khi nhấn nút, ảnh thay đổi tương ứng (`cat.png`, `dog.png`, `bird.png`).

### GUI Layout Requirements

* Sử dụng `App(title="Image Viewer")`.
* Ảnh hiển thị ở giữa trên (dùng `Picture`).
* Dưới ảnh là 3 nút đặt theo hàng ngang (dùng `Box` chứa `PushButton`).
* Kích thước cửa sổ: 400x350.
* Ảnh nên vừa với cửa sổ (width khoảng 200–250px).

**Sơ đồ bố cục:**

```
---------------------------------
|             [ẢNH]              |
|  [Mèo]   [Chó]   [Chim]       |
---------------------------------
```

---

## PROBLEM 4: TRÒ CHƠI OẲN TÙ TÌ

### Problem Description

Tạo ứng dụng GUI bằng `guizero` có 3 nút “Kéo”, “Búa”, “Bao”.
Khi bấm nút, chương trình chọn ngẫu nhiên nước đi cho máy và in ra console:
`You: Kéo | Computer: Bao | Result: Win`

### GUI Layout Requirements

* Sử dụng `App(title="Rock Paper Scissors")`.
* Phần tiêu đề `Text("Chọn một trong ba:")` hiển thị ở trên.
* 3 nút “Kéo”, “Búa”, “Bao” sắp theo hàng ngang, cách nhau đều.
* Có thể dùng `Box` để gom các nút.
* Kích thước cửa sổ: khoảng 300x200.

**Sơ đồ bố cục:**

```
---------------------------------
|       Chọn một trong ba:      |
|  [Kéo]   [Búa]   [Bao]        |
---------------------------------
```

---

## PROBLEM 5: ĐIỀU KHIỂN LED ẢO

### Problem Description

Tạo ứng dụng GUI mô phỏng 3 đèn LED: “LED 1”, “LED 2”, “LED 3”.
Mỗi LED có một nút riêng để bật/tắt.
Khi nhấn nút, LED tương ứng đổi màu (từ xám sang xanh và ngược lại).

### GUI Layout Requirements

* Sử dụng `App(title="LED Control")`.
* 3 LED hiển thị bằng `Box` hoặc `Text`, đặt hàng ngang ở giữa.
* Bên dưới là 3 nút điều khiển “LED 1”, “LED 2”, “LED 3”.
* Mỗi nút tương ứng với một LED.
* Cửa sổ kích thước khoảng 400x300.
* Khi LED bật → đổi màu nền Box/Text sang “green”.
* Khi tắt → đổi lại “gray”.

**Sơ đồ bố cục:**

```
---------------------------------------
|   [LED1]   [LED2]   [LED3]          |
|   [Nút 1]  [Nút 2]  [Nút 3]         |
---------------------------------------
```


