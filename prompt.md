## Prompt 1 - Thiết lập bối cảnh dự án
```text
Đóng vai Senior Business Analyst và Solution Architect có hơn 15 năm kinh nghiệm trong lĩnh vực Hotel Management System.

Hãy xây dựng bối cảnh nghiệp vụ cho hệ thống Quản lý Khách sạn & Resort.

Yêu cầu:

- Mô tả mục tiêu hệ thống.
- Xác định phạm vi dự án.
- Xác định ít nhất 4 Actor.
- Xác định ít nhất 5 Module chính.
- Liệt kê chức năng của từng Module.

Trình bày theo chuẩn Software Requirement Specification (SRS).
```

---

## Prompt 2 - Phân tích Actor và User Story

```text
Tiếp tục.

Dựa trên bối cảnh ở trên hãy phân tích Actors và User Stories.

Yêu cầu:

Mỗi Actor phải có:
- Vai trò
- Quyền hạn
- Mục tiêu

Viết User Story theo mẫu:

As a...
I want...
So that...

Mỗi User Story cần có Acceptance Criteria.
```

---

## Prompt 3 - Functional Requirements

```text
Tiếp tục.

Phân tích toàn bộ Functional Requirements.

Trình bày theo chuẩn:

FR-01
FR-02
FR-03
...

Mỗi Functional Requirement gồm:

- Description
- Input
- Output
- Business Logic
- Validation Rules
- Exception Handling
```

---

## Prompt 4 - Non Functional Requirements

```text
Tiếp tục.

Phân tích Non Functional Requirements.

Bao gồm:

- Performance
- Security
- Availability
- Scalability
- Reliability
- Maintainability
- Logging
- Monitoring
- Backup
- Disaster Recovery
- Responsive UI
```

---

## Prompt 5 - Use Case Diagram

```text
Tiếp tục.

Thiết kế Use Case Diagram bằng Mermaid.

Actors gồm:

- Customer
- Receptionist
- Manager
- Admin

Sơ đồ phải đúng cú pháp Mermaid.
```

---

## Prompt 6 - Hoàn thiện Use Case

```text
Use Case Diagram còn đơn giản.

Hãy bổ sung thêm các chức năng:

- Booking Room
- Check-in
- Check-out
- Payment
- Invoice
- Discount
- Room Service
- Customer Management
- Employee Management
- Room Management
- Revenue Report
- Dashboard
- Manage Promotion

Sau đó sinh lại Mermaid hoàn chỉnh.
```

---

## Prompt 7 - Activity Diagram

```text
Tiếp tục.

Thiết kế Activity Diagram bằng Mermaid.

Quy trình:

Customer Booking Room

Bao gồm:

- Search Room
- Select Room
- Check Availability
- Booking
- Payment
- Confirmation
- Cancel Booking
- Refund
```

---

## Prompt 8 - Sequence Diagram

```text
Tiếp tục.

Thiết kế Sequence Diagram bằng Mermaid.

Quy trình Booking Room.

Các thành phần:

- Customer
- Web UI
- Booking Service
- Payment Service
- Notification Service
- Database
```

---

## Prompt 9 - ERD

```text
Tiếp tục.

Thiết kế ERD bằng Mermaid.

Ít nhất gồm các bảng:

Customer

Employee

Room

RoomType

Booking

BookingDetail

Payment

Invoice

Service

BookingService

Promotion

Discount

Role

UserAccount

Quan hệ phải đúng chuẩn:

1-1

1-N

N-N

Có đầy đủ Primary Key và Foreign Key.
```

---

## Prompt 10 - Hoàn thiện ERD

```text
ERD hiện tại còn thiếu.

Hãy bổ sung:

Room Status

Booking Status

Payment Status

Invoice Status

Promotion Status

CreatedDate

UpdatedDate

CreatedBy

UpdatedBy

DeletedFlag

Audit Fields

Soft Delete

Timestamp

Sau đó sinh lại Mermaid hoàn chỉnh.
```

---

## Prompt 11 - Data Dictionary

```text
Tiếp tục.

Viết Data Dictionary cho toàn bộ Database.

Bao gồm:

- Table Name
- Column Name
- Data Type
- Length
- Nullable
- Primary Key
- Foreign Key
- Description
```

---

## Prompt 12 - Business Rules

```text
Tiếp tục.

Viết ít nhất 25 Business Rules.

Đánh số:

BR-01
BR-02
...
BR-25

Business Rules phải phản ánh đúng nghiệp vụ quản lý khách sạn.
```

---

## Prompt 13 - Exception Cases

```text
Tiếp tục.

Viết Exception Cases.

Bao gồm:

- Booking Failure
- Payment Failure
- Room Not Available
- Duplicate Booking
- Invalid Customer
- Invalid Payment
- Expired Promotion
- Invalid Check-in
- Invalid Check-out
- System Error
- Database Error
- Network Error
```

---

## Prompt 14 - Test Scenarios

```text
Tiếp tục.

Viết Test Scenarios.

Bao gồm:

- Happy Path
- Negative Test
- Boundary Value Test
- Validation Test
- Security Test
- Performance Test
- Concurrency Test
```

---

## Prompt 15 - Rà soát và hoàn thiện SRS

```text
Cuối cùng.

Kiểm tra toàn bộ tài liệu SRS.

Đánh giá:

- Thiếu Actor nào không.
- Thiếu Module nào không.
- Thiếu Business Rule nào không.
- Thiếu Functional Requirement nào không.
- Thiếu Non Functional Requirement nào không.
- Có lỗi logic hay không.
- Có lỗi quan hệ Database hay không.
- Có lỗi Use Case hay không.
- Có lỗi Activity Diagram hay không.
- Có lỗi Sequence Diagram hay không.
- Có lỗi ERD hay không.

Nếu còn thiếu hãy tự động bổ sung.

Sau đó xuất toàn bộ tài liệu theo chuẩn IEEE 830 Software Requirement Specification với bố cục đầy đủ gồm:

1. Introduction
2. Business Overview
3. Scope
4. Stakeholders
5. Actors
6. Modules
7. User Stories
8. Functional Requirements
9. Non Functional Requirements
10. Business Rules
11. Use Case Diagram
12. Activity Diagram
13. Sequence Diagram
14. ERD
15. Data Dictionary
16. Exception Cases
17. Test Scenarios
18. Assumptions
19. Constraints
20. Future Enhancements

Đảm bảo tài liệu có chất lượng Production Ready và có thể sử dụng trực tiếp làm tài liệu SRS cho dự án thực tế.
```
