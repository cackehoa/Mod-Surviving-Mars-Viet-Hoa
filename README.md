# Mod Surviving Mars Việt Hóa
Đây là mod Mod Surviving Mars Việt Hóa phiên bản 1001514

## Lời nói đầu
Mình là nông dân thích chơi trò chơi chỉ là trình độ tiếng Anh của mình khá kém. Mình cũng đã và đang cố học tiếng Anh nhưng quá già để có thể nhớ hết từ vựng. Vì vậy mình muốn dịch một tựa trò chơi để phục vụ cho bản thân mặt khác cũng có ý định share cho mọi người sử dụng. Nhưng thời gian mình có hạn nên sẽ cập nhật từ từ những lúc mình rãnh.

Nếu có lỗi gì liên quan đến dịch thuật các bạn có thể liên hệ với mình để mình cập nhật bản mod này hoàn thiện hơn.
## Tiến trình dịch
Xem tiến trình dịch và cập nhật mới nhất tại [TIENTRINH.md](TIENTRINH.md)
## Hướng dẫn
### Cài đặt trò chơi

Cài đặt trò chơi Surviving Mars và chạy thử trước khi cài mod

Đề nghị mua trò chơi để ủng hộ nhà sản xuất.

### Phiên bản yêu cầu: v.1001514

Mình dịch trên phiên bản v.1001514 nên có thể không chạy hoặc có lỗi trên phiên bản khác

### Cài đặt mod

- Tải tất cả thư mục [Vietnamese](Vietnamese/) trong này
- Copy và dán vào thư mục **AppData\Roaming\Surviving Mars\Mods**
- Nếu không có thư mục **Mods** thì tạo thư mục **Mods** và dán thư mục **Vietnamese** vào
- Khởi động game vào **PARADOX MOD MANAGER** -> **Installed Mods**
- Bật mod **Vietnamese**

### Tìm thư mục AppData

- Ấn phím window hoặc tổ hợp phím Ctrl + ESC
- Nhập `%AppData%` rồi ấn phím Enter trên bàn phím
### Hướng dẫn dịch

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
- Có một số định nghĩa trong văn bản giữ 2 đấu ```<``` và ```>``` bạn nên để nguyên vì trò chơi sẽ thay thế nó bằng một **giá trị** khác
- Nếu trong văn bản dịch của bạn cần chèn dấu nháy đôi ```"``` thì bạn nhập 2 dấu nháy đôi liền kề nhau ```""```

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

## Liên lạc và ủng hộ
Ủng hộ tại: [Playerduo](https://playerduo.com/cackehoa)

Fanpage: [fb](https://www.facebook.com/cackehoa)

Discord: [Discord](https://discord.gg/Z5C98FG)

Youtube: [Cắc kè hoa](https://www.youtube.com/c/Cắckèhoa)
## Giấy phép
[MIT](LICENSE)
