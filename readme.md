 51 changes: 51 additions & 0 deletions51  
readme.md
@@ -0,0 +1,51 @@
1 - Dars
1. Ma'lumotlarni kirgizishlik va chiqarishlik
input and output
input
prompt
output
alert
confirm
2. Malumotlarni js orqali dacumentga qo'shishlik
a = prompt ("ismingizni kiriting");
console.log(window);
text=window.document.getElementById("id nomi");
//text.innerHTML="<i>nimadur</i>";
//text.inneText="nimadur....";
text.textContent = a + " nimadur ";
consile.log(text);

3. Consol turlari
console.worn("..."); -> qandaydur hatolik haqida ogohlantimoqchi bo'lsak.
console.error("....."); -> hatolik haqida ogohlantirishlik bermoqchi b'lsak.
consile.din("..."); -> to'grida to'gri yozgan malumotimizni chiqarishlik uchun.
console.table("..."); ->jadval ko'rinishida chiqarberadi malumotlarimizni.
4. Syntax and comments
comeents ( // and / * .... * / )
statement and semicolon ;
Block { }
Experssion 4+6
White spaces (space, new line , tab )
5. O'zgaruvchilar
var
let
const
6. Data tayp
Data tayip js da 8 ta turi mavjud , ular o'zi 2turga bo'linadi primotive va no primotive

primotive

number
string
boolean
undefined
null
nigInt
symbol
no primotive

Object
7. O'zgaruvchi nomlash usullari
camel case -> myName
Pascal case -> MyName
snace case -> my_name