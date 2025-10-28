# cake-sale-website-main  
Đồ án website bán bánh – **BA & Tester**

---

## Giới thiệu  

**Cake Website** là đồ án mô phỏng **hệ thống quản lý và bán hàng trực tuyến cho tiệm bánh**, được xây dựng với mục tiêu **thực hành quy trình phát triển và kiểm thử phần mềm (Software Testing Life Cycle – STLC)**.  

### Hệ thống cho phép:
- Người dùng duyệt và đặt mua bánh trực tuyến  
- Quản lý đơn hàng, khuyến mãi, và tồn kho  
- Quản trị viên quản lý sản phẩm, khách hàng và phân quyền người dùng  

### Dự án được chia thành hai phần chính:
1. **Phần phát triển (Cake-Website):** Chứa mã nguồn website (frontend + backend).  
2. **Phần kiểm thử (CakeShop_Dev_BA_Tester):** Chứa toàn bộ tài liệu kiểm thử do nhóm **BA & Tester** thực hiện.  

---

## Cấu trúc thư mục chính  
CakeShop_Dev_BA_Tester/
│
├── 1. NhapHang/ # Kiểm thử chức năng nhập hàng
│ ├── Test case nhập hàng
│ ├── Báo cáo lỗi liên quan đến nhập hàng
│ └── Kịch bản kiểm thử
│
├── 2. MuaHang/ # Kiểm thử chức năng mua hàng
│ ├── Test case mua hàng
│ ├── Báo cáo lỗi liên quan đến mua hàng
│ └── Kịch bản kiểm thử
│
├── Cake-Website/ # Source code chính của website
│
├── 1. UnitTesting.xlsx # Kiểm thử đơn vị (Unit Test)
├── 2. TestPlanChecklist (HopTrang).xlsx
├── 3. TestPlanChecklist (HopDen).xlsx
├── 4. TestCase and TestReport.xlsx
├── 5. Q&A.xlsx
├── 6. DefectList.xlsx
│
├── BaoCao(VN).pdf # Báo cáo tiếng Việt
├── BaoCao(UK).pdf # Báo cáo tiếng Anh
│
├── SoDoPhanQuyen.drawio # Sơ đồ phân quyền người dùng
├── SoDoTrienKhai.drawio # Sơ đồ triển khai hệ thống
└── UseCase.drawio # Sơ đồ Use Case của hệ thống

