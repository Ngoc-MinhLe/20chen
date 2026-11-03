# Chia tiền cuộc nhậu

Site tĩnh để ghi nhận nhiều bữa ăn trong ngày, chia đều hóa đơn, theo dõi người đã thanh toán và xem lịch sử.

## Deploy trên Vercel

Import repository này vào Vercel. `vercel.json` đã cấu hình thư mục output là `dist`, nên không cần build command.

## Firebase

Ứng dụng dùng Firebase project `along-6e1ce` và Firestore collection `meals`. Hãy kiểm tra Firestore Rules trước khi dùng chung; Firebase Web config trong frontend không phải secret, nhưng quyền đọc/ghi phải được giới hạn bằng Rules hoặc Authentication.
