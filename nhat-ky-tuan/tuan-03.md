# Nhật ký tuần 03

> **File ví dụ** — tên và số liệu đều giả. Tuần mới thì copy
> [`_mau-tuan.md`](_mau-tuan.md) thành `tuan-4.md`.
> Tuần này kiểu data: **3D LiDAR**.

**Lead tuần này:** @
**Dữ liệu / task CVAT:** `https://…/tasks/<id>`

## Nhóm trưởng tuần này (chỉ làm 25 ảnh / 1 task)

| Nhóm trưởng | Task | Số ảnh | Ghi chú |
|---|---|---|---|
| @__ | Task A | 25 | Nhóm trưởng Seg, review theo vòng PHuy |
| @__ | Task B | 25 | Nhóm trưởng BBox, review theo vòng Mạnh |

> Nhóm trưởng tuần này chưa chốt — @__ Task A · @__ Task B.

## Thành viên và phân công

| Thành viên | Vị trí | Phân công tuần này |
|---|---|---|
|  | Lead | Chia job, chốt edge case, review xác suất 10% mọi job |
| HHuy | Annotator | 50 ảnh (25+25) — person-bit 16:00, review Cường 20:00 |
| Long | Annotator | 50 ảnh (25+25) — review HHuy, person-bit 16:00/20:00 |
| PHuy | Annotator | 50 ảnh (25+25) — review Mạnh (nhóm trưởng Seg), person-bit 16:00/20:00 |
| Mạnh | **Nhóm trưởng Seg** | 25 ảnh Seg — review PHuy (vòng) |
| Cường | **Nhóm trưởng BBox** | 25 ảnh BBox — review Mạnh (vòng) |

> Review rotation: `HHuy → Long → PHuy → Mạnh → Cường → HHuy` — xem [`phan-cong-review.md`](phan-cong-review.md).

## Công việc

| # | Nội dung công việc | Annotator | Reviewer | Hoàn thành | Ghi chú |
|---|---|---|---|---|---|
| 1 | T2 Nhận Job — Lead chia batch | — | — | ⬜ 0% | 25+25 / người |
| 2 | T3 Gán đợt 1 | @HHuy, @Long, @PHuy, @Mạnh, @Cường | @Long, @PHuy, @Mạnh, @Cường, @HHuy | ⬜ 0% | person-bit `nhat-ky-job/` 16:00/20:00 |
| 3 | T4 Nộp phần đầu + Report | Mỗi người | Mỗi người | ⬜ 0% | review T4 xong trước 21:00 để họp T5 |
| 4 | T5 Mentor Duty 1 — họp online | Lead | — | ⬜ 0% | dùng § Duty 1 trong `tuan-03.md` |
| 5 | T6 Gán đợt 2 | Mỗi người | Mỗi người | ⬜ 0% | 16:00/20:00 |
| 6 | T7 Đóng batch trước 20:00 | Mỗi người | Mỗi người | ⬜ 0% | |
| 7 | CN Mentor Duty 2 — chốt tuần | Lead | — | ⬜ 0% | dùng § Duty 2 trong `tuan-03.md` |

Mức hoàn thành: ✅ xong **và đã qua review** · 🟡 đang làm (ghi %) · ⛔ bị chặn (ghi P-xxx) · ⬜ chưa bắt đầu

## Tổng kết

- Đã gán: _ / 250 ảnh (_%) — 5 người × 50 (nhóm trưởng × 25)
- Qua review lần đầu: _% (trả lại _ ảnh)
- Edge case mới / đã chốt: P-xxx → QĐ-xxx
- Ảnh tệ: _ đề xuất → _ đồng ý bỏ/giữ

## Vướng mắc

- P-xxx nào chưa chốt, job nào dừng, đã hỏi mentor/BTC chưa

## Kế hoạch tuần sau

- Chốt P-xxx, mở lại job bị dừng.
- Kiểu data tuần sau: …
- Nhóm trưởng tuần sau (random T2): Task A: @__ · Task B: @__
- Vòng review: giữ nguyên `HHuy → Long → PHuy → Mạnh → Cường → HHuy`
