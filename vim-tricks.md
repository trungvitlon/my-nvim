### Quit
1. Thoát ra cửa sổ chính: `:q`
2. Thoát và không lưu: `:qa!`
3. Lưu và thoát: `:wq`

### INSERT 
1. Vào chế độ INSERT: `i`
2. Trỏ đến cuối dòng: `A`
3. Thêm dòng trên/dưới: `O` / `o`
4. Xóa từ con trỏ đến hết dòng: `C`
5. Xóa cả dòng: `S`

### COPY - PASTE
1. Copy dòng: `number` + `yy` / `dd` 
2. Copy toàn bộ: `:%y+` / `:%d+`
3. Paste trên/dưới: `P` / `p`

### NAVIGATIONS
1. Giữa các dòng: `h` `j` `k` `l` 
2. Giữa các từ: `w` `b` `e`
3. Giữa các khoảng: `{}`
4. Đầu/cuối trang: `G` / `gg`
5. Giữa các cửa sổ: `C-w` + `w`

### UNDO
1. `u` `C-u`

### MAKE
1. Tạo file: `:e folder/abc.cpp`
2. Tạo folder: `:!mkdir folder`
3. Custom Workplace
    - Mở các cửa số: `:vsplit` / `split`
    - Lưu: `:mksession abc.vim`
    - Mở: `$ ./nvim -S abc.vim`

### TAB
1. Chuyển về tab trước: `Ctrl-6`
2. Tạo tab-bar
    - Mở file: `:tabedit abc.cpp`
    - Di chuyển: `gt` `gT`
    - Mở nhiều: `$ ./nvim -p file1 file2 ...`

### VISUAL 
1. Chọn dòng: `V`
2. Viết trên nhiều dòng
    - Vào VISUAL Block: `C-q`
    - Chọn dòng
    - Vào INSERT: `I`
    - Thoát: `Esc`
