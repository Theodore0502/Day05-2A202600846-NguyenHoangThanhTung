# Thin SPEC – Day 05

## 1. Track, Product/App và User

**Track:** B – Travel & Hospitality

**Product/App thật:** Vinpearl / Sun World

**User cụ thể:**

Khách du lịch tự túc lần đầu đến một địa điểm mới và chưa có nhiều thông tin về nơi sẽ đến.

**Nhóm có phải user thật không?**

Có một phần.

Các thành viên trong nhóm đã từng đi du lịch tự túc và gặp khó khăn trong việc lựa chọn nơi lưu trú phù hợp với ngân sách và nhu cầu cá nhân.

---

## 2. Evidence Summary

| Evidence                                                 | Nguồn       | User/Pain nói lên điều gì?                     | SPEC phải đổi gì?               |
| -------------------------------------------------------- | ----------- | ---------------------------------------------- | ------------------------------- |
| Người dùng phải mở nhiều website để so sánh khách sạn    | Observation | Quá nhiều lựa chọn, khó ra quyết định          | AI cần hỗ trợ chọn lọc          |
| Không biết khách sạn nào phù hợp ngân sách               | Observation | User thiếu hỗ trợ ra quyết định                | AI cần cá nhân hóa đề xuất      |
| Không biết khách sạn nào phù hợp kiểu du lịch của mình   | Observation | User không hiểu sự khác nhau giữa các lựa chọn | AI cần giải thích lý do đề xuất |
| Người dùng thường chọn theo cảm tính hoặc review rời rạc | Observation | Dễ đặt nhầm nơi ở                              | AI cần hỗ trợ decision making   |

---

## 3. Pain Statement

Khách du lịch tự túc lần đầu đến một địa điểm mới đang gặp khó khăn trong việc lựa chọn nơi lưu trú,

vì có quá nhiều lựa chọn khách sạn nhưng thiếu thông tin để đánh giá khách sạn nào phù hợp nhất với nhu cầu cá nhân.

Điều này dẫn đến mất nhiều thời gian tìm kiếm, dễ đặt nhầm dịch vụ và ảnh hưởng đến trải nghiệm du lịch.

---

## 4. Build Slice

Cho khách du lịch tự túc đang lên kế hoạch chuyến đi,

prototype sẽ dùng AI để augment quá trình lựa chọn khách sạn,

dựa trên:

* Địa điểm
* Ngân sách
* Số người
* Kiểu du lịch

để tạo ra:

* Top 3 khách sạn phù hợp
* Lý do đề xuất
* Chi phí dự kiến

và xử lý failure mode "thiếu thông tin đầu vào" bằng cách hỏi thêm người dùng.

---

## 5. Auto/Aug Decision

### Chọn

Augmentation

### Lý do

Lựa chọn nơi lưu trú là quyết định cá nhân.

AI chỉ nên đóng vai trò tư vấn và gợi ý.

Người dùng vẫn là người quyết định cuối cùng.

### Human Role

**Decider**

---

## 6. Four Paths

| Path           | Prototype phải thể hiện gì?                              |
| -------------- | -------------------------------------------------------- |
| Happy          | User nhập đầy đủ thông tin, AI đề xuất khách sạn phù hợp |
| Low-Confidence | Thiếu ngân sách hoặc sở thích, AI hỏi thêm               |
| Failure        | AI đề xuất khách sạn không phù hợp nhu cầu               |
| Correction     | User thay đổi tiêu chí, AI cập nhật đề xuất              |

---

## 7. Failure Mode Nguy Hiểm Nhất

Nếu user cung cấp thông tin chưa đầy đủ,

AI có thể đề xuất khách sạn vượt ngân sách hoặc không phù hợp với nhu cầu thực tế.

Hậu quả:

* Mất niềm tin vào hệ thống
* Đề xuất không hữu ích
* Trải nghiệm du lịch kém

Prototype xử lý bằng:

* Ask Again
* Show Options

Ví dụ:

"Ngân sách của bạn là bao nhiêu?"

"Bạn đi nghỉ dưỡng, gia đình hay khám phá?"

**Owner kiểm thử:** Nguyễn Hoàng Thanh Tùng – 2A202600846

---

## 8. Owner Plan

| Thành viên                            | Việc phụ trách      | Bằng chứng trong repo              |
| ------------------------------------- | ------------------- | ---------------------------------- |
| Lê Bá Chiến – 2A202600755             | Research / Evidence | Evidence Pack                      |
| Đàm Mạnh Dũng – 2A202600741           | Prototype / UI      | Prototype demo                     |
| Nguyễn Hoàng Thanh Tùng – 2A202600846 | SPEC / Test / Demo  | Thin SPEC, Test Cases, Demo Script |
