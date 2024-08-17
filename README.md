![Ảnh chụp màn hình 2024-08-17 173807](https://github.com/user-attachments/assets/bfcbfe62-6e3f-46e5-bada-8aa1a4fe01a7)
![Ảnh chụp màn hình 2024-08-17 173752](https://github.com/user-attachments/assets/64ee6926-1b87-4d4a-b769-c13ba3f1950b)
![Ảnh chụp màn hình 2024-08-17 173703](https://github.com/user-attachments/assets/7f3e21dc-4b03-4153-951a-164f91c2037c)
![Ảnh chụp màn hình 2024-08-17 173608](https://github.com/user-attachments/assets/158854ed-6829-463b-997a-985e7a5b687a)
![Ảnh chụp màn hình 2024-08-17 173549](https://github.com/user-attachments/assets/2f5afbd6-5514-4e8f-933d-90c004cf7e83)
# MinesweeperSDL2
# Giới thiệu về trò chơi
* Dựa trên game [Minesweeper](https://vi.wikipedia.org/wiki/D%C3%B2_m%C3%ACn_(tr%C3%B2_ch%C6%A1i)) của Microsoft, trò chơi được làm bằng ngôn ngữ C++ và thư viện đồ hoạ SDL2.
* Mọi thông tin về thư viện SDL2, các cú pháp thường sử dụng tham khảo tại: https://www.libsdl.org/
* Cách tải, liên kết thư viện SDL2 với project và tutorial SDL2, tham khảo tại: https://lazyfoo.net/tutorials/SDL/index.php
* Trò chơi có sử dụng hình ảnh tại: https://www.flaticon.com/
* Hướng dẫn tải game: Sau khi tải code về dưới dạng zip, giải nén và chạy code bằng cách vào mục "GAMEPROJECT.sln" (chạy bằng Visual Studio)  . 
* Mọi hình ảnh, âm thanh và font chữ được sử dụng trong trò chơi được lưu trong thư mục res.


 # Cách chơi
 * Giống như trò dò mìn truyền thống, bạn phải mở các ô trên bảng sao cho không mở phải ô chứa mìn. Mỗi số ở các ô biểu thị cho số lượng mìn ở xung quanh ô đó. Nếu mở phải ô chứa mìn, bạn sẽ thua. Nếu mở được tất cả các ô không có mìn, bạn sẽ thắng. Nếu bạn muốn chơi lại, hãy nhấn vào biểu tượng mặt cười ở trên cửa sổ game. 
 * Có 4 chế độ có thể lựa chọn:
    * Dễ: gồm 9 hàng, 9 cột và 10 mìn.
    * Trung bình: gồm 16 hàng, 16 cột và 40 mìn.
    * Khó: gồm 30 hàng, 16 cột và 99 mìn.
    * Tự chọn: Bạn có thể nhập số hàng, số cột và số mìn mà bạn muốn vào các ô tương ứng trên cửa sổ. 
 * Sau mỗi lần chiến thắng, thời gian mà bạn hoàn thành sẽ được lưu vào file txt trong thư mục score. Với chế độ tự chọn, trò chơi sẽ tự tạo file txt tương ứng với số liệu mà bạn nhập vào. 
     
