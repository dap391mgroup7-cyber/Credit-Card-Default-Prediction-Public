# 💳 Dự đoán Vỡ nợ Thẻ tín dụng (UCI-350)

## 📌 Tổng quan dự án
Dự án này tập trung vào việc dự đoán khả năng vỡ nợ của khách hàng trong tháng tiếp theo dựa trên dữ liệu lịch sử thanh toán tại Đài Loan. 

**Mục tiêu chính:** 
- Xây dựng mô hình phân loại (LogReg & SVC).
- Xử lý vấn đề dữ liệu mất cân bằng (Class Imbalance).
- Tối ưu hóa các chỉ số thực chiến như PR-AUC và Precision@k.

## 📊 Research Questions
1. Imbalance ảnh hưởng thế nào đến ROC-AUC vs PR-AUC?
2. Class-weight trong LogReg/SVC có cải thiện recall@k không?
3. SVC có vượt LogReg ở vùng top-risk không?

## 🛠 Công nghệ sử dụng
- Ngôn ngữ: Python
- Thư viện: Pandas, Scikit-learn, Matplotlib, Seaborn
- Báo cáo: LaTeX (Overleaf)
