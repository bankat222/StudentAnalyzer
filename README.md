# Student Analyzer – Unit Test with JUnit

## Mô tả
Chương trình Java phân tích điểm số sinh viên, bao gồm:
- Đếm số học sinh đạt loại Giỏi (>= 8.0)
- Tính điểm trung bình của các điểm hợp lệ (0–10)

Các điểm không hợp lệ (<0 hoặc >10) sẽ bị bỏ qua.

## Công nghệ sử dụng
- Java
- JUnit 5

## Cách chạy kiểm thử
1. Mở project 
2. Đảm bảo JUnit 5 đã được thêm vào project
3. Chạy file `StudentAnalyzerTest.java`
4. Kiểm tra kết quả test pass

## Các chức năng
- `countExcellentStudents(List<Double>)`
- `calculateValidAverage(List<Double>)`
