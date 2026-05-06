  ---

  🛒 ###E-commerce Consumer Behavior Analysis & BI Solution
  (Phân tích hành vi người tiêu dùng & Giải pháp Business Intelligence)

  ---

  🇺🇸 English Version

  📌 Project Overview
  This project provides a comprehensive Business Intelligence (BI) solution for analyzing E-commerce consumer behavior. By leveraging the Microsoft BI Stack and Data
  Mining techniques, the project transforms raw data into actionable insights, helping businesses understand customer segments, purchase intent, and satisfaction    
  levels.

  🛠 Tech Stack
   * ETL (Extract, Transform, Load): SQL Server Integration Services (SSIS)
   * Data Warehouse & OLAP: SQL Server Analysis Services (SSAS) - Multidimensional Cube
   * Query Language: SQL, MDX (Multi-Dimensional Expressions)
   * Data Mining: Python (K-Means Clustering, Decision Tree)
   * Visualization: Power BI, Microsoft Excel

  📂 Key Components (from Report)
   1. Data Integration: Cleaning and migrating raw CSV data into a structured SQL Server Data Warehouse using SSIS.
   2. OLAP Modeling: Designing a Star Schema with dimensions (Customer, Time, Location, Channel, Behavior) and Fact tables.
   3. Advanced Analytics: Using MDX for complex queries like Drill-down, Roll-up, and Slice & Dice to analyze trends.
   4. Customer Insights: Utilizing K-Means for segmentation and Decision Trees to predict spending levels.

  ---

  🇻🇳 Tiếng Việt

  📌 Tổng quan dự án
  Dự án này cung cấp một giải pháp Business Intelligence (BI) toàn diện để phân tích hành vi người tiêu dùng thương mại điện tử. Bằng cách kết hợp bộ công cụ
  Microsoft BI và các kỹ thuật Khai thác dữ liệu (Data Mining), dự án chuyển đổi dữ liệu thô thành các thông tin có giá trị, giúp doanh nghiệp hiểu rõ về phân khúc
  khách hàng, ý định mua hàng và mức độ hài lòng.

  🛠 Công nghệ sử dụng
   * ETL (Trích xuất, Biến đổi, Nạp): SSIS
   * Kho dữ liệu & OLAP: SSAS (Mô hình đa chiều - Cube)
   * Ngôn ngữ truy vấn: SQL, MDX
   * Khai thác dữ liệu: Python (Phân cụm K-Means, Cây quyết định Decision Tree)
   * Trực quan hóa: Power BI, Microsoft Excel

  📂 Nội dung chính (Từ báo cáo)
   1. Tích hợp dữ liệu: Làm sạch và chuyển đổi dữ liệu từ file CSV vào SQL Server thông qua SSIS.
   2. Mô hình hóa OLAP: Thiết kế sơ đồ hình sao (Star Schema) với các chiều (Khách hàng, Thời gian, Vị trí, Kênh mua sắm) và bảng Fact.
   3. Truy vấn nâng cao: Sử dụng MDX để thực hiện các thao tác khoan sâu (Drill-down), cuộn lên (Roll-up) và cắt lát dữ liệu.
   4. Phân tích thông minh: Ứng dụng K-Means để phân cụm khách hàng và Decision Tree để dự báo mức chi tiêu.

  ---

  🚀 Installation & Setup (Hướng dẫn cài đặt)

  1. Prerequisites (Yêu cầu hệ thống)
   * SQL Server (Standard or Enterprise edition)
   * SQL Server Analysis Services (SSAS)
   * SQL Server Integration Services (SSIS)
   * Visual Studio with BI Data Tools (SSDT)
   * Python 3.x (for Data Mining)

  2. Database Setup (Cài đặt Database)
   1. Open SQL Server Management Studio (SSMS).
   2. Attach the database files (doan_Olap.mdf) located in the Database/ folder.
      (Attach file .mdf trong thư mục Database vào SQL Server).

  3. ETL Process (Chạy SSIS)
   1. Open the solution file in Source/doan_Olap_ssis/.
   2. Update the Connection Manager to point to your local SQL Server instance and the raw CSV file in the data/ folder.
   3. Run the package to load data.
      (Cập nhật Connection Manager trỏ về server local và chạy package để nạp dữ liệu).

  4. OLAP Cube (Triển khai SSAS)
   1. Open the solution in Source/doan_Olap_ssas/.
   2. Update the Data Source connection string.
   3. Right-click on the project and select Deploy.
      (Cập nhật Data Source và Deploy dự án lên SSAS).

  5. Data Mining (Chạy Python)
   1. Navigate to Source/Data_mining/.
   2. Install dependencies: pip install pandas scikit-learn matplotlib.
   3. Run the Jupyter Notebooks (KMeasn.ipynb, Decision_Tree.ipynb).

  ---

  📊 Sample Visuals
   * MDX Reports: Located in Source/Code_MDX/.
   * Power BI Dashboard: Open Source/Power_BI/Report_Power_BI.pbix.
   * Excel Report: Check Source/Excel/Report_excel.xlsx.

  👥 Authors (Sinh viên thực hiện)
   * Phạm Hùng Quốc Việt (23521783)
   * Cam Hồng Mạnh (23520914)

  ---
