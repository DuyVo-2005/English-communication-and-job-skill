# Chapter 2.1 - Scanning network 

associating services v: liên kết dịch vụ

banner n: biểu ngữ (thông báo hoặc thông tin hiển thị khi truy cập vào một hệ thống hoặc dịch vụ mạng)

Banner grabbing (OS fingerprinting) n: thu thập thông tin banner (gửi các yêu cầu đơn giản và phân tích các phản hồi: phiên bản phần mềm, hệ điều hành và các thông tin cấu hình,...gồm 2 loại active: kẻ tấn công gửi các gói tin đến các cổng mở trên hệ thống mục tiêu để thu thập thông tin về dịch vụ đang chạy trên các cổng đó. Điều này có thể bao gồm thông tin về phiên bản của dịch vụ, hệ điều hành; passive: kẻ tấn công không gửi gói tin đến hệ thống mục tiêu mà chỉ lắng nghe và thu thập các gói tin mà hệ thống tự động gửi ra. Điều này có thể bao gồm các banner hoặc thông báo từ các dịch vụ mà hệ thống đang chạy, mà không cần phải gây ra sự can thiệp)

evade a traceback v: tránh bị truy vết, tránh để lại dấu vết hoặc ngăn chặn việc tạo ra traceback

calibrate (fireware rule) v: hiệu chỉnh

evasion Technique n: công nghệ lãng tránh

exploit v: khai thác

IDS - Intrusion Detection System n: Hệ thống Phát hiện Xâm nhập (gồm Network-based IDS (NIDS), Host-based IDS (HIDS))

IPS (Intrusion Prevention System): Hệ thống ngăn chặn xâm nhập. (Đây là một hệ thống an ninh mạng được thiết kế để phát hiện và ngăn chặn các hoạt động độc hại bằng cách giám sát lưu lượng mạng và chặn các cuộc tấn công tiềm ẩn)

locate active device v: xác định vị trí thiết bị đang hoạt động

mechanism n: cơ chế

misguide['mis'gaid] v: làm cho lạc đường, làm lạc lối

scanning methodology n: phương pháp luận quét

Scanning beyond IDS v: "quét mạng vượt qua IDS" hoặc "quét mạng vượt qua hệ thống phát hiện lỗ hổng".

Scan detect v: quét phát hiện

scanning pen testing n: Kiểm tra thử xâm nhập

Source routing là một phương pháp trong mạng máy tính cho phép người gửi của gói tin xác định đường đi mà gói tin sẽ đi qua trên mạng thay vì để các router trung gian tự quyết định (Strict Source Routing: Người gửi chỉ định một danh sách cụ thể các địa chỉ mà gói tin phải đi qua theo thứ tự, Loose Source Routing: Người gửi chỉ định một danh sách các địa chỉ mà gói tin phải đi qua, nhưng không bắt buộc phải theo thứ tự cụ thể và có thể đi qua các điểm khác)

spoof ip address v: giả mạo địa chỉ IP

penetration testing n: kiểm tra xâm nhập

poses v: đưa ra, phô ra

Proxies n: máy chủ trung gian hoặc phần mềm trung gian (chuyển tiếp các yêu cầu từ máy khách tới máy chủ đích và ngược lại - Forward Proxy [loại proxy mà máy khách sử dụng để truy cập internet], Reverse Proxy [loại proxy mà máy chủ đích sử dụng để xử lý các yêu cầu từ máy khách], Anonymous Proxy[ẩn địa chỉ IP thực của họ khi truy cập internet], Transparent Proxy [Không ẩn địa chỉ IP thực của người dùng và không thay đổi nội dung của các yêu cầu]

proxies sever n: máy chủ proxy (hoạt động như một trung gian giữa máy tính của bạn và internet giúp cải thiện bảo mật, tăng cường quyền riêng tư và có thể hỗ trợ trong việc kiểm soát và giám sát lưu lượng truy cập mạng)

simulate v: mô phỏng

spyware n: phần mềm gián điệp (là một loại phần mềm độc hại được cài đặt trên thiết bị của bạn mà không có sự cho phép của bạn. Nó có thể theo dõi hoạt động của bạn, thu thập thông tin cá nhân và gửi thông tin này đến các bên thứ ba)

tear it down v: "phá hủy" hoặc "tháo dỡ"

Trojan horses n: "ngựa Trojan" hoặc "phần mềm Trojan" (là một loại phần mềm độc hại giả dạng phần mềm hợp pháp để lừa người dùng cài đặt nó. Khi được cài đặt, nó có thể thực hiện nhiều hành động gây hại như đánh cắp dữ liệu, giám sát hoạt động, và tạo cửa hậu để kẻ tấn công có thể truy cập vào hệ thống)


# Chapter 2.2 - Operating system security

encompass[ɪnˈkʌmpəs] v: vây quanh, bao quanh

maintain v: bảo trì

measure in place n: "biện pháp được thực hiện" hoặc "biện pháp đã được triển khai".

utility[juːˈtɪləti] n: tiện ích

kernel n: nhân

patching n: "vá lỗi" hoặc "sửa chữa".

Whitelisting n: quá trình xác định và cấp phép cho một tập hợp các thực thể được tin tưởng và cho phép thực hiện một số hành động cụ thể trong hệ thống hoặc mạng (ip, user, email, ứng dụng có tên trong danh sách mới được truy cập vào mạng hoặc hệ thống)
