# Highlight_row_column_Excel_Add-in
Tô màu hàng cột trong Excel/Highlight row column Excel Add-in
Ctrl+Shift+H: bật hoặc tắt tô sáng.
Ctrl+Shift+J: đổi chế độ, lần lượt là Dòng + Cột → Chỉ dòng → Chỉ cột.
Macro ChonMauToSang: chọn 1 trong 5 màu nhạt.
Macro KhoiDongLai: bật lại nếu add-in ngừng chạy sau một lỗi VBA.
Add-in nhớ các cài đặt này cho lần mở Excel sau.

Cách hoạt động:

Add-in thêm 1 quy tắc định dạng có điều kiện cho dòng và cột của ô đang chọn, đặt ưu tiên cao nhất.
Khi chuyển sheet hoặc lưu file, quy tắc này tự xóa, nên file lưu ra không bị dính màu tô sáng.
Add-in không đụng đến định dạng có sẵn.
Nếu chỉ di chuyển giữa các ô thì file không bị đánh dấu “chưa lưu”.
Sheet đang bị khóa (Protect) thì add-in tự bỏ qua.

Lưu ý quan trọng: Khi add-in đang bật, Ctrl+Z (Undo) sẽ không dùng được, vì mọi macro thay đổi sheet đều làm Excel xóa lịch sử Undo. Lúc cần nhập liệu và hay phải Undo, nhấn Ctrl+Shift+H để tắt tạm.

Nếu dùng Microsoft 365 bản mới, hãy xem trong View có nút Focus Cell không. Đó là tính năng tô sáng dòng và cột có sẵn của Excel và không làm mất Undo, nên có thể không cần đến add-in này.

Ver 2 thêm chức năng đổi màu
Ctrl+Shift+K	Đổi màu (1–5 màu có sẵn, 6 là tự chọn)
