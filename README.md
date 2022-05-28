# **Snakegame**


## Mục lục
1. [Hướng dẫn cài đặt](#hướng-dẫn-cài-đặt-game)
2. [Mô tả chung](#mô-tả-chung)
3. [Các chức năng](#các-chức-năng)
4. [Thuật toán của game](#thuật-toán-của-game) 
5. [Kết luận](#kết-luận)

### Nội dung
1. ### Hướng dẫn cài đặt game

    - Cài đặt Code::Blocks, SDL2, SDL_ttf, SDL_mixed, SDL_image,..

    - Fork repo BTL_Snakegame và git clone về máy

    Sau đó mở `Code::Blocks` và nhấn vào thư mục đã clone về. Mở file "Snake.cpp.cpp" rồi build&run

2. ### Mô tả chung
 
    Rắn săn mồi là 1 trò chơi cổ điển, xuất hiện vào năm 1997 trên Nokia, gồm những ô vuông di chuyển trên nền màu xanh
    
3. ### Các chức năng

    Luật chơi:
      - Tạo ra 1 nền tĩnh có thức ăn sinh ngẫu nhiên
      - Hoạt động của rắn: Người chơi điều khiển rắn bằng các nút mũi tên  ⇧, ⇩, ⇦, ⇨ sao cho rắn ăn được thức ăn  và không bị cắn vào đuôi hay đâm vào tường. Rắn không thể quay đầu lại.
      - Có 3 level chơi:
          + Level dễ(E): Tốc độ rắn là 300ms, sau mỗi lần ăn, người chơi được + 20 điểm
          + Level trung bình(M): Tốc độ là 220ms, sau mỗi lần ăn được cộng 25 điểm
          + Level khó(H): Tốc độ 150ms, sau mỗi lần ăn cộng 30 điểm
      - Mỗi khi bị cắn vào đuôi hoặc đâm đầu vào tường, trò chơi sẽ kết thúc, hiển thị điểm người chơi
    
4. ### Thuật toán của game
    -------------------------------
   - Ngôn ngữ lập trình: C++
   - Thư viện đồ họa: SDL2
   - Sử dụng các ký thuật lập trình cơ bản: Hàm, vòng lặp, câu lệnh điều kiện,///

5. ### Kết luận

    * Ưu điểm:
      - Biết sử dụng thư viện đồ họa SDL2
      - Nâng cao được kiến thức lập trình
      - Tạo được âm thanh cho trò chơi và 1 số chức năng khác.
    * Khuyết điểm:
      - Game còn khá cổ điển, cơ bản
      - Chưa làm được những chức năng nâng cao như xây vật cản, lưu điểm, hướng dẫn chơi, bật/tắt âm thanh

    * Hướng phát triển:
      - Nâng cấp màn chơi để người chơi nó nhiều lựa chọn
      - Xây dựng nhiều vật cản, cách bố trí vật cản trong tứn mức độ chơi
      - Phát triển thành game nhiều người chơi để mọi người có thể thi đấu trực tiếp với nhau..
    




