# LumiZ — bản phát hành

Kho này chỉ chứa **tệp cài** của LumiZ, không chứa mã nguồn. Mã nguồn ở
`Lumisoft-art/LumiZ-App`; mỗi lượt đóng gói đẩy tệp sang đây qua GitHub Releases.

Vì sao tách ra: hạn mức artifact của tổ chức ở gói miễn phí là 500MB, mà một lượt dựng
bốn hệ ra khoảng 840MB. Tệp đính vào một Release thì không tính vào hạn mức đó.

## Cách đọc các bản ở đây

| Loại bản | Thẻ | Chữ ký | Tự cập nhật |
|---|---|---|---|
| Bản phát hành | `v0.1.1` | Có (Authenticode / notarize) | Có — kèm `latest.yml` và `release-manifest.json` đã ký |
| Bản thử | `test-12` | Không, tên tệp có hậu tố `-unsigned` | Không |

Bản thử là để kiểm tra tính năng trên máy nội bộ. Windows sẽ cảnh báo lúc cài vì tệp
không có chữ ký số.

Kho ở chế độ công khai để ứng dụng tải bản cập nhật **không cần token**: một tệp cài
không bao giờ nên mang theo khoá truy cập nào.
