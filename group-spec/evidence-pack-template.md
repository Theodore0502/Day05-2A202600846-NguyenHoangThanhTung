# Evidence Pack

## 1. Nhóm và Track

**Tên nhóm:** Nhóm 09

**Track:** Travel & Hospitality

**Product/App đã chọn:** Vinpearl / Sun World

**Build Slice đang nghĩ:**

AI Hotel Matcher – Hỗ trợ khách du lịch lựa chọn khách sạn phù hợp.

---

## 2. Self-use Evidence

| Observation                                            | Screenshot/Link | Path liên quan | Điều học được                   |
| ------------------------------------------------------ | --------------- | -------------- | ------------------------------- |
| Có rất nhiều lựa chọn khách sạn trong cùng một khu vực | Observation     | Happy          | User có nhiều lựa chọn          |
| Khó biết khách sạn nào phù hợp nhu cầu                 | Observation     | Low-Confidence | User thiếu hỗ trợ ra quyết định |
| User không biết sự khác biệt giữa các loại phòng       | Observation     | Failure        | Thiếu thông tin so sánh         |
| User phải tự tìm hiểu lại sau khi xem gợi ý            | Observation     | Correction     | Chưa có hỗ trợ cá nhân hóa      |

---

## 3. User / Review / Social Evidence

| Quote / Review / Observation            | Nguồn       | User là ai?          | Pain / Failure Mode  |
| --------------------------------------- | ----------- | -------------------- | -------------------- |
| "Không biết nên ở resort nào"           | Observation | Khách du lịch tự túc | Decision Fatigue     |
| "Có quá nhiều lựa chọn"                 | Observation | Khách mới            | Information Overload |
| "Không biết phòng nào phù hợp gia đình" | Observation | Khách gia đình       | Thiếu cá nhân hóa    |

---

## 4. Competitor / Analog Evidence

| App     | Họ xử lý thế nào?      | Pattern học được       | Có áp dụng được không? |
| ------- | ---------------------- | ---------------------- | ---------------------- |
| Booking | Filter theo nhu cầu    | Preference Collection  | Có                     |
| Agoda   | Gợi ý theo ngân sách   | Budget Matching        | Có                     |
| Airbnb  | Hiển thị lý do đề xuất | Explain Recommendation | Có                     |

---

## 5. Evidence → Insight

### Evidence nổi bật nhất

Người dùng không thiếu thông tin khách sạn.

Người dùng thiếu khả năng đánh giá khách sạn nào phù hợp nhất với nhu cầu cá nhân.

### Insight

Khách du lịch không chỉ cần danh sách khách sạn.

Họ cần hỗ trợ ra quyết định.

### Opportunity

Dùng AI để gợi ý khách sạn phù hợp dựa trên:

* Ngân sách
* Số người
* Mục đích chuyến đi
* Sở thích

---

## 6. Evidence đổi SPEC như thế nào?

### Trước Evidence

Nhóm định làm:

AI Concierge hỗ trợ toàn bộ chuyến đi.

### Sau Evidence

Nhóm đổi thành:

AI Hotel Matcher tập trung vào một nhiệm vụ duy nhất:

Hỗ trợ lựa chọn nơi lưu trú phù hợp.

### Lý do

* Scope nhỏ hơn
* Dễ build trong 1 ngày
* Có AI decision rõ ràng
* Có failure path dễ kiểm thử
