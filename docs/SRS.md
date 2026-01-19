# Đặc tả yêu cầu phần mềm (Software Requirements Specification)

## 1. Danh sách User Stories (Product Backlog)

### Epic: Quản lý Lịch học (Smart Schedule)
| ID | User Story | Priority |
| :--- | :--- | :--- |
| **SCH-01** | Là học sinh, tôi muốn nhập lịch học cố định ở trường để hệ thống tránh xếp lịch tự học vào giờ đó. | High |
| **SCH-02** | Là người dùng, tôi muốn hệ thống tự động đề xuất khung giờ ôn tập vào các khoảng thời gian rảnh. | High |

### Epic: Hỗ trợ tập trung (Focus Assistant)
| ID | User Story | Priority |
| :--- | :--- | :--- |
| **FOC-01** | Là người dùng, tôi muốn tùy chỉnh thời gian tập trung (25p, 50p) để phù hợp với từng môn học. | Medium |

## 2. Tiêu chí chấp nhận (Acceptance Criteria) 
**Tính năng: Nhập lịch cố định (SCH-01)**
* [ ] Người dùng có thể chọn thứ trong tuần, giờ bắt đầu và giờ kết thúc.
* [ ] Hệ thống phải báo lỗi nếu giờ kết thúc nhỏ hơn giờ bắt đầu.
* [ ] Lịch mới nhập không được trùng với các lịch đã có sẵn.

## 3. Yêu cầu phi chức năng (Non-functional Requirements)
* **Performance:** Trang web phải tải dưới 2 giây trên mạng 4G.
* **UI/UX:** Giao diện tương thích (Responsive) với cả Mobile và Desktop.
