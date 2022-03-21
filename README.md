# Mod Surviving Mars Việt Hóa
Đây là mod Mod Surviving Mars Việt Hóa phiên bản 1001514

# Giới thiệu
Surviving Mars là một công cụ xây dựng thành phố khoa học viễn tưởng xoay quanh việc thuộc địa hóa sao Hỏa và tồn tại trong quá trình này. Chọn một cơ quan vũ trụ để có tài nguyên và hỗ trợ tài chính trước khi xác định vị trí cho thuộc địa của bạn. Xây dựng mái vòm và cơ sở hạ tầng, nghiên cứu khả năng mới và sử dụng Drone để mở khóa cách phức tạp hơn để định hình và mở rộng khu định cư của bạn. Tự trồng thực phẩm, khai thác khoáng chất hoặc chỉ cần thư giãn bên quầy bar sau một ngày làm việc mệt mỏi. Tuy nhiên, điều quan trọng nhất là giữ cho cư dân của bạn sống sót. Không phải là một nhiệm vụ dễ dàng trên một hành tinh mới lạ.
# Tiến trình dịch 99%
Xem tiến trình dịch và cập nhật mới nhất tại [TIENTRINH.md](TIENTRINH.md)

# Hướng dẫn
## Cài đặt trò chơi

Cài đặt trò chơi Surviving Mars và chạy thử trước khi cài mod

Đề nghị mua trò chơi để ủng hộ nhà sản xuất.

## Phiên bản yêu cầu: v.1001514

Mình dịch trên phiên bản v.1001514 nên có thể không chạy hoặc có lỗi trên phiên bản khác

## Cài đặt mod

- Tải tất cả thư mục [Vietnamese](Vietnamese/) trong này
- Copy và dán vào thư mục **AppData\Roaming\Surviving Mars\Mods**
- Nếu không có thư mục **Mods** thì tạo thư mục **Mods** và dán thư mục **Vietnamese** vào
- Khởi động game vào **PARADOX MOD MANAGER** -> **Installed Mods**
- Bật mod **Vietnamese**

## Tìm thư mục AppData

- Ấn phím window hoặc tổ hợp phím Ctrl + ESC
- Nhập `%AppData%` rồi ấn phím Enter trên bàn phím
## Hướng dẫn dịch

Trong thư mục [Vietnamese](Vietnamese/) có 3 tập tin bạn chỉ cần quan tâm đến tập tin [Vietnamese.csv](Vietnamese/Vietnamese.csv)

Cấu trúc của tập tin [Vietnamese.csv](Vietnamese/Vietnamese.csv) là: ```ID,Text,Translation``` (Ngay dòng đầu tiên là bạn thấy)

Bạn chỉ việc thay nhập thêm phần dịch ở **Translation** thôi ví dụ:
```ID,Text,Translation```
dịch thành
```ID,Text,Chữ```
với ```Chữ``` ở đây là dịch ```Text``` ra tiếng Việt

**Chú ý:**
- Nếu trong văn bản dịch của bạn có dấu phẩy ```,``` thì bạn nên xóa bỏ nó để tránh chương trình không nhận hết văn bản dịch
- Nếu muốn giữ dấu phẩy ```,``` trong đoạn văn bản dịch rồi của mình thì nên đoạn văn đó giữa 2 đấu nháy đôi ```"```
- Nếu trong văn bản dịch của bạn cần chèn dấu nháy đôi ```"``` thì bạn nhập 2 dấu nháy đôi liền kề nhau ```""```

    VD: ```Họ nói: ""Ok""``` hoặc ```"Họ nói: ""Ok"""```

- Có một số định nghĩa trong văn bản giữ 2 đấu ```<``` và ```>``` bạn nên để nguyên vì trò chơi sẽ thay thế nó bằng một **giá trị** khác

    VD: ```<ModLabel>``` và ```<u(path)>```

- Một số định nghĩa bạn có thể lợi dụng để trình bày văn bản mình đẹp hơn:
  + ```<newline>``` Xuống dòng
  + ```<green>``` và ```</green>``` văn bản ở giữa màu xanh lá
  + ```<red>``` và ```<red>``` văn bản ở giữa màu đỏ
  + ```<color 128 128 128>``` và ```</color>``` văn bản ở giữa màu rgb(128,128,128)
  + ```<left>``` canh trái
  + ```<right>``` canh phải
  + ```<if(điều kiện)>``` và ```</if>```
  + ```<em>``` và ```</em>```
  + ...

## Công cụ dịch

Dùng Notepad, Notepad++

## Một số thuật ngữ trong bản dịch

+ **Vườn ươm** (Nursery): Tại sao không phải nhà trẻ, mẫu giáo? Mình thích thuật ngữ vườn ươm sao khi nói về các thiên hà có sao mới sinh ra liên tục
+ **Trầm tích** (Deposit): Những gì tích tụ bên dưới mặt đất
+ **Căn cứ** (Colony): Mình không thích thuật ngữ thuộc địa, theo mình thuộc địa là xâm chiếm, cai trị, đồng hóa... **NGƯỜI** khác. Còn hành động khai hoan trên sao Hỏa nó giống hành động khai hoang mãnh đất kế bên và không ai nói hành động phá rừng mở đất là xâm chiếm, hay thuộc địa hóa cả. Hay việc giết, nuôi, giam cầm, nô lệ... động vật là hành vi thuộc địa hóa cả.\
+ **Cư dân** (Colonist): tương tự như trên thì thực dân chỉ phù hợp với kẻ thống trị hơn là khai hoang
+ **Tạo hình** (Terraforming): Nếu dịch là địa hình không phù hợp, mà dịch tạo địa hình cũng không đúng lắm. Trong trò chơi này **Terraforming** được mô tả như hành động thay đổi không khí (tăng ôxy), nhiệt độ, tạo từ trường, trồng thực vật, phát tán vi khuẩn... nhằm biến đổi sao Hỏa thành môi trường thân thiện với con người nó không đơn giản là thay đổi địa hình (đào núi lấp biển)

# Xem thêm hướng dẫn sử dụng github

Nếu chưa biết cách sữ dụng [github](https://github.com) thì bạn có thể xem thêm [ở đây](https://github.com/cackehoa/cackehoa/blob/main/huongdan/HUONG-DAN.md)

# Liên lạc và ủng hộ
Ủng hộ tại: [Playerduo](https://playerduo.com/cackehoa)

Fanpage: [fb](https://www.facebook.com/cackehoa)

Discord: [Discord](https://discord.gg/Z5C98FG)

Youtube: [Cắc kè hoa](https://www.youtube.com/c/Cắckèhoa)
# Giấy phép
[MIT](LICENSE)
