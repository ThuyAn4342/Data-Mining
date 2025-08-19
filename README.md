# Social Media vs Productivity – Data Mining Project

## 1. Giới thiệu
Dự án này thực hiện phân tích và khai phá dữ liệu với chủ đề **Social Media vs Productivity** nhằm tìm hiểu mối quan hệ giữa việc sử dụng mạng xã hội, giấc ngủ, mức độ stress và năng suất làm việc.  
Dữ liệu được xử lý, phân tích và trực quan hóa bằng **Python (Google Colab)**. Ngoài ra, nhóm còn xây dựng báo cáo chi tiết về quy trình khai phá dữ liệu.

## 2. Cấu trúc dự án
- `Social_Media_vs_Productivity.ipynb` → File Google Colab (toàn bộ code phân tích, tiền xử lý, mô hình).  
- `social_media_vs_productivity.csv` → Dữ liệu gốc được sử dụng trong phân tích.  
- `Báo_cáo_Khai_phá_Social_Media_vs_Productivity.pdf` → Báo cáo khai phá dữ liệu (quy trình, kết quả, nhận xét).  

## 3. Công nghệ & Thư viện sử dụng

- **Ngôn ngữ**: Python  
- **Phân tích & Xử lý dữ liệu**:  
  - Pandas, NumPy, SciPy  
  - Scikit-learn (train_test_split, preprocessing, classification, clustering, metrics, pipeline)  
  - Imbalanced-learn (SMOTE)  
  - Mlxtend (association rules)  

- **Trực quan hóa**:  
  - Matplotlib, Seaborn, Graphviz  

- **Khai phá dữ liệu & Mô hình**:  
  - Decision Tree, Naive Bayes, Linear Regression  
  - KMeans, Agglomerative Clustering, PCA  
  - Association Rule Mining  

- **Môi trường phát triển**: Google Colab / Jupyter Notebook

## 4. Các bước thực hiện
4.1. **Tiền xử lý dữ liệu**  
   - Làm sạch dữ liệu (missing values, outliers).  
   - Chuẩn hóa dữ liệu.  

4.2. **Phân tích khám phá (EDA)**  
   - Thống kê mô tả.  
   - Vẽ biểu đồ phân bố, mối quan hệ giữa các biến.  

4.3. **Khai thác dữ liệu**  
   - **Clustering (PCA + KMeans, Agglomerative Clustering)**: nhóm các cá nhân theo hành vi sử dụng mạng xã hội và năng suất.  
   - **Classification (Decision Tree, Naive Bayes)**: dự đoán `days_feeling_burnout_per_month`, `actual_productivity_score`.  
   - **Association Rule Mining (Apriori)**: tìm các luật kết hợp phổ biến giữa các yếu tố (stress, social, sleep, productivity).  
   - **Linear Regression**: xây dựng mô hình hồi quy để phân tích ảnh hưởng của các yếu tố đến năng suất (`actual_productivity_score`).  

4.4. **Đánh giá mô hình**  

    - Triển khai các mô hình và đánh giá, nhận xét trên tập test với các chỉ số đánh giá thích hợp cho từng loại mô hình

4.5. **Báo cáo & Kết luận**  
   - Trình bày quy trình, kết quả trực quan.  
   - Đề xuất gợi ý cải thiện năng suất cá nhân.    

## 5. Cách chạy dự án
1. Clone repo về máy:
   ```bash
   git clone https://github.com/ThuyAn4342/Data-Mining.git
2. Mở file Social_Media_vs_Productivity.ipynb trên Google Colab hoặc Jupyter Notebook.
3. Chạy từng cell để xem kết quả.
## 7. Báo cáo

Chi tiết quy trình và kết quả có thể tham khảo trong file: Báo_cáo_Khai_phá_Social_Media_vs_Productivity.pdf
