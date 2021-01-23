# AssemblyPractice
 Learn assembly by some simple fucntion
 
Ở 2 hệ điều hành khác nhau mình sử dụng 2 phiên bản asm khác nhau:
- linux dùng nasm
- windows dùng masm

Nasm sử dụng là raw asm code, cho nên lượng macro là không có.
Còn Masm hỗ trợ tương đối lớn macro, sử dụng khá thuận tiện, cho nên trong quá trình nghiên cứu, mình cũng sử dụng một số ít hàm để tối giản bớt code.
Nguyên lý hoạt động của 2 compiler, linker nó cũng hơi khác một tí. Tuy nhiên cũng không gây cản trở nhiều. 
Đối với MASM, ai có kinh nghiệm về ASM trước rồi có thể tìm thư mục help trong thư mục cài đặt của nó để xem, nó có chứa những hướng dẫn cặn kẽ làm quen với MASM32. 
 
Trong thư mục windows ASM, có một file là compile.bat, file này là file hỗ trợ compile đối với MASM32, vì quá trình gõ lệnh của MASM32 khá dài dòng, cách sử dụng là :

```
compile.bat <tên file> <option>  
- với tên file không có .asm nha
- option: r = run: tức là compile xong run luôn file exe, d = debug: tức là không run file, cho mục đích kiểm tra tính đúng sai của code hoặc debug file tạo ra. 
``` 
