# **Bài giảng: Biến và các kiểu dữ liệu cơ bản**

## 1. **Khái niệm về biến, khai báo biến và quy tắc đặt tên**

- **Biến** là một khu vực trong bộ nhớ được dùng để lưu trữ dữ liệu.
- **Khai báo biến** trong JavaScript:
  ```javascript
  let age = 25;
  const name = "John";
  var city = "Hanoi";
  ```
- **Quy tắc đặt tên biến:**
  - Chỉ dùng chữ, số, “$”, “\_”.
  - Phải bắt đầu bằng chữ, “$” hoặc “\_”.
  - Phân biệt chữ hoa, chữ thường.
  - Không dùng từ khoá.

## 2. **So sánh let và const**

| Thuộc tính               | let                     | const                      |
| ------------------------ | ----------------------- | -------------------------- |
| Khả năng gán lại giá trị | Có thể thay đổi giá trị | Không thể thay đổi giá trị |
| Phạm vi hoạt động        | Block scope             | Block scope                |

## 3. **Kiểu dữ liệu cơ bản**

- **Number:**
  ```javascript
  let x = 10;
  ```
- **String:**
  ```javascript
  let message = "Hello World";
  ```
- **Boolean:**
  ```javascript
  let isAvailable = true;
  ```
- **In ra màn hình với console.log:**
  ```javascript
  console.log(x);
  console.log(typeof x);
  ```

## 4. **Xử lý toán cơ bản**

```javascript
let a = 10,
  b = 5;
console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
console.log(a % b);
```

## 5. **Sử dụng module Math**

```javascript
console.log(Math.max(10, 20, 30));
console.log(Math.min(10, 20, 30));
console.log(Math.round(4.7));
console.log(Math.sqrt(16));
```

## 6. **Format String**

```javascript
let name = "Alice";
let age = 25;
console.log(`Tên: ${name}, Tuổi: ${age}`);
```

---

# **Bài giảng: Cấu trúc điều kiện**

## 1. **Giá trị Boolean**

```javascript
let isLoggedIn = true;
console.log(isLoggedIn);
```

## 2. **Toán tử so sánh và logic**

```javascript
console.log(5 > 3);
console.log(5 < 3);
console.log(true && false);
console.log(true || false);
console.log(!true);
```

## 3. **Cấu trúc if-else**

```javascript
let score = 80;
if (score >= 90) {
  console.log("Xuất sắc");
} else if (score >= 70) {
  console.log("Khá");
} else {
  console.log("Trung bình");
}
```

## 4. **Cấu trúc switch-case**

```javascript
let day = 2;
switch (day) {
  case 1:
    console.log("Thứ hai");
    break;
  case 2:
    console.log("Thứ ba");
    break;
  default:
    console.log("Không xác định");
}
```

## 5. **Toán tử 3 ngôi**

```javascript
let age = 18;
let status = age >= 18 ? "Người lớn" : "Trẻ em";
console.log(status);
```

---

# **Bài giảng: Vòng lặp trong JavaScript**

## 1. **Vòng lặp for**

- Dùng khi số lần lặp biết trước.
- Cú pháp:
  ```javascript
  for (khởi_tạo; điều_kiện; bước_lặp) {
    // Khối lệnh
  }
  ```
- Ví dụ:
  ```javascript
  for (let i = 0; i < 5; i++) {
    console.log("Lần lặp: ", i);
  }
  ```

## 2. **Vòng lặp while**

- Dùng khi số lần lặp không xác định trước.
- Cú pháp:
  ```javascript
  while (điều_kiện) {
    // Khối lệnh
  }
  ```
- Ví dụ:
  ```javascript
  let i = 0;
  while (i < 5) {
    console.log("Giá trị i: ", i);
    i++;
  }
  ```

## 3. **Vòng lặp do-while**

- Luôn chạy ít nhất một lần, dù điều kiện sai ngay từ đầu.
- Cú pháp:
  ```javascript
  do {
    // Khối lệnh
  } while (điều_kiện);
  ```
- Ví dụ:
  ```javascript
  let j = 0;
  do {
    console.log("Lần lặp: ", j);
    j++;
  } while (j < 5);
  ```
---

# **Bài tập nâng cao**

1. **In các số từ 1 đến 100 chia hết cho 3 và 5.**
2. **Tính tổng các số từ 1 đến n bằng vòng lặp.**
3. **In bảng cửu chương từ 1 đến 9.**
4. **In dãy Fibonacci tới số n.**
5. **Tính giai thừa của một số.**
6. **Vẽ tam giác sao đầy.**
7. **Tìm số nguyên tố lớn nhất trong một mảng.**
