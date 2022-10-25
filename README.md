# Lab2/Ex10 Vietnamese
Describe code:
Mỗi lần PacMan di chuyển là giá trị mảng matrix_buffer[8] sẽ thay đổi:
Đầu tiên em sẽ tính hết giá trị của mỗi bước di chuyển cho các trường hợp ở hàm shiftmatrix
Sau đó em copy giá trị qua matrix_buffer[8] thông qua hàm copymatrix
Trong hàm main, em tạo biến shift_matrix để đếm khi nào quét hết LED ma trận. Mỗi khi index_led_matrix == MAX_LED_MATRIX 
thì shift_matrix++. Em để trong setTimer1 và setTimer1(20) để xem kết quả.
