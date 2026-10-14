# Tai Cau Truc Template Sass

Bài CodeGym 1516.

## Chạy
`npm ci`, `npm run build`, sau đó mở index.html. `npm run build:min` tạo CSS nén; `npm run watch` theo dõi thay đổi. PowerShell có thể dùng npm.cmd.

## Tái cấu trúc
Nguồn bố cục/mã Template đã thực hiện: bài 1553, https://github.com/vietdotest/codegym18-1553-website-template-advanced. Bài 1516 không đính kèm hình hoặc file thiết kế khác. Sử dụng cùng header, navigation, card dịch vụ và footer; bổ sung khối thống kê vào bản CSS nền để đủ các phần đề liệt kê. Sau đó tái cấu trúc SCSS giữ nguyên bản nền này. Tách variables, mixins, base, layout, components và responsive; Nesting giữ selector gốc.

Dùng @use để gộp partials. CSS đã biên dịch được commit để có thể mở trang ngay.

## Đối chiếu
Mở original.html để xem bản CSS ban đầu. Kết quả biên dịch tại build-validation.json; kiểm tra computed styles và bố cục trước/sau tại validation.json.
