


# CSE392 – Nhóm 10 | Hệ thống quản lý giao hàng
Tên thành viên :
1.Nguyễn Duy Kiên
2.Vũ Lê Hoàng 
3.Hoàng Lã Gia Huy
4.Nguyễn Gia Tăng

> **Tài liệu giới thiệu dự án, phân công 4 thành viên và theo dõi công việc.**  
> Repository: https://github.com/Duy-Kien1706/CSE392-Nhom10-TLU

## 1. Giới thiệu dự án

Dự án mẫu xây dựng **hệ thống quản lý giao hàng** với 4 tác nhân: **khách gửi hàng, người nhận hàng, tài xế và quản trị viên**. Hệ thống dự kiến hỗ trợ tạo đơn, quản lý và phân công giao hàng, theo dõi trạng thái, quản lý tài khoản và thông báo tiến độ.


## 2. Thành viên và vai trò

**Cần thay tên và tài khoản mẫu bằng thông tin thật của nhóm trước khi nộp.** Đây là phân công đề xuất, chưa phải Assignees đã được gán trên GitHub.

| Thành viên | GitHub | Vai trò chính | Công việc phụ trách |
|---|---|---|---|
| **TV1** | `Nguyễn Duy Kiên` | Trưởng nhóm / Phân tích / Kiểm thử | Phân tích yêu cầu, Use Case, ERD, kế hoạch, tài liệu, kiểm thử tổng thể |
| **TV2** | `Hoàng Lã Gia Huy` | UI/UX & Frontend/Mobile | Thiết kế Figma, giao diện người gửi, người nhận, tài xế, quản trị và tích hợp API |
| **TV3** | `Vũ Lê Hoàng` | Backend – Xác thực & Đơn hàng | Database người dùng, đăng ký/đăng nhập, JWT, phân quyền, API quản lý đơn |
| **TV4** | `Nguyễn Gia Tăng` | Backend – Vận hành & Tích hợp | API phân công tài xế, cập nhật trạng thái, tính phí, thông báo, kiểm thử API |

## 3. Công việc cụ thể theo thành viên

### Nguyễn Duy Kiên – Phân tích hệ thống, điều phối và kiểm thử
- [ ] Xác định yêu cầu của khách gửi, người nhận, tài xế và quản trị viên.
- [ ] Lập danh sách chức năng, vẽ sơ đồ Use Case tổng quát và chi tiết.
- [ ] Xác định thực thể, thuộc tính, quan hệ và vẽ sơ đồ ERD.
- [ ] Viết tài liệu mô tả nghiệp vụ, tiêu chí chấp nhận.
- [ ] Tạo/làm rõ Issues, gán nhiệm vụ và theo dõi Master Plan.
- [ ] Lập kịch bản kiểm thử đăng nhập, tạo đơn, phân công và giao hàng.
- [ ] Tổng hợp kết quả kiểm thử, lỗi và tài liệu báo cáo.

**Sản phẩm bàn giao:** Use Case, ERD, tài liệu yêu cầu, kế hoạch, báo cáo kiểm thử.

### Hoàng Lã Gia Huy – Thiết kế giao diện và frontend
- [ ] Thiết kế màn hình đăng ký/đăng nhập trên Figma.
- [ ] Thiết kế màn hình tạo đơn và theo dõi đơn hàng.
- [ ] Thiết kế danh sách đơn, chi tiết đơn và lịch sử cho tài xế.
- [ ] Thiết kế Dashboard quản trị, màn hình quản lý người dùng, đơn hàng, tài xế.
- [ ] Hiện thực các màn hình và luồng điều hướng.
- [ ] Kết nối các màn hình với API, xử lý thông báo lỗi.
- [ ] Kiểm thử giao diện trên màn hình điện thoại và máy tính.

**Sản phẩm bàn giao:** Link Figma, mã nguồn giao diện, ảnh minh họa hoạt động.

### Vũ Lê Hoàng – Backend xác thực và đơn hàng
- [ ] Thiết kế bảng Users, Roles, Orders và dữ liệu liên quan.
- [ ] Xây dựng API đăng ký, đăng nhập và lấy thông tin tài khoản.
- [ ] Triển khai JWT (hoặc phương thức xác thực đã thống nhất) và phân quyền.
- [ ] Xây dựng API tạo, liệt kê, xem chi tiết, cập nhật, hủy đơn hàng.
- [ ] Kiểm tra dữ liệu đầu vào, quyền truy cập và xử lý lỗi.
- [ ] Kiểm thử bằng Postman và ghi tài liệu endpoint.

**Sản phẩm bàn giao:** API xác thực, API quản lý đơn và bộ kiểm thử Postman.

### Nguyễn Gia Tăng – Backend giao vận, tích hợp và yêu cầu phát sinh
- [ ] Xây dựng API danh sách tài xế và phân công đơn.
- [ ] Kiểm tra khả năng nhận đơn của tài xế, tránh phân công không hợp lệ.
- [ ] Xây dựng API cập nhật trạng thái: chờ nhận, đang giao, thành công/thất bại.
- [ ] Xác định công thức và xây dựng API tính phí vận chuyển theo khoảng cách.
- [ ] Bổ sung thông báo cho người dùng khi đơn hàng đổi trạng thái.
- [ ] Kiểm thử các API bằng Postman và phối hợp tích hợp với frontend.
- [ ] Ghi nhận yêu cầu phát sinh, lỗi và cách khắc phục.

**Sản phẩm bàn giao:** API vận hành, chức năng thông báo, kết quả kiểm thử tích hợp.

## 4. Phân công GitHub Issues

### Các Issue đã có khi soạn README

| Issue | Nội dung | Người phụ trách đề xuất |
|---|---|---|
| [#2](https://github.com/Duy-Kien1706/CSE392-Nhom10-TLU/issues/2) | Phân tích yêu cầu hệ thống | TV1 |
| [#3](https://github.com/Duy-Kien1706/CSE392-Nhom10-TLU/issues/3) | Thiết kế giao diện ứng dụng | TV2 |
| [#4](https://github.com/Duy-Kien1706/CSE392-Nhom10-TLU/issues/4) | Xây dựng API đăng nhập | TV3 |
| [#5](https://github.com/Duy-Kien1706/CSE392-Nhom10-TLU/issues/5) | Bổ sung thông báo trạng thái đơn hàng | TV4 |

### Các Issue đề xuất tạo thêm

| Tiêu đề Issue | Phụ trách | Label | Milestone |
|---|---|---|---|
| `[Task] Xây dựng API quản lý đơn hàng` | TV3 | `module:backend` | M3 |
| `[Task] Thiết kế giao diện quản trị viên` | TV2 | `module:mobile` | M2 |
| `[Task] Xây dựng API phân công tài xế` | TV4 | `module:backend` | M3 |
| `[Task] Xây dựng giao diện theo dõi đơn hàng` | TV2 | `module:mobile` | M3 |
| `[Task] Bổ sung chức năng tính phí vận chuyển` | TV4 | `change-request` | M3 |
| `[Task] Kiểm thử và hoàn thiện hệ thống` | TV1 | `change-request` | M4 |

**Lưu ý:** Những Issue đề xuất chưa được tạo tự động; cần tạo tại tab **Issues**, gán Assignee và thêm vào Project.

## 5. Quy ước Labels và Milestones

### Labels

| Label | Mục đích |
|---|---|
| `module:mobile` | Giao diện ứng dụng và frontend |
| `module:backend` | Cơ sở dữ liệu, API và xử lý máy chủ |
| `change-request` | Yêu cầu phát sinh, bổ sung hoặc thay đổi |

### Milestones

| Milestone | Nội dung | Sản phẩm |
|---|---|---|
| **M1 – Planning** | Phân tích yêu cầu, lập kế hoạch | Use Case, ERD, WBS |
| **M2 – Design** | Thiết kế giao diện, giải pháp | Figma, thiết kế chi tiết |
| **M3 – Development** | Lập trình, tích hợp | Chức năng giao diện và API |
| **M4 – Testing** | Kiểm thử, sửa lỗi, hoàn thiện | Test case, báo cáo, bản hoàn thiện |

Các cột mốc cần được tạo trong **Issues → Milestones**; ghi trong README không tự tạo chúng.

## 6. Quản lý trên GitHub Projects

### Master Plan (Table)

Thêm các cột: `Title`, `Status`, `Assignees`, `Labels`, `Milestone`, `Start Date`, `Target Date`. Điền ngày và người phụ trách cho từng nhiệm vụ theo lịch nhóm.

### Kanban (Board)

- **Todo:** chờ thực hiện.
- **In Progress:** đang thực hiện.
- **In Review:** chờ kiểm tra/duyệt code.
- **Done:** hoàn thành và được xác nhận.

Kéo các Issue giữa các cột theo tình trạng **thực tế**, không đánh dấu hoàn thành khi chưa nghiệm thu.

## 7. Quy trình làm việc nhóm

1. Trưởng nhóm tạo Issue theo mẫu `[Task] Tên nhiệm vụ`, mô tả rõ yêu cầu và checklist `- [ ]`.
2. Gắn **Assignee**, **Label**, **Milestone**, **Project**, `Start Date`, `Target Date`.
3. Thành viên nhận việc chuyển Issue sang **In Progress** và tạo nhánh: `feature/<issue-number>-<short-name>`.
4. Commit các thay đổi với nội dung rõ ràng, mở Pull Request và liên kết Issue (ví dụ `Closes #4` khi phù hợp).
5. Thành viên khác kiểm tra mã nguồn, kiểm thử, yêu cầu sửa nếu cần.
6. Sau khi đạt yêu cầu, merge PR, tích checklist, đóng Issue và cập nhật trạng thái **Done**.

## 8. Danh sách kiểm tra trước khi nộp bài

- [ ] README có tên và tài khoản GitHub thực tế của 4 thành viên.
- [ ] Mỗi Issue có tiêu đề chuẩn, checklist, người phụ trách, Label và Milestone.
- [ ] Repository có 3 Labels và 4 Milestones.
- [ ] Project có bảng Master Plan, `Start Date` và `Target Date`.
- [ ] Kanban có 4 trạng thái: Todo, In Progress, In Review, Done.
- [ ] Các sản phẩm đầu ra (file thiết kế, code, báo cáo) được liên kết vào Issues/PR.

---


