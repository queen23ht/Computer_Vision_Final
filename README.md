# Dự án Phân Tích Dữ Liệu Sản Phẩm Thời Trang

Dự án này tập trung vào việc phân tích và xử lý dữ liệu sản phẩm từ các thương hiệu thời trang Adidas, Uniqlo và Yame.

## Cấu trúc thư mục

```
.
├── archive/                    # Thư mục chứa dữ liệu
│   ├── adidas_final/          # Dữ liệu Adidas
│   ├── uniqlo_final/          # Dữ liệu Uniqlo
│   └── yame_final/            # Dữ liệu Yame
├── manage.ipynb               # File chính xử lý dữ liệu
├── manage_ML.ipynb           # File xử lý Machine Learning
├── manage_move.ipynb         # File xử lý di chuyển dữ liệu
├── direction.ipynb           # File phân tích hướng
├── eda.ipynb                 # File phân tích dữ liệu khám phá
├── edaMANAGE.ipynb          # File phân tích dữ liệu quản lý
├── crawladd.ipynb           # File crawl dữ liệu
└── MANAGE.csv               # File CSV chứa dữ liệu tổng hợp
```

## Cài đặt

1. Clone repository này về máy local của bạn
2. Cài đặt các thư viện cần thiết:
```bash
pip install -r requirements.txt
```

## Sử dụng

1. Chạy file `manage.ipynb` để xử lý dữ liệu cơ bản
2. Sử dụng `manage_ML.ipynb` để thực hiện các phân tích Machine Learning
3. File `eda.ipynb` và `edaMANAGE.ipynb` để thực hiện phân tích dữ liệu khám phá
4. File `direction.ipynb` để phân tích hướng dữ liệu
5. File `crawladd.ipynb` để crawl thêm dữ liệu mới

## Dữ liệu

Dữ liệu được lưu trữ trong thư mục `archive/` với cấu trúc:
- Mỗi thương hiệu có một thư mục riêng
- Dữ liệu được phân loại theo loại sản phẩm (áo/quần)
- File CSV chứa thông tin chi tiết về sản phẩm

## Yêu cầu hệ thống

- Python 3.7+
- Jupyter Notebook
- Các thư viện được liệt kê trong file requirements.txt 