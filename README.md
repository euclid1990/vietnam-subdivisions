# Phân cấp hành chính Việt Nam

## Cấu trúc thư mục

- `provinces.json`: Thông tin về toàn bộ tỉnh, thành phố
  - `provices`: Thư mục chứa các tỉnh, thành phố
    - `VN{LocationID}`: Dữ liệu các quận, huyện của tỉnh, thành phố
      - `districts.json`: Thông tin về toàn bộ quận, huyện, thị xã trực thuộc tỉnh, thành phố
        - `VN{LocationID}`: Dữ liệu các xã, phường của quận, huyện
          - `towns.json`: Thông tin về toàn bộ xã, phường của quận, huyện

- Sử dụng {LocationID} trong các file `.json` để lấy thông tin từ cấp cao tới cấp thấp dễ dàng :laughing:

## Nguồn dữ liệu

- Internet :joy:
