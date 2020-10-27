# Bắt đầu với OpenCore

## Những thứ cần chuẩn bị
  
1. Thời gian và kiên nhẫn.
   * Đừng cài hackintosh khi đang có deadlines hoặc việc quan trọng cần làm. Hackintosh không thể là dùng như máy chính để làm việc.
2. _**[Quan trọng]**_ **Hiểu phần cứng của bạn**
   * Tên CPU và thế hệ
   * GPUs (Card đồ hoạ)
   * Thiết bị lưu trữ (HDD/SSD, cấu hình NVMe/AHCI/RAID/IDE)
   * Tên model của laptop/desktop(máy bàn). Ví dụ, lap của mình là Dell 5548. 
   * Cổng **Ethernet chipset**
   * WLAN/Bluetooth chipset. Ví dụ: Card WiFi Laptop DW1820A
3. _**[Quan trọng]**_ **Hiểu biết cơ bản về COMMAND LINES và cách dùng TERMINAL/COMMAND PROMPT**
   * Đây là điều kiện cần. Phải biết rõ lệnh `cd` là dùng để duyệt vào thư mục hay là xoá một file,..
4. _**[Quan trọng]**_ Một máy tính có phần cứng tương thích. Xem thêm ở mục _**Compatibility**_.
   * [Hardware Limitations page](macos-limits.md)
5. _**[Quan trọng]**_ Yêu cầu tối thiểu:
   * 12GB USB nếu dùng macOS để tạo USB cài đặt.
   * 4GB USB nếu dùng Windows hoặc Linux để tạo USB cài đặt.
   * Cá nhân mình thấy nên mua luôn USB 32GB để dành xài. Cỡ 150k trên Shopee.
6. _**[Quan trọng]**_ Một **kết nối Ethernet**
   * Bạn phải có một cổng Ethernet. Trong trường hợp, bạn có một [compatible WiFi card](https://dortania.github.io/Wireless-Buyers-Guide/), có thể dùng nó.
     * Đa số Wifi cards không được hỗ trợ bởi macOS
   * Với những ai không có cổng ethernet nhưng có điện thoại Android, bạn có thể kết nối Android phone với WiFi và sau đó tether it qua cổng USB với phần mềm [HoRNDIS](https://joshuawise.com/horndis#available_versions).
7. _**[Quan trọng]**_ **Proper OS Installation:**
   * Có một thiết bị đang dùng:
     * macOS (bảng càng mới càng tốt)
     * Windows (Windows 10, 1703 hoặc mới hơn)
     * Linux (cài sẵn Python 2.7 hoặc mới hơn)
   * Dành cho người dùng Windows hoặc Linux, ổ cứng còn trống **15GB**. Trên Windows, ổ đĩa hệ điều hành (C:) phải có ít nhất 15GB.
   * Đối với người dùng macOS, ổ đĩa hệ thống còn trống **30GB**.
   * Hầu hết những công cụ được dùng trong hướng dẫn này cần [Python installed](https://www.python.org/downloads/)
