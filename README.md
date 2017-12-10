# JavaScript
### Sự khác nhau giữa null và undefined?

- **Undefined**:
  - Undefined tạm hiểu là không xác định. Nếu khai báo một biến nhưng chưa gán giá trị cho nó thì giá trị của biến đó sẽ là `undefined `.
  - Nếu thiết lập 1 biến với giá trị là `undefined` thì biến đó cũng sẽ trở thành `undefined`.

- **Null**:
  - Null có nghĩa là rỗng hoặc một giá trị không tồn tại.
  - 1 biến có thể khai báo với giá trị `null`, và nó có nghĩa là không có gì cả.

----------

### Use Strict là gì? Điểm mạnh và hạn chế khi sử dụng nó?
- **Use Stricht là gì**:
  - Use strict là từ khóa khai báo sử dụng chế độ Strict Mode, nếu bạn muốn sử dụng chế độ Strict Mode ở đâu thì chỉ việc đặt từ khóa "use strict" ở đó.
  - Chế độ Strict Mode có hai phạm vi sử dụng đó là toàn cục và cục bộ.
    - Tính toàn cục tức là khi bạn đặt từ `use strict` ở ngoài hàm và nằm phía trên cùng của file thì lúc này tất cả các đoạn code bên dưới đều bị ảnh hưởng.
    - Tính cục bộ tức là bạn đặt `use strict` nằm trong một hàm nào đó thì phạm vi ảnh hưởng chỉ nằm trong hàm đó mà thôi.
- **Điểm mạnh và hạn chế khi sử dụng nó**
  - Điểm mạnh:
    - Tạo ra một chuẩn code nghiêm ngặt cho javascript.
  - Hạn chế: 
    - Không thể sử dụng một biến mà không khai báo.
    - Các tham số của một hàm không được phép trùng nhau.
    - Không sử dụng được cách viết số thuộc hệ bát phân với tiền tố  là 0.

----------

### So sánh == và ===
- Toán tử  === chỉ trả về  `true` nếu như cả hai bên đều cùng một loại và có cùng giá trị. Nếu so sánh khác loại, kết quả sẽ trả về  `false`.
  - Vd: "0" === 0 sẽ trả về kết quả là `false`.
- Toán tử  == sẽ chuyển đổi kiểu của toán hạng nếu như hai toán hạng có kiểu khác nhau, và chỉ bắt đầu so sánh sự bằng nhau khi đã thực hiện đổi kiểu xong.
 - Vd: "0" === 0 sẽ trả về kết quả là `true`.

----------

### So sánh sự khác nhau giữa các cách khai báo var, const và let
- var: có phạm vi sử dụng ở trong hàm.
- const và let:
  - có phạm vi sử dụng trong block scope.
  - const chỉ nhận giá trị khi khai báo lần đầu tiên, không thay đổi giá trị cho các lần sau.
  - let có thể thay đổi giá trị.
