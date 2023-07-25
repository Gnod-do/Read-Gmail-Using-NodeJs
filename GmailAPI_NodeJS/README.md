# GmailAPI_NodeJS

## How to Run:

Clone this repo > Run command `npm install`  > Then run `npm run test` 

Note: Also make sure you change your client id , refresh token, client secrets ect..

description: API này dùng để read, decode message nhận được server -> client

-----------

Quy trình thực hiện:
1. Đăng kí cloud google dành cho developer - cái này dùng để lưu trữ các dự án cũng như sẽ cho client_id, api tích hợp
2. Sau đó cần tạo request ở postman - có thể xem chi tiết ở file json trong đường dẫn này https://github.com/afsarali273/GmailAPI/blob/master/Gmail/Gmail%20Authentication.postman_collection.json

Trong file này cần sửa client_id và cấu hình thông số cá nhân khác.
3. Sau đó cần refresh token: nghĩa là cần cấu hình lại 1 mã thông báo mới sau 1 khoảng thời gian nhất định người nhận nhận được thông báo
4. Access token: Cho phép quyền truy cập vào liên kết
5. Get emails: đưa vào mã email nhận được message
6. Search for Message: cái này support để tìm kiếm 1 message theo mail người gửi, theo mã mail và mã tin nhắn
7. Inbox message: API này tổ hợp lại tất cả các bước trên

Dưới đây là 3 video bổ trợ để config được những thông số cũng như cách đăng ký tài khoản.
https://www.youtube.com/watch?v=8RaSbyk-DJY&list=PLXBKC3hh6AEqpcgZpoIhRoUeads9nu8uG&index=1&t=0s
https://www.youtube.com/watch?v=wq8n4whsOFc&list=PLXBKC3hh6AEqpcgZpoIhRoUeads9nu8uG&index=1&t=0s
https://www.youtube.com/watch?v=GHXT59krs5E