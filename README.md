# Datascience

Repo này lưu trữ tài liệu, notebook EDA, mã nguồn chính và dữ liệu mẫu để phục vụ các thí nghiệm Data Science.

Cấu trúc thư mục:
- docs/ - Tài liệu
- notebooks/ - Các notebook EDA (Jupyter)
- src/ - Mã nguồn core (module, hàm xử lý dữ liệu, pipeline)
- sample_data/ - Dữ liệu ví dụ (mẫu nhỏ)
- pyproject.toml - Khai báo dependency và metadata
- README.md - Mô tả repo

Hướng dẫn nhanh:
1. Cài đặt môi trường:
   - Python 3.10+ (hoặc theo yêu cầu bạn muốn)
   - Sử dụng venv hoặc conda
   - Cài đặt dependency:
     - pip install -e .
     - Hoặc dùng poetry/pip-tools nếu bạn quản lý môi trường khác
2. Chạy Jupyter Lab để mở notebook:
   - jupyter lab

Các mục tiếp theo mình có thể thêm: notebook mẫu trong notebooks/, file CSV mẫu trong sample_data/, hoặc template mã trong src/.
