Daily Homeworks
(15/4/2021)

Question 1: 
Sử dụng Githb, chúng ta có thể code 1 project trên nhiều máy tính khác nhau hay không? (Bạn vừa code ở máy của thư viện, vừa code của ở máy tính của mình) Tại sao
*
Chúng ta có thể code cùng 1 project ở trên nhiều máy tính khác nhau bởi vì mỗi lần code, khi chúng ta commit lên repo của project thì mọi thay đổi đều được lưu lại lịch sử (thời gian, người thay đổi, nội dung thay đổi). Việc lưu lại các commit thay đổi sẽ giúp chúng ta dễ dàng quản lý source code hơn bao giờ hết.

Question 2:
Có cách nào để trên Github cập nhật được những thay đổi của mình vửa commit ở máy tính của mình hay không?
*
- Có
- Các bước thực hiện
+ git status: kiểm tra xem có những gì thay đổi hay không?
+ git add . :thêm tất cả các thay đổi của mình trong working area vào 
+ git commit –m “<message>”: đưa tất cả những thay đổi của mình vào kho lưu
                                                   trữ Storage Area
+ git push origin master: đẩy tất cả những thay đổi đã commit được lưu ở 
                                          Storage Area lên Repo (nơi lưu trữ các thay đổi đối
                                          với project cả chúng ta sau khi chúng ta đã tạo repo ở
                                          trên Github và remote chúng với project ở máy chúng
                                          ta 
                                          (Remote: git remote add origin <Link repo>
Question 3: 
Có cách nào để lấy tất cả các thay đổi mới nhất trên Github về máy tính của mình?
*
- Chuột phải vào nơi chúng ta muốn pull pull project trên Github về, chọn GitBash
- Sử dụng lệnh sau: “git pull origin master” để pull tất cả các thay đổi trong project trên Github về máy của chúng ta 
- Ngoài ra, chúng ta còn 1 cách khác là sử dụng git clone trong trường hợp chúng ta xóa project cũ đi để tải về mới toàn bộ
  “git clone <Link repo>”
