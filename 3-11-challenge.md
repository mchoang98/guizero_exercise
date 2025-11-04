### **Bài Tập 1: Trụ Đèn Giao Thông Tự Động**

**Yêu cầu:**

* Tạo 3 nút tượng trưng đèn đỏ – vàng – xanh, không nhấn được.
* Tự động chuyển đèn theo thứ tự **Đỏ → Vàng → Xanh → Đỏ**.
* Hiển thị **đếm ngược 10 giây** trước khi chuyển đèn.

**Gợi ý:**

1. Dùng `App` làm cửa sổ, `Box` xếp 3 nút `PushButton` theo trụ.
2. Biến `state` lưu trạng thái đèn hiện tại, biến `countdown = 10`.
3. Viết hàm `change_light()` đổi màu nút theo `state` và reset `countdown`.
4. Viết hàm `countdown_timer()` giảm `countdown` mỗi giây, khi về 0 gọi `change_light()` và tiếp tục đếm ngược.
5. `Text` dưới trụ đèn hiển thị `"Chuyển sau: X s"`.


<img width="184" height="534" alt="image" src="https://github.com/user-attachments/assets/680d0fba-f9d3-4328-a4e3-7d2ff284cd2e" />
<img width="182" height="544" alt="image" src="https://github.com/user-attachments/assets/c5c4b803-4486-452b-92bf-82fa9463f2d4" />
<img width="186" height="540" alt="image" src="https://github.com/user-attachments/assets/ff3bc7aa-9f80-4ecb-a566-4a733760fa23" />


### **Bài Tập 2: Bảng điểm học sinh**

Tạo một bảng điểm môn học bằng guizero với các yêu cầu sau:

Tiêu đề chính: “Điểm môn học”, trải đều 2 cột.

Cột Môn: Liệt kê các môn học (Toán, Văn, Anh).

Cột Điểm: Liệt kê điểm tương ứng (8, 9, 10).

Điểm trung bình: Hiển thị dưới cùng, span cả 2 cột.

Giao diện:

Sử dụng Box để sắp xếp các Text theo grid.

Các ô cân đối về kích thước.

Có viền (border) cho các Box.

Gợi ý:

Dùng Box với layout="grid" cho từng cột.

Dùng Text để hiển thị tiêu đề, môn, điểm và điểm trung bình.

Sử dụng grid=[x,y] hoặc grid=[x,y,xspan,yspan] để căn chỉnh các ô.

<img width="621" height="617" alt="image" src="https://github.com/user-attachments/assets/c64bad91-3fa6-4233-8930-212301f8d987" />



### **BÀI TẬP 3: ỨNG DỤNG HỘP QUÀ GACHA**

**Mục tiêu:**
Lập trình ứng dụng bằng **guizero** mô phỏng mở hộp quà Gacha.

**Yêu cầu:**

1. Tạo giao diện gồm:

   * Một hình ảnh hộp quà *mặc định* (`question.png`).
   * Một nút **"MỞ HỘP"**.

2. Khi nhấn nút:

   * Chương trình chọn **ngẫu nhiên** một vật phẩm theo tỉ lệ:

     * Normal → 60%
     * Epic → 30%
     * Rare → 10%

3. Sau khi chọn:

   * Hiển thị **ảnh vật phẩm** tương ứng (`normal.png`, `epic.png`, `rare.png`).
   * Hiển thị tên vật phẩm với màu chữ theo độ hiếm:

     * Normal → xanh dương (blue)
     * Epic → tím (purple)
     * Rare → vàng (gold/yellow)

**Gợi ý:**

* Dùng `random.choices()` để random theo phần trăm.
* Dùng `Picture` để đổi hình.
* Dùng `Text` để đổi nội dung và màu chữ.

<img width="367" height="484" alt="image" src="https://github.com/user-attachments/assets/ea76446f-d7ca-43bb-92b1-be8f9b3ed787" />



