# Lab2/Ex6 Vietnamese
Report 1:
Nếu không có setTimer0(1000) thì timer0\_flag = 0 theo mặcc định nên vô while, sofware timer sẽ không chạy.
Report 2:
Nếu setTimer0(1) thì time0\_duration = 1/10 nên time0\_duration = 0 và khi vô hàm timer\_run sẽ không chạy nên sofWare timer cũng không chạy.
Report 3:
Nếu setTimer0(10) thì theo lý thuyết:
So với trường hợp 1: do có setTimer0 nên timer0\_flag sẽ không theo mặc định nữa.
So với trường hợp 2: timer0\_duration=10/10=1 vô vô hàm timer\_run sẽ chạy và timer0\_flag = 1.
Nhưng khi ta vừa setTimer xong thi nó sẽ xảy ra ngắt liền nên ta sẽ mất đi 10ms đầu và nó gần như là không có bất kỳ một delay nào xảy ra cả.
