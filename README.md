# Week-8-Thiết kế đèn giao thông

## 1 Mô hình mạch dãy - mạch điều khiển đèn giao thông 

Hướng ưu tiên (cao tốc) xanh trong thời gian T, sau đó​:
- Nếu không có ô tô xuất hiện ở hướng không ưu tiên, hướng ưu tiên tiếp tục chu kỳ xanh mới​
- Nếu có ô tô ở hướng không ưu tiên, hướng ưu tiên chuyển sang vàng trong thời gian t, sau đó:  ​
    - Hướng ưu tiên chuyển sang đỏ, hướng không ưu tiên xanh trong thời gian T, sau đó​:
      - Hướng không ưu tiên chuyển sang vàng trong thời gian t và chuyển sang đỏ, hướng ưu tiên chuyển sang xanh​

Các Khối
- Khối sensor: phát hiện ô tô ở hướng không ưu tiên​
- Khối timer: đếm thời gian​
- Khối highway_controller điều khiển đèn hướng ưu tiên​
- Khối countryroad_controller: điều khiển đèn hướng không ưu tiên​

### Mô hình mạch dãy
![Screenshot 2024-04-21 185920](https://github.com/HoangHuyHust12/Week-8-Thi-t-k-s-/assets/142207226/125af6b9-edd5-49c7-90f2-a309b211bb50)

### Bộ điều khiển hướng ưu tiên
![Screenshot 2024-04-21 191907](https://github.com/HoangHuyHust12/Week-8-Thi-t-k-s-/assets/142207226/9951f9db-1146-482c-913c-525eeffd53d8)
