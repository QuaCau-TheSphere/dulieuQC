Mô tả:: Thao tác được tốt Obsidian
# Mức độ thành thạo
# Thử thách
- [ ] Cài plugin
- [ ] Dùng template
- [ ] [[Dùng phím tắt]]
- [ ] Đọc [[Triết lý của Obsidian]]
- [ ] Mở dòng lệnh
- [ ] Lưu chuyển dữ liệu
- [ ] Đồng bộ với điện thoại: Syncthing
# Khu trưng bày
# Tài liệu

# Người chơi
```dataview
list
From "8 Tổ chức/82 Thành viên (Người chơi)"
where contains(kỹ-năng, [[]])
```

# Thử thách ở Quả Cầu
```dataview 
List
from "7 Công việc"
Where contains(kỹ-năng, [[]])
```

> [!info]- Chi tiết
> ```dataview
> table 
> 	trạng-thái as "Trạng thái", 
> 	filter(file.inlinks, (i) => i.hoạt-động) as "Thành quả cần có",
> 	người-chơi as "Người chơi"
> from "7 Công việc"
> Where contains(kỹ-năng, [[]])
> ```
