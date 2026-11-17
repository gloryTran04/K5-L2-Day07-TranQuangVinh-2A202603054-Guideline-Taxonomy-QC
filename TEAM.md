# Thông tin nhóm

- Tên nhóm: K5-L2-Day07-TranQuangVinh
- Mã thành viên: 101, 102
- Người điều phối: Trần Quang Vinh (101)
- Người review bản cuối: Phạm Công Bằng (102)
- Commit chốt bài (điền ở kênh nộp sau khi commit):

## Kết quả tóm tắt

- Pilot hay cả bộ 40 ảnh: Pilot 12 ảnh
- Lượt gán hoàn tất / được giao: 24/24
- IAA trước calibration (kèm mẫu số):47 cặp box ghép được, IoU trung bình 0.842, đồng thuận lớp 97.9%.
- Vòng QC và số ảnh đã duyệt / cả lô:duyệt 12/12 ảnh, 0 ảnh lỗi, quyết định Release.
- Quyết định và lý do: Release lô pilot 12 ảnh. QC duyệt đủ 12/12 ảnh: 0/12 ảnh có lỗi (0%, đạt ngưỡng ≤ 2% trong taxonomy), 0/84 box đối tượng sai, 0 vật bỏ sót. Nhãn cuối không còn box nào gắn `can_review`, và đã có `batch_manifest.json` kèm checksum. IAA trước calibration IoU trung bình 0.842 trên 47 cặp box ghép, nhưng cả 93 ca lệch đã được chốt trong `calibration_decisions.csv` và sửa vào `labels_calibrated.json` trước khi QC. Phạm vi: chỉ dùng cho 12 ảnh pilot, chưa đại diện cho cả bộ 40 ảnh.
