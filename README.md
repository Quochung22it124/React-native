# 📸 Camera Notes App (React Native + Expo)

## 🧩 Giới thiệu
Ứng dụng **Camera Notes** cho phép người dùng **chụp ảnh, thêm ghi chú (caption)** và **lưu trữ ảnh cục bộ** bằng AsyncStorage.  
Đây là bài thực hành cơ bản về **Expo Camera, FileSystem, và AsyncStorage** dành cho sinh viên CNTT năm 3.

---

## 🚀 Tính năng chính
✅ Xin quyền sử dụng camera  
✅ Chụp ảnh và xem lại ảnh  
✅ Nhập caption (ghi chú) cho ảnh  
✅ Lưu thông tin `{path, caption}` vào AsyncStorage  
✅ Hiển thị danh sách ảnh + caption bằng FlatList  

---

## 💡 Mở rộng (gợi ý)
- Sửa hoặc xoá caption
- Lưu ảnh vào MediaLibrary
- Chia sẻ ảnh qua ứng dụng khác (sử dụng `expo-sharing`)

---

## ⚙️ Cài đặt
```bash
# Tạo project mới
npx create-expo-app camera-notes
cd camera-notes

# Cài các package cần thiết
npx expo install expo-camera expo-media-library expo-file-system
npm install @react-native-async-storage/async-storage
