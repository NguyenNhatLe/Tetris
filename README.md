# Tetris
BÁO CÁO BÀI TẬP LỚN MÔN LẬP TRÌNH NÂNG CAO - INT2215_1

Họ và tên: Nguyễn Nhật Lê
MSSV: 21020347
Tựa game: Tetris

1. Cách lấy và chạy chương trình:
Bước 1: Download từ github file zip chứa toàn bộ code & thư viện, hình ảnh, âm thanh từ github
Bước 2: Giải nén, tìm và chạy file Tetris.exe để chạy game.
2. Mô tả chung về trò chơi, các ý tưởng chính:
Di chuyển các khối gạch đang rơi từ từ ngẫu nhiên xuống trong kích thước hình chữ nhật 20 hàng x 10 cột (trên màn hình). Chỗ nào có gạch rồi thì không di chuyển được tới vị trí đó. Người chơi xếp những khối hình sao cho khối hình lấp đầy 1 hàng ngang và hàng ngang ấy sẽ biến mất.
Được điều khiển bằng 4 phím -  [LEFT], [RIGHT],[DOWN],[UP].

3. Mô tả các chức năng đã cài đặt
Video minh họa

Mô tả:
Cách khối gạch có hình dạng bất kì sẽ rơi xuống, người chơi dùng các phím mũi tên [LEFT], [RIGHT],[DOWN] để di chuyển khối gạch, phím [UP] để thay đổi hình dạng viên gạch theo ý muốn. Khi 1 hàng ngang được lấp đấy bởi các viên gạch sẽ biến mất, những khối gạch ở bên trên sẽ rơi xuống vị trí tương ứng đến . Game kết thúc khi viên gạch chạm ví trí cao nhất trên hình chữ nhật kích thước 20x10.
Có nhạc nền trong suốt thời gian chơi. 
4. Các kỹ thuật lập trình được sử dụng trong chương trình:
Các kỹ thuật lập trình
Sử dụng mảng , xâu (string), hàm rand();
Sử dụng biến const, con trỏ và tham chiếu;
Sử dụng struct ;
Sử dụng thư viện <SFML/Graphics.hpp> ; <SFML/Audio.hpp> ; <time.h>
Xử lí sự kiện chuột, bàn phím;

5. Kết luận, hướng phát triển và các điều tâm đắc rút ra được sau khi hoàn thiện chương trình:
Qua quá trình suy nghĩ ý tưởng, bắt tay vào làm và hoàn thiện project này, em đã củng cố và học thêm được rất nhiều những điều thú vị và mới mẻ trong các thư viện đồ họa SFML , cách sử dụng hàm, biến trong C++. Em nhận ra được rằng, để làm một project không chỉ cần sự hiểu biết về các hàm, tính năng riêng của từng thư viện mà 1 lập trình viên còn phải biết cách kết hợp chúng và tạo ra các chức năng như mình mong muốn. Ngoài ra, em nhận thấy việc sử dụng các thư viện khác nhau, các ngôn ngữ lập trình khác nhau đều có thể tạo được những chức năng mình mong muốn, miễn là có sự tư duy và hiểu biết của lập trình viên. Em mong rằng trong quá trình học sau này, em có thể được thầy cô chỉ dẫn nhiều hơn nữa để em khám phá ra thêm những kỹ năng mới và những điều thú vị của lập trình.

6. Hướng phát triển game
Bắt đầu game sẽ có màn hình menu lựa chọn để "Start Game", "Exit Game"
Kết thúc trò chơi sẽ hiện ra màn hình "You lose!" 
Thêm các chức năng: tính điểm , chơi lại, âm thanh khi các khối gỗ lấp đầy hàng ngang biến mất.