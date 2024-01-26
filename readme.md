1 - Array
Array - bir vaqitning o'zida bir nechta qiymatlarni o'zida saqlashi mumkun bo'lgan obect. uni ikki hil ko'rinishda yaratishlik mumkun : 1- ko'rinishii va eng ko'p qo'lanadiga usul bu ( [ ] ) figurni qavuslar ichida yozishlik , 2- uslibi esa (new) kalit so'zidan foydalanib.

M:

// 1- misol

let arrayName = ['js' ,'java' , 'go'];

// 2- misol

let arrayName = new Array('js' ,'java' , 'go');

Array'dan element olish
Array - elementlarini uning indexslaridan foydalanib oloshligimiz mumkun . Array elementlarining raqamlari ( 0 ) - dan boshlanadi.

M:

let arrayName = ['js' ,'java' , 'go']; console.log(arrayName[0]); // natija ==> js console.log(arrayName[2]); // natija ==> go

Array'ga element qo'shish
Array'ga element qo'shish uchun " push() " va " ushift() " metodlaridan foydalanishligimiz mumkun . Bunda " push() " - metodi bizga massivnig ohiridan element qo'shin=b bersa " ushift() " meto'di esa aksincha boshidan element qo'shinb beradi , yaqshiroq tushunishlik uchun misol koramiz.

M:

// push() metodiga misol

let name = ['js' ,'java']; name.push('go'); console.log(name); //natija => ['js' ,'java' , 'go']

//unshift metodiga misol

let name = ['java' , 'go']; name.unshift('js'); console.log(name); //natija => ['js' ,'java' , 'go']

1. String metodlari
String length: Matn uzunligini qaytaradi.
M:

var str = "Hello"; console.log(str.length); // 5

String charAt(): Berilgan indeksdagi belgini qaytaradi.
M:

var str = "Hello"; console.log(str.charAt(1)); // "e"

String charCodeAt(): Berilgan indeksdagi belgining Unicode qiymatini qaytaradi.
M:

var str = "Hello"; console.log(str.charCodeAt(1)); // 101

String [ ]: Matndagi belgi indeks orqali qaytariladi.
M:

var str = "Hello"; console.log(str[1]); // "e"

String slice(): Berilgan indekslar orasidagi qismni kesib olish.
M:

var str = "Hello, World!"; console.log(str.slice(7, 12)); // "World"

String substring(): Berilgan indekslar orasidagi qismni kesib olish (slice bilan bir xil, lekin manfiy indekslar bilan ishlaydi).
M:

var str = "Hello, World!"; console.log(str.substring(7, 12)); // "World"

lesson- 9 Array va String 1 - Array Array - bir vaqitning o'zida bir nechta qiymatlarni o'zida saqlashi mumkun bo'lgan obect. uni ikki hil ko'rinishda yaratishlik mumkun : 1- ko'rinishii va eng ko'p qo'lanadiga usul bu ( [ ] ) figurni qavuslar ichida yozishlik , 2- uslibi esa (new) kalit so'zidan foydalanib.

M:

// 1- misol

let arrayName = ['js' ,'java' , 'go'];

// 2- misol

let arrayName = new Array('js' ,'java' , 'go');

Array'dan element olish Array - elementlarini uning indexslaridan foydalanib oloshligimiz mumkun . Array elementlarining raqamlari ( 0 ) - dan boshlanadi.

M:

let arrayName = ['js' ,'java' , 'go']; console.log(arrayName[0]); // natija ==> js console.log(arrayName[2]); // natija ==> go

Array'ga element qo'shish Array'ga element qo'shish uchun " push() " va " ushift() " metodlaridan foydalanishligimiz mumkun . Bunda " push() " - metodi bizga massivnig ohiridan element qo'shin=b bersa " ushift() " meto'di esa aksincha boshidan element qo'shinb beradi , yaqshiroq tushunishlik uchun misol koramiz.

M:

// push() metodiga misol

let name = ['js' ,'java']; name.push('go'); console.log(name); //natija => ['js' ,'java' , 'go']

//unshift metodiga misol

let name = ['java' , 'go']; name.unshift('js'); console.log(name); //natija => ['js' ,'java' , 'go']

IIFT function va Array meto'dlari

IIFT function IIFT function - o'zini o'zi chaqiruvchi funcsiya ham dep atasak bo'ladi sababini esa misolda ko'rib yanayam yahshiroq tushunib olamiz M :
(function (arg1 , arg2){ consile.log(arg1 + arg2); })(11 ,10); // natija => 21 2. Array Array - bir vaqitning o'zida bir nechta qiymatlarni o'zida saqlashi mumkun bo'lgan obect. uni ikki hil ko'rinishda yaratishlik mumkun : 1- ko'rinishii va eng ko'p qo'lanadiga usul bu ( [ ] ) figurni qavuslar ichida yozishlik , 2- uslibi esa (new) kalit so'zidan foydalanib. M :

// 1- misol

let arrayName = ['js' ,'java' , 'go'];

// 2- misol

let arrayName = new Array('js' ,'java' , 'go');

Array'dan element olish Array - elementlarini uning indexslaridan foydalanib oloshligimiz mumkun . Array elementlarining raqamlari ( 0 ) - dan boshlanadi. M :

let arrayName = ['js' ,'java' , 'go']; console.log(arrayName[0]); // natija ==> js console.log(arrayName[2]); // natija ==> go Array'ga element qo'shish Array'ga element qo'shish uchun " push() " va " ushift() " metodlaridan foydalanishligimiz mumkun . Bunda " push() " - metodi bizga massivnig ohiridan element qo'shin=b bersa " ushift() " meto'di esa aksincha boshidan element qo'shinb beradi , yaqshiroq tushunishlik uchun misol koramiz. M :

// push() metodiga misol

let name = ['js' ,'java']; name.push('go'); console.log(name); //natija => ['js' ,'java' , 'go']

//unshift metodiga misol

let name = ['java' , 'go']; name.unshift('js'); console.log(name); //natija => ['js' ,'java' , 'go']

Array elemeni ozgartirish Array elemeni ozgartirishlik uschun unig index'slaridan foydalansak bo'ladi. M :

let name = ['js' ,'java' , 'go' ]; console.log(name); //natija => ['js' ,'java' , 'go'] name[1]='c++'; console.log(name); //natija => ['js' ,'c++' , 'go']

Array elementlarini o'chirish Array - elementlarini o'chirishlik uchun "pop( )" va "shift( )"metodlaridan foydalansak bo'ladi , bubda "pop( )" - metodi massiv ichidagi ohirgi elamentni o'chiradi va o'chirilgan elamentni ham qaytarish imkoni mavjuv bu metodda , "shift( )"- metodi massiv ichidagi boshidagi elamentni o'chiradi va o'chirilgan elamentni ham qaytarish imkoni mavjuv bu metodda. M :

// "pop()" metodi

const name = ['js' , 'java' , 'go' , 'c++' , 'c#']; const name2 = name.pop(); console.log(name); // natija => ['js' , 'java' , 'go' , 'c++' ] console.log(name2); // natija => c#

//----------------------------------------------------------

//"shift()" metodi

const name = ['js' , 'java' , 'go' , 'c++' , 'c#']; const name2 = name.shift(); console.log(name); // natija => [ 'java' , 'go' , 'c++' , 'c#' ] console.log(name2); // natija => js Array uzunligini aniqlash Array uzunligini yani uning ichidagi conini aniqlashlik uchun ( lenght ) - hususiyatidan foydalanamiz . M :

const name = ['js' , 'java' , 'go' , 'c++' , 'c#']; console.log(name.lenght); // natiga ==> 5 concat() Metod concat() -metodi ikki yoki undan ortiq arraylarni bitlashtiridshlik uchun ishlatiladi . bu ularni birlashtiradi va natiga qaytaradi . M :

const array1 = [ 1, 4 ]; const array2 = [ 2, 3, 7 , 9 ]; const result = array1.concat(array2); console.log(result); // natija ==> [1, 4, 2, 3, 7, 9] indexOf() va lastIndexOf() Metodlari: indexOf() belgilangan elementni birinchi marta qaysi indeksda ekanligini qaytaradi, lastIndexOf() esa oxirgi marta qaysi indeksda ekanligini. M :

let fruits = ["apple", "banana", "kiwi", "melon", "banana"]; console.log(fruits.indexOf("banana")); // 1 console.log(fruits.lastIndexOf("banana")); // 4 find() metodi find() - metodi birinchi bo;lib shart bajargan array elamentini qaytaradi , kopincha bu metod array ichida meto'd qaytarishlikda ishlatiladi. M :

const result = [1, 4, 2, 3, 7, 9 ]; const findValue = (n) => n === 2 ; const findValue2= result.find(findValue); console.log(findValue2); // natiga => 2 // agar shartga tushmasa undefaind qaytaradi misol uchun n === 5 korinishini kiritsak. splice(start, deleteCount, item1, ..., itemN) Metodi: splice() metodi massivda belgilangan indeksdan boshlab ma'lum bir soni o'chiradi va/ya yangi element(lar)ni qo'shadi. M :

let fruits = ["apple", "banana", "orange", "grape"]; fruits.splice(2, 1, "kiwi", "melon"); console.log(fruits); // natija ==> ["apple", "banana", "kiwi", "melon", "grape"]

slice(start, end) Metodi: slice() metodi massivning belgilangan oraliqni ko'chirib olish uchun ishlatiladi. M :

let fruits = ["apple", "banana", "kiwi", "melon", "grape"]; let subArray = fruits.slice(1, 4); console.log(subArray); //natija ==> ["banana", "kiwi", "melon"]

indexOf() va lastIndexOf() Metodlari: indexOf() belgilangan elementni birinchi marta qaysi indeksda ekanligini qaytaradi, lastIndexOf() esa oxirgi marta qaysi indeksda ekanligini. M :

let fruits = ["apple", "banana", "kiwi", "melon", "banana"]; console.log(fruits.indexOf("banana")); //natiga => 1 console.log(fruits.lastIndexOf("banana")); //natiga => 4

includes() Metodi: includes() metodi massivda berilgan elementni qidiradi va mavjud bo'lsa true, aks holda false qaytaradi. M :

let fruits = ["apple", "banana", "kiwi", "melon"]; console.log(fruits.includes("kiwi")); // true console.log(fruits.includes("grape")); // false filter(callback) Metodi: filter() metodi berilgan shartlarni qondirib, shartlarni bajaradigan elementlarni qaytaradi. M :

let numbers = [10, 25, 5, 40]; let filteredNumbers = numbers.filter(number => number > 20); console.log(filteredNumbers); // natija =>### map(callback) Metodi: [25, 40]

map(callback) Metodi: map() metodi massivning har bir elementi uchun berilgan funksiyani bajarib, yangi bir massivni qaytaradi. M :

let numbers = [1, 2, 3, 4]; let squaredNumbers = numbers.map(number => number ** 2); console.log(squaredNumbers); //natija => [1, 4, 9, 16]