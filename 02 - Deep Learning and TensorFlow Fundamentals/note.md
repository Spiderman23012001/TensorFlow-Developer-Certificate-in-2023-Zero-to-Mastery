## Shuffle the order of element:
<br>--> Được sử dụng trong quá trình chuẩn bị dữ liệu huấn luyện trong machine learning để tạo ra các batch (nhóm) dữ liệu ngẫu nhiên từ tập dữ liệu huấn luyện. Việc này giúp mô hình học được từ các mẫu dữ liệu có tính ngẫu nhiên hơn và tránh hiện tượng mô hình học "đọc thuộc lòng" dữ liệu.

__________
<pre>
import numpy as np

# Tạo một tensor 2D (ma trận) làm ví dụ
tensor = np.array([[1, 2, 3],
                   [4, 5, 6],
                   [7, 8, 9]])

# Xáo trộn thứ tự của các hàng (axis=0)
np.random.shuffle(tensor)

print(tensor)

</pre>