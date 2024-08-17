# MinesweeperSDL2
# Giới thiệu về trò chơi
* Dựa trên game [Minesweeper](https://vi.wikipedia.org/wiki/D%C3%B2_m%C3%ACn_(tr%C3%B2_ch%C6%A1i)) của Microsoft, trò chơi được làm bằng ngôn ngữ C++ và thư viện đồ hoạ SDL2.
* Mọi thông tin về thư viện SDL2, các cú pháp thường sử dụng tham khảo tại: https://www.libsdl.org/
* Cách tải, liên kết thư viện SDL2 với project và tutorial SDL2, tham khảo tại: https://lazyfoo.net/tutorials/SDL/index.php
  https://www.youtube.com/watch?v=k1JGvJU707k&list=PLR7NDiX0QsfQQ2iFXsXepwH46wf3D4Y4C
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
 * Một vài hình ảnh về game:
 ![Ảnh chụp màn hình 2024-08-17 173549](https://github.com/user-attachments/assets/9b4b4261-c98d-4df5-b97d-ba01e4cef02a)
![Ảnh chụp màn hình 2024-08-17 173608](https://github.com/user-attachments/assets/8f8b6892-f485-402c-8e19-bf20fc238244)
![Ảnh chụp màn hình 2024-08-17 173752](https://github.com/user-attachments/assets/18201ccf-db66-4b11-9e4b-af1d6b0f72ef)
![Ảnh chụp màn hình 2024-08-17 173703](https://github.com/user-attachments/assets/a0bd69c1-29d5-43c8-9b33-6870ff730830)

* Chế độ custom:

![Ảnh chụp màn hình 2024-08-17 173807](https://github.com/user-attachments/assets/6ac34156-0db6-4323-b4e5-61f7287f419e)


     
