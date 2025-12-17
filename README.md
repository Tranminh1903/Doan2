#Tên sản phẩm 

Doan2 - Defense Tower game thủ thành – Team 3 người

## Yêu cầu môi trường
- Unity: 6.3 LTS (6000.3.1f1)
- IDE: Visual Studio 2022
- Git LFS: quan trọng
- OS: Windows 10/11

##Setup nhanh
Git clone repo về: git clone https://github.com/Tranminh1903/Doan2.git

Tải git lfs: git lfs install

Chuyển nhanh làm việc: git checkout develop

## Cấu trúc file
Doan2/
 ├── Assets/Project
 │   ├── Art/        (Sprite, UI, Animation)
 │   ├── Audio/      (Nhạc, hiệu ứng âm thanh)
 │   ├── Prefabs/    (Player, Enemy, UI, Item)
 │   ├── Scenes/     (Main.unity)
 │   ├── Scripts/    (Code C#)
 │   └── UI/         (Canvas, UI Prefab)
 ├── Packages/
 └── ProjectSettings/

## Quy trình làm việc Git
main : nhánh release (chỉ merge khi có 1 cập nhật lớn)
develop : nhánh tích hợp chung
develop/_tênthànhviên : nhánh làm tính năng riêng

| Prefix   | Ý nghĩa           |
| -------- | ----------------- |
| feat     | Thêm tính năng    |
| fix      | Sửa lỗi           |
| chore    | Việc lặt vặt      |
| refactor | Tối ưu / dọn code |


## Quy ước làm việc khi commit
### Những thứ KHÔNG được commit
Library/
Temp/
Build/
Logs/

### Những thứ được commit
Assets/
Packages/
ProjectSettings/
File .meta

### Ngoài ra 
Asset (ảnh, âm thanh)
Bắt buộc dùng Git LFS
Không commit asset nặng nếu chưa track LFS

Scene & Prefab
Scene chính (Main.unity) chỉ do 1 người phụ trách
Các thành viên khác:
Làm việc qua Prefab
Không chỉnh trực tiếp Scene chính


