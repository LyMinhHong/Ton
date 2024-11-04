#TON Nhiệm vụ kiểm tra liên kết

### Thử nghiệm

Bạn có thể xem phiên bản demo của ứng dụng tại liên kết sau:

[Ứng dụng demo](https://ton-test-task.vercel.app)

## Sự miêu tả

Một ứng dụng một trang được xây dựng bằng Next.js và thư viện ton-connect. Ứng dụng này cho phép người dùng kết nối ví tiền điện tử TonKeeper, xem số dư của họ và thực hiện chuyển tiền sang mạng TestNet TON với giao diện trực quan.

##Hướng dẫn sử dụng

- **Kết nối ví**:
 - Để liên kết ví TonKeeper của bạn, hãy nhấp vào nút "Liên kết ví".
 - Trong hộp thoại chọn ví TonKeeper.
 - Xác nhận link ví trong ứng dụng TonKeeper.

- **Gửi tiền**:
 - Trên màn hình chính, nhấp vào nút "Gửi" để đến trang chuyển tiền.
 - Nhập số tiền cần thiết và địa chỉ người nhận vào mẫu chuyển khoản để bắt đầu quá trình gửi.
 - Xác nhận chuyển khoản trong ví TonKeeper của bạn.

## Công nghệ

- **@tonconnect/ui-react** - Thư viện để tích hợp với ví TonKeeper thông qua TonConnect.
- **next** - Một framework để tạo các ứng dụng tĩnh và phía máy chủ trong React.
- **tailwindcss** - Một khung CSS tiện dụng để tạo giao diện người dùng.
- **typescript** - Ngôn ngữ lập trình để gõ mạnh bằng JavaScript.

## Cài đặt và khởi chạy ứng dụng

1. Sao chép kho lưu trữ:
``` bash
bản sao git https://github.com/roman-pixel/ton-test-task.git
```

2. Vào thư mục dự án

3. Cài đặt các phần phụ thuộc bằng sợi hoặc npm:

 ``` bash
 cài đặt npm
 ```
4. Khởi chạy ứng dụng

``` bash
npm chạy dev
```

