# Mô hình máy cắt vải tự động

## 1. Giới thiệu đề tài

Mô hình máy cắt vải tự động là dự án ứng dụng kiến thức cơ điện tử nhằm mô phỏng quá trình cấp vải và thực hiện thao tác cắt vải tự động. Hệ thống sử dụng vi điều khiển Arduino Nano để xử lý tín hiệu, điều khiển các cơ cấu chấp hành và phối hợp hoạt động giữa các bộ phận.

Đề tài hướng đến việc xây dựng một mô hình có kết cấu nhỏ gọn, chi phí hợp lý và dễ dàng thử nghiệm, qua đó tìm hiểu nguyên lý hoạt động của máy cắt vải trong thực tế.

## 2. Mục tiêu dự án

- Thiết kế và lắp ráp mô hình máy cắt vải ở quy mô nhỏ.
- Ứng dụng Arduino Nano trong điều khiển hệ thống.
- Tìm hiểu cách sử dụng cảm biến và cơ cấu chấp hành.
- Mô phỏng quá trình cấp vải, định vị và thực hiện thao tác cắt.
- Kiểm tra khả năng hoạt động và đánh giá độ ổn định của mô hình.

## 3. Nguyên lý hoạt động dự kiến

Hệ thống được điều khiển bởi Arduino Nano. Khi nhận lệnh khởi động, bộ điều khiển xử lý tín hiệu đầu vào và điều khiển các cơ cấu tương ứng để thực hiện trình tự hoạt động của máy.

Quá trình vận hành dự kiến gồm các bước:
1. Khởi động hệ thống.
2. Cấp và đưa vải đến vị trí cần cắt.
3. Xác định vị trí hoặc chiều dài cắt theo thiết kế.
4. Kích hoạt cơ cấu cắt.
5. Hoàn thành chu trình và chờ lệnh tiếp theo.

Trình tự hoạt động cụ thể sẽ được điều chỉnh theo cấu hình phần cứng và chương trình điều khiển thực tế.

## 4. Phần cứng dự kiến

- **Arduino Nano V3.0:** Bộ điều khiển trung tâm.
- **Cảm biến:** Phát hiện vị trí hoặc trạng thái của hệ thống.
- **Động cơ kéo vải:** Hỗ trợ di chuyển vải.
- **Cơ cấu chấp hành dao cắt:** Thực hiện thao tác cắt theo thiết kế.
- **Mạch điều khiển động cơ:** Kết nối và điều khiển động cơ.
- **LCD và nút nhấn:** Hiển thị thông tin, lựa chọn hoặc điều chỉnh chế độ nếu được tích hợp.
- **Khung mô hình và bộ phận cơ khí:** Lắp đặt, dẫn hướng và cố định các thành phần.

Danh sách linh kiện và thông số kỹ thuật sẽ được cập nhật khi hoàn thiện thiết kế.

## 5. Công nghệ sử dụng

- Vi điều khiển Arduino Nano.
- Arduino IDE và ngôn ngữ lập trình C/C++.
- Cảm biến và mạch điều khiển động cơ.
- Thiết kế, lắp ráp cơ khí và tích hợp hệ thống cơ điện tử.

## 6. Tiến độ thực hiện

- [x] Tìm hiểu ý tưởng và xác định hướng phát triển mô hình.
- [ ] Hoàn thiện thiết kế phần cứng.
- [ ] Lắp ráp và đấu nối linh kiện.
- [ ] Xây dựng chương trình điều khiển.
- [ ] Kiểm tra và hiệu chỉnh hoạt động.
- [ ] Hoàn thiện báo cáo và đánh giá kết quả.

## 7. Cấu trúc repository

- `firmware/`: Chương trình điều khiển Arduino.
- `hardware/`: Danh sách linh kiện và sơ đồ đấu nối.
- `docs/`: Tài liệu thiết kế và báo cáo dự án.
- `images/`: Hình ảnh mô hình và quá trình thử nghiệm.

## 8. Định hướng phát triển

Trong các giai đoạn tiếp theo, dự án hướng đến việc cải thiện độ chính xác khi cấp vải, nâng cao độ ổn định của cơ cấu cắt, bổ sung chức năng điều chỉnh chiều dài cắt và tăng cường các tính năng an toàn.

## 9. Tác giả

Dự án học tập thuộc lĩnh vực Cơ điện tử, tập trung vào thiết kế cơ khí, điều khiển tự động và lập trình vi điều khiển.
