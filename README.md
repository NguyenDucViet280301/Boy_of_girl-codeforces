Ngày đó, nhiều chàng trai dùng ảnh của các cô gái xinh đẹp làm ảnh đại diện trên diễn đàn. Vì vậy, khá khó để biết giới tính của người dùng ngay từ cái nhìn đầu tiên. Năm ngoái, anh hùng của chúng ta đã vào một diễn đàn và trò chuyện vui vẻ với một người đẹp (anh ấy nghĩ vậy). Sau đó, họ nói chuyện rất thường xuyên và cuối cùng họ trở thành một cặp đôi trong mạng lưới.

Nhưng hôm qua, anh ấy đã đến gặp "cô ấy" ngoài đời thực và phát hiện ra "cô ấy" thực ra là một người đàn ông rất mạnh mẽ! Anh hùng của chúng ta rất buồn và anh ấy quá mệt mỏi để yêu lại lần nữa. Vì vậy, anh ấy đã nghĩ ra một cách để nhận dạng giới tính của người dùng theo tên người dùng của họ.

Đây là phương pháp của anh ấy: nếu số ký tự riêng biệt trong tên người dùng của một người là lẻ, thì anh ấy là nam, nếu không thì cô ấy là nữ. Bạn được cung cấp chuỗi ký tự biểu thị tên người dùng, vui lòng giúp anh hùng của chúng tôi xác định giới tính của người dùng này theo phương pháp của anh ấy.

Đầu vào:

Dòng đầu tiên chứa một chuỗi không rỗng, chỉ chứa các chữ cái tiếng Anh thường — tên người dùng. Chuỗi này chứa tối đa 100 chữ cái.

Đầu ra:

Nếu theo phương pháp của anh hùng của chúng ta là một phụ nữ, hãy in " CHAT WITH HER! " (không có dấu ngoặc kép), nếu không, hãy in " IGNORE HIM! " (không có dấu ngoặc kép).

Giải quyết:

Dùng phép toán "chuỗi ký tự" % 2 == 0

    Nếu == 0 là số chẵn
    Nếu != 0 là số lẻ
