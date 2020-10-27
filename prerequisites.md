# Bắt đầu với OpenCore

## Những thứ cần chuẩn bị
  
1. _**[CRUCIAL]**_ Thời gian và kiên nhẫn.
   * Đừng cài hackintosh khi đang có deadlines hoặc việc quan trọng cần làm. Hackintosh không thể là máy chính dùng để làm việc.
2. _**[CRUCIAL]**_ **Hiểu phần cứng của bạn**
   * Tên CPU và thế hệ
   * GPUs (Card đồ hoạ)
   * Thiết bị lưu trữ (HDD/SSD, cấu hình NVMe/AHCI/RAID/IDE)
   * Tên model của laptop/desktop(máy bàn). Ví dụ, lap của mình là Dell 5548. 
   * Cổng **Ethernet chipset**
   * WLAN/Bluetooth chipset. Ví dụ: Card WiFi Laptop DW1820A
3. _**[CRUCIAL]**_ **Hiểu biết cơ bản về COMMAND LINES và cách dùng TERMINAL/COMMAND PROMPT**
   * Đây là điều kiện cần. Chúng tôi không thể giúp nếu bạn không biết lệnh `cd` để vào thư mục hoặc xoá một file.
4. _**[CRUCIAL]**_ Một máy tính có phần cứng tương thích. Xem thêm ở mục _**Compatibility**_.
   * [Hardware Limitations page](macos-limits.md)
5. _**[CRUCIAL]**_ Yêu cầu tối thiểu:
   * 12GB USB nếu dùng macOS để tạo USB cài đặt.
   * 4GB USB nếu dùng Windows hoặc Linux để tạo USB cài đặt.
   * Cá nhân mình thấy nên mua luôn USB 32GB để dành xài. Cỡ 150k trên Shopee.
6. _**[CRUCIAL]**_ Một **kết nối Ethernet**
   * Bạn phải có một cổng Ethernet. Trong trường hợp, bạn có một [compatible WiFi card](https://dortania.github.io/Wireless-Buyers-Guide/), có thể dùng nó.
     * Note the majority of Wifi cards are not supported by macOS
   * For people who can't use ethernet but have an Android phone, you can connect your Android phone to WiFi and then tether it using USB with [HoRNDIS](https://joshuawise.com/horndis#available_versions).
7. _**[CRUCIAL]**_ **Proper OS Installation:**
   * Có một thiết bị đang dùng:
     * macOS (bảng càng mới càng tốt)
     * Windows (Windows 10, 1703 hoặc mới hơn)
     * Linux (cài sẵn Python 2.7 hoặc mới hơn)
   * For Windows or Linux users, **15GB** of free space on the drive you're working on. On Windows, your OS disk (C:) must have 15GB free at least.
   * For macOS users, **30GB** of free space on the system's drive.
   * Most tools used in this guide will also require [Python installed](https://www.python.org/downloads/)
