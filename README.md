# Fullstack JS Roadmap

Roadmap học full-stack JavaScript (Node/NestJS + Next.js) chuẩn bị apply intern.

## Bắt đầu từ đâu

1. Đọc [RULES.md](./RULES.md) — quy tắc bắt buộc trong suốt quá trình học.
2. Mở issue phase đang học (bắt đầu từ Phase 0) — trong đó có lịch chi tiết
   từng ngày, nguồn học và acceptance criteria.
3. Mỗi issue con là một bước công việc, làm tuần tự theo bảng lịch trong issue
   phase. Khi tự thấy đã xong một bước, **comment vào issue con kèm bằng chứng**
   (link PR, output chạy thật, giải thích bằng lời) — mentor review rồi mới tick.
   Không tự tick, và không tick nếu chỉ "xem hiểu".
4. Kẹt ở đâu: tự mò tối đa 30 phút, sau đó hỏi kèm đủ 3 ý — đã thử gì,
   expected gì, actual ra gì.

## Code làm ra để ở đâu

Repo này **không chứa code bài làm** — chỉ dùng để xem lịch và comment nộp
bằng chứng vào issues.

- **Bài tập nhỏ** (đoạn code ngắn, câu trả lời, số liệu đo): comment thẳng
  vào issue con tương ứng.
- **Project**: làm trên repo riêng thuộc tài khoản GitHub của người học —
  Phase 0 dùng repo Pokemon game có sẵn; Phase 1–4 mỗi phase tạo 1 repo mới
  (todo-api, blog-api, blog-frontend, product-catalog). Portfolio khi apply
  intern chính là các repo này.
- **PR template**: repo project mới thì copy `templates/pull_request_template.md`
  của repo này vào `.github/pull_request_template.md` ngay từ bước đầu.
- **Quy trình git**: Phase 0 phần bài tập nhỏ (Ngày 1–10) commit thẳng lên
  main, tập viết commit message rõ nghĩa. **Từ dự án refactor game (Ngày 11)
  trở đi**, mỗi đơn vị công việc làm trên 1 branch riêng
  (vd `refactor/1-esm`, `feat/jwt-auth`) và mở Pull Request — mentor review
  trên PR, được duyệt rồi mới merge.
- **Nộp bài**: khi đạt điều kiện của issue con, comment vào issue đó kèm
  link repo / commit / PR cụ thể — mentor review rồi mới tick.

## Các phase

| Phase | Nội dung | Issue |
|---|---|---|
| Phase 0 | Nền JS vững chắc | [#1](../../issues/1) |
| Phase 1 | Node.js & Express — Todo API | [#2](../../issues/2) |
| Phase 2 | Database + NestJS — Blog API có phân quyền | [#3](../../issues/3) |
| Phase 3 | React + Next.js — Blog Frontend | [#4](../../issues/4) |
| Phase 4 | Dự án tổng hợp + intern prep — Product Catalog | [#5](../../issues/5) |

Danh sách đầy đủ điều kiện từng phase: xem [Issues](../../issues), lọc theo
label `phase-0` → `phase-4`.
