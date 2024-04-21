# Week-8-Thiết kế đèn giao thông

## 1 Mô hình mạch dãy - mạch điều khiển đèn giao thông 

Hướng ưu tiên (cao tốc) xanh trong thời gian T, sau đó​:
- Nếu không có ô tô xuất hiện ở hướng không ưu tiên, hướng ưu tiên tiếp tục chu kỳ xanh mới​
- Nếu có ô tô ở hướng không ưu tiên, hướng ưu tiên chuyển sang vàng trong thời gian t, sau đó ​

Hướng ưu tiên chuyển sang đỏ, hướng không ưu tiên xanh trong thời gian T, sau đó​
- Hướng không ưu tiên chuyển sang vàng trong thời gian t và chuyển sang đỏ, hướng ưu tiên chuyển sang xanh​

Các Khối
- Khối sensor: phát hiện ô tô ở hướng không ưu tiên​
- Khối timer: đếm thời gian​
- Khối highway_controller điều khiển đèn hướng ưu tiên​
- Khối countryroad_controller: điều khiển đèn hướng không ưu tiên​
