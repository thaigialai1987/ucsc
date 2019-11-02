# hack pass wifi thì có 1 cách khá phổ biến, có tên là "kẻ sinh đôi ma quỷ" (evil twins) như sau:
1. Hacker sẽ thiết lập một Access Point giả nhưng có tên mạng (SSID) giống y hệt Access Point thật.
2. AP giả sẽ "gây nhiễu" việc xác thực từ các máy người dùng đến AP thật, khiến người dùng không thể truy cập đến AP thật.
3. Người dùng kết nối đến AP giả mạo (vì nhầm tên mạng). Lúc này, hacker tạo một giao diện yêu cầu người dùng nhập account truy cập wifi. Khi người dùng nhập mật khẩu, hacker sẽ có được tài khoản này.
4. Hacker sử dụng tài khoản ở bước 2 để truy cập vào Access Point thật. Từ đó hacker tiếp tục thực hiện tấn công vào hệ thống mạng.
# Tool
[Fluxion](https://github.com/FluxionNetwork/fluxion)