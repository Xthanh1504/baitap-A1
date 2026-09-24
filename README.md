# LAB A1 - LÀM QUEN ANDROID STUDIO & THEO DÕI VÒNG ĐỜI ACTIVITY

## 1. Thông tin sinh viên
- Họ và tên: Trần Phạm Xuân Thành
- MSSV: 231A010584
- Môn học: Lập trình trên các thiết bị di động
- Lab: A1
- Ngôn ngữ: Java + XML
- Android Studio: Android Studio Quail 3 | 2026.1.3]
- Thiết bị: Pixel 7
- Android: Android 17 - API 37
## 2. Mục tiêu

Sau khi hoàn thành Lab A1:

- Cài đặt và cấu hình Android Studio, Android SDK.
- Chạy ứng dụng trên máy ảo AVD.
- Tạo project Android bằng Java + XML Layout.
- Ghi log bằng Log.d và theo dõi bằng Logcat.
- Quan sát 7 callback vòng đời Activity:
  - onCreate()
  - onStart()
  - onResume()
  - onPause()
  - onStop()
  - onRestart()
  - onDestroy()
- Đọc lỗi crash NullPointerException trong Logcat.
- ## 3. Checkpoint 1

Ứng dụng đã chạy thành công trên máy ảo Pixel 7.
 em quên chụp cái "hello word" rồi ạ huhu
## 4. Checkpoint 2

Sau khi mở ứng dụng lần đầu, Logcat ghi nhận đúng thứ tự vòng đời:

```text
onCreate (savedInstanceState = null)
onStart
onResume
