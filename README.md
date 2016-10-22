I)KHÁI NIỆM CON TRỎ  

-Con trỏ là một biến dùng để chứa địa chỉ  

-Vì có nhiều loại địa chỉ nên cũng có nhiều kiểu con trỏ tương ứng: +Kiểu con trỏ int dùng để chứa địa chỉ biến kiểu int 

                                                                   +Tương tự ta có con trỏ kiểu float, kiểu double,…  
-Cũng như với 1 biến bất kỳ nào khác, con trỏ cần được khai báo trước khi sử dụng  
*KHAI BÁO:   

<kiểu_DL> * <tên_biến_con_trỏ>;  
 VÍ DỤ: 
 int a,*p;
 float b,c,*p,*q;  
II Toán tử lấy địa chỉ (&)
-Địa chỉ: Khi khai báo biến, máy sẽ cấp phát cho biến một khoảng nhớ. 
-Địa chỉ của biến là số thứ tự của byte đầu tiên trong một dãy các byte liên tiếp mà máy dành cho biến (các byte được đánh số từ 0). 
-Máy phân biệt các loại địa chỉ như các biến. Ví dụ như: địa chỉ kiểu int, kiểu float,…
-Vào thời điểm mà chúng ta khai báo một biến thì nó phải được lưu trữ trong một vị trí cụ thể trong bộ nhớ.
-Chúng ta không quyết định nơi nào biến đó được đặt, điều đó làm tự động bởi trình biên dịch và hệ điều hành.
-Nhưng khi hệ điều hành đã gán một địa chỉ cho biến thì chúng ta cần biết biến đó được lưu trữ ở đâu.
-Điều này được thực hiện bằng cách đặt trước tên biến một dấu và (&).

  

 
