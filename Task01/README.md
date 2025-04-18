# Javascript Task(variables,Data types,Operators)

## Task-01
Konsola mesaj verin:
```js
console.log("My name is Murad");
```

## Task-02
Adı `name` və adınızın mənimsədildiyi sabit dəyişən təyin edin. 
Bu dəyişənin dəyərini konsolda göstərin.
```js
const name = "Murad";
console.log(name);
```

## Task-03
Bu adlardan hansının dəyişən üçün istifadə oluna biləcəyini göstərin. 
Birdən çox variant seçin.
```
2user
c@rt
person
title color
console
$add
```

## Task-04
Depodaki bütün kitabların ümumi dəyərini konsola çıxarın:
```js
let bookPrice = 750;
let bookAmount = 14;
console.log(bookPrice * bookAmount);
```

## Task-05
Dəyişən dəyərini saniyə metrə çevirin və onu konsola çıxarın.
```js
let kmhSpeed = 75;
let msSpeed = kmhSpeed * 1000 / 3600;
console.log(msSpeed);
```

## Task-06
İstifadəçinin doğum tarixini soruşan və bu günə qədər yaşadığı 
günlərin sayını göstərən proqram yazın.

## Task-07
Ədədlər üzərində əməliyyatları yerinə yetirin.
```js
let num = 45;
console.log(num ** 5);
console.log(num % 3);
```

## Task-08
Konsola bu növ mesaj çıxarın:
```js
let firstName = 'Alan';
let lastName = 'Turing';
console.log(`Sizin adınız ${firstName} ${lastName}. Tanışlığımıza çox şadam!`);
```

## Task-09
Şablon mətnlərdən istifadə edərək, 
konsola "Sizi bir daha görməyimizə şadıq, [firstName] [lastName]".
```js
console.log(`Sizi bir daha görməyimizə şadıq, ${firstName} ${lastName}`);
```

## Task-10
Addaki hərflərin sayını konsola çıxarın.
```js
let fullName = "Murad Orucov";
console.log(fullName.replace(/\s/g, '').length);
```

## Task-11
İstifadəçinin ad soyadının baş hərflərini konsola çıxaran proqram yazın.
```js
let fullName = "Murad Orucov";
let initials = fullName.split(' ').map(n => n[0]).join('.');
console.log(initials);
```

## Task-12
İstifadəçidən tam adını daxil etməyini istəyin və soyadı ilə adının yerini dəyişin.
```js
let fullName = prompt("Adınızı daxil edin: (AD SOYAD)");
let [firstName, lastName] = fullName.split(' ');
console.log(`${lastName} ${firstName}`);
```

## Task-13
Konsola "Salam, [ad]!" formatında salamlama mesajı çıxarın.
```js
let name = prompt("Adınızı daxil edin:");
console.log(`Salam, ${name}!`);
```

## Task-14
İki ədədin toplama, çıxma, vurma və bölməsinin nəticələrin konsola alt-alta 4 sətir olaraq çıxarın.

## Task-15
12345 və 98765 ədədlərinin hasilindən alınan nəticənin 6-cı rəqəmini tapan proqram yazın.

## Task-16
Əməliyyatların nəticəsini müəyyənləşdirin.

```plaintext
"" + 1 + 0 = 
"" - 1 + 0 = 
"true" - false = 
6 / "3" = 
4 + 5 + "px" = 
"$" + 4 + 5 =  
"4" - 2 = 
NaN + "px" =
7 / 0 = 
"-9" + 5 = 
"-9" - 5 = 
null + 1 =
undefined + 1 =
```

## Task-17
Rəqəmlərin cəmini göstərən proqram yazın.
İstifadəçidən dörd rəqəmli ədəd daxil etməsini xahiş edən və 
sonra daxil edilmiş ədədlərin rəqəmlərinin cəmini konsola çıxaran proqram yazın.

## Task-18
İstifadəçinin soyadını və adını almaq üçün proqram tərtib edin.
Proqram bir mesajla istifadəçinin soyadını və adını daxil etməsini istəyir və 
konsola «Salam, <ad>!» mesajını çıxarır.

## Task-19
Qiyməti mətn halına salan proqram tərtib edin.
İstifadəçidən «530.90» formatında qiymət daxil etməyi xahiş edən və
qiyməti «530 manat 90 qəpik» formatında konsola çıxaran proqram tərtib edin.

## Task-20
Vergi nəzərə alınmadan əmək haqqı məbləğini hesablayan proqram tərtib edin. 
Proqram istifadəçidən əmək haqqı məbləğin soruşur və 
13% vergi istisna olmaqla məbləği konsola çıxarır.

## Task-21
İstifadəçidən soyad, ad və ata adını istəyən, 
soyadı və baş hərfləri konsola çıxaran proqram tərtib edin.
Məsələn, «İvanov Pyotr Sergeevich» — «İvanov P.S.».

## Task-22
Depozitdən mənfəətin hesablanması üçün proqram yazın.
Proqram istifadəçidən əmanətin məbləğini, müddətini və 
faiz dərəcəsini daxil etməsini istəyir və gözlənilən mənfəəti hesablayır.

## Task-23
Müxtəlif müqayisə operatorları ilə 5 ifadə yazın.
value dəyişəni üçün müxtəlif müqayisə operatorları ilə 5 ifadə yazın, 
hansıki əməliyyat nəticəsi value = 10 üçün true və value = 20 üçün false olacaq.

## Task-24
İstifadəçidən yaşını soruşun. 
Əgər yaşı 18-dən azdırsa, o zaman brauzerdə «Access denied» bildirişi çıxarın. 
Əks halda «Access granted» bildirişini çıxarın.

## Task-25
Üç ədədin ortancılını tapmaq üçün proqram yazın.
İstifadəçidən bir bildirişlə üç ikirəqəmli ədəd daxil etməsini xahiş edin. 
Konsola orta ədədi, yəni nə ən böyüyü, nə də ən kiçiyini çıxarmayın.
İstifadəçi bir neçə eyni nömrə daxil edibsə, xəta bildirişi çıxarın.

Məsələn:
- "45 46 47"
- "47 46 45"
- "46 45 47"
- "46 47 45"


## Task-26
İstifadəçidən bir il daxil etməsini soruşun və ilin uzun il olub olmadığını yoxlayın.  
Uzun il 4-ə qalıqsız bölünən ildir.  
Daxil edilmiş il uzun ildirsə, konsola mesaj cıxarın.  
«İl uzun il deyil» və ya «İl uzun ildir» mesajını çıxarın.

## Task-27
if...else operatoru ilə yazılmış kodu switch operatoruna dəyişdirməklə kodu yenidən yazın.
```javascript
let id = prompt('enter product id:');
if (id === '1') {
  alert('Available 10 pcs.');
} else if (id === '2') {
  alert('Available 256 pcs.');
} else if (id === '3') {
  alert('Available 53 pcs.');
} else if (id === '4') {
  alert('There are 3 available.');
} else {
  alert('Out of stock');
}
```

## Task-28
İstifadəçidən onun cinsini (M və ya F hərfləri şəklində) sorğulayan və 
gender dəyişəninə male yaxud female sözlərindən birini yazdıran proqramı yazın

## Task-29
Ayın adını mətnlə konsola yazdıran bir program yazın.
İstifadəçidən ayın nömrəsini soruşun və adını konsola çıxarın.

## Task-30
İstifadəçi tərəfindən daxil edilmiş tarixin təsvirini çıxarın.
İstifadəçidən tarixi «2009.12.19» formatında daxil etməyi xahiş edin. 
Tarixin təsvirini «19 Dekabr 2009-cu il» formatında çıxarın.
Daxil edilmiş dəyərə validator əlavə edin.
İstifadəçi səhv formatda dəyər daxil edərsə, «Yanlış dəyər daxil edilib» bildirişi göstərin.


## Task-31
```
let p = 8;
let q = p-- - --p + p++ + ++p;
console.log(p, q);
```


## Task-32
```
let a = 6, b = 4, c = 2;

let x = ++a - b-- + c++ - --b + a++;
let y = a-- + --c - ++b + x++ - --a;

console.log(a, b, c, x, y);
```


## Task-33
```
let a = 7, b = 3, c = 5;

let x = a-- - ++b + c++ - --a + b++ - --c + a++ - b-- + c++;
let y = --x + a++ - --b + c-- - x++ + ++a - b++ + --c - x--;
let z = a-- + ++b - --c + x++ - --y + b-- - ++x + c++ - --a + y++;

console.log(a, b, c, x, y, z);
```