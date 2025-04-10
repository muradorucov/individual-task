# Javascript Array Tasks

## Task-01

```
Üç addan ibarət massiv yaradın.
Massivin ikinci elementinin dəyərini “Classified” ilə əvəz edin.
Massivi konsola çıxarın.
```

## Task-02

```
Massiv verilib. "Episode 4: New Hope" kimi mesajları ardıcıl olaraq konsola çıxarın.
Massiv elementlərin düzün.
let arr = ['New Hope', 'The Empire Strikes Back', 'Return of the Jdi'];
//Episode 4: New Hope
//Episode 5: Empire strikes back
//Episode 6: Return of the Jdi
```

## Task-03

```
let salary = [
    [60, 60, 60, 60, 60, 60, 60, 60, 60, 60, 60, 60],
    [75, 75, 75, 75, 75, 75, 70, 77, 75, 75, 70, 75],
    [150, 150, 150, 150, 150, 150, 150, 150, 150, 150, 150, 180],
    [65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65],
    [80, 80, 80, 80, 80, 80, 80, 105, 105, 105, 105, 105],
    [65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65],
    [80, 80, 80, 80, 80, 80, 80, 80, 80, 80, 80, 120],
    [65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65, 65],
    [80, 80, 80, 80, 80, 80, 80, 90, 90, 90, 90, 90],
    [75, 75, 75, 75, 75, 75, 75, 75, 75, 75, 70, 75],
];
Şöbə işçilərinin əmək haqqını təhlil etmək üçün proqram tərtib edin.
Şöbədə müxtəlif maaşlarla 10 nəfər çalışır. Şöbə işçilərinin əmək haqlarını təhlil etmək
üçün proqram tərtib edin.
 - Bütün bir departamentin bir il üçün ümumi maaşlarının cəmini qaytaran bir funksiya yazın.
salary massivi əsasında il ərzində bütün işçilərin maaşlarının cəmini qaytaran
 getAnnualSalary() funksiyasını yazın.
- Ay nömrəsinə görə işçilərin aylıq maaşlarını massiv halında almaq üçün funksiya yazın.
Ayın nömrəsini parametr kimi qəbul edən və salary massivindən
 həmin ay üçün işçi maaşlarını massiv halında qaytaran getMonthlySalary() funksiyasını yazın.
Ayın nömrəsi elementin indeks nömrəsi ilə eyni deyil.
- Rüb ərzində maaşların ümumi cəmini qaytaran funksiya yazın.
Parametr kimi rübün rəqəmini (1, 2, 3 və ya 4) qəbul edən və
 salary massivi əsasında həmin rüb üçün şöbənin bütün
işçilərinin maaşlarının cəmini qaytaran getQuarterSalary() funksiyasını yazın.
Rüb - 3 aylıq bir müddətdir.
```

## Task-04

```
İstifadəçidən beş ədəd elementi daxil etməyi tələb edən, onları massivə yazan və
ən kiçik ədədi konsola çıxaran proqram yazın.
```

## Task-05

```Verilən mətn tip dəyərdəki vergülləri nöqtəli vergüllə əvəz edin.
'32, 31, 34, 36, 31' mətni verilmişdir ,İçindəki vergülləri nöqtəli
vergüllə əvəz edin.(Massivden sitifade ederek)(join)
```

## Task-06

```
Üç qrup yoldaşının adlarından ibarət massiv yaradın;
Başqa bir qrup yoldaşının adını massivin sonuna əlavə edin;
İlk adı silin;
Massivi konsola çıxarın.
```

## Task-07(rest-in istifadesi)

```
Massiv üzərində əməliyyatlar aparın.
10 ədəddən ibarət massiv yaradın.
İlk 2 ədədi dəyişənlərə yazın və qalanlardan yeni massiv yaradın.
```

## Task-08

```
Massivin maksimal dəyərini tapın.
10 rəqəmdən ibarət massiv yaradın.
Math.max funksiyasından istifadə edərək onların arasında maksimumu tapın.
spread-operatorundan istifadə edərək massiv arqumentlərini funksiyaya ötürün.
```

## Task-09

```
Massivin bütün elementlərinin dəyərin ikiqat artırın.
5 rəqəmdən ibarət massiv yaradın.
Orijinal massivin surətini çıxarın və yeni massivin bütün elementlərini ikiqat artırın.
Orijinal massivin dəyişmədiyini yoxlayın.
```

## Task-10

```
Proqramlaşma şöbəsinin işçilərini saxlayan massiv yaradın.
Şirkətin 10 işçisi haqqında məlumat olan massiv verilib. development massivi yaradın,
hansıki proqramlaşma şöbəsinin işçilərini özündə saxlayacaq,
yəni department özəlliyinin dəyəri «development» olan işçiləri.
let employees = [
[ 'Jaylee Macy', 'marketing' ],
[ 'John Smith', 'management' ],
[ 'Blossom Hartley', 'design' ],
[ 'Austin Carpenter', 'marketing' ],
[ 'Joan Knowles', 'development' ],
[ 'Sally Nunez', 'management' ],
[ 'Laurel Ward', 'development' ],
[ 'Lark Simon', 'marketing' ],
[ 'Jane Stone', 'management' ],
[ 'Courtney Olson', 'development' ],
];
```

## Task-11

```
Elektron növbəni idarə etmək üçün proqram tərtib edin.
İstifadəçidən məlumat tələb edən və növbəni yeniləyən proqram tərtib edin.

- İstifadəçidən növbəni yeniləmək üçün məlumat tələb edin.
- Əgər istifadəçi yeni müştərinin ad və soyadını daxil edibsə,
proqram müştərini növbənin sonuna əlavə edir.
- İstifadəçi boş bir dəyər daxil edərsə, proqram növbədə birincinin adını və
 soyadını göstərir və onu növbədən çıxarır.
- İstifadəçi «=» işarəsini daxil edərsə, proqram dayanır və növbə massivini konsola çıxarır.
```

## Task-12

```
Tam ədədlər massivini qəbul edən, onu artan ardıcıllıqla sıralayan və sıralanmış massivi geri
qaytaran sortArray funksiyasını yazın.
let array = [1, 6, 34, 5, 1, -4, 54, 76, 23, 65, 3, 50, 45, 100, 2346, -52, 6545, 0, 45, 22];
```

## Task-13

```
Rəqəmlər massivini parametr kimi qəbul edən və həmin massivdən konsola
bütün mənfi ədədləri çıxaran funksiya yazın.
```

## Task-14

```
Rəqəmlər massivini parametr kimi qəbuil edən və həmin massivdəki bütün müsbət
ədədləri konsola çıxaran funksiya yazın.
İterasiya üçün anonim funksiyadan istifadə edin.
```

## Task-15

```
Geri çağırış funksiyalarını yazın (callback) printWithDashes, printWithHearts, printWithIndex.
Massiv verilmişdir. 3 geri çağırış funksiyası yazın (callback): printWithDashes,
 printWithHearts, printWithIndex, hansıki onlar belə çağırılan zamanı
names.forEach(printWithDashes);
names.forEach(printWithHearts);
names.forEach(printWithIndex);
-array- const names = ["Michael", "Trevor", "Franklin", "Lamar", "Jimmy"];

OUTPUT:
kosnsolda çıxsın:

---

Michael

---

---

Trevor

---

---

Franklin

---

---

Lamar

---

---

Jimmy

---

<3<3<3<3 Michael <3<3<3<3
<3<3<3<3 Trevor <3<3<3<3
<3<3<3<3 Franklin <3<3<3<3
<3<3<3<3 Lamar <3<3<3<3
<3<3<3<3 Jimmy <3<3<3<3
0 - Michael
1 - Trevor
2 - Franklin
3 - Lamar
4 - Jimmy
```

## Task-16

```
Kebab-case formatında mətni parametr kimi qəbul edən və onu UPPER_CASE mətninə
 çevirən kebabToUpper funksiyasını yazın.
INPUT: console.log(kebabToUpper('first-user'));
OUTPUT: FIRST_USER
```

# MAP,FILTER,FIND

## Task-17

```
Orijinal massivin elementlərindən ibarət yeni massiv yaradın.
Rəqəmlər massivi verilmişdir.
Aşağıdakı kimi dəyişdirilən orijinal massivin elementlərindən ibarət yeni massiv yaradın:

- mənfi ədədlər müsbət olublar;
- müsbət ədədlər ikiqat artırılıb.
  let numbers = [1, 5, -7, 3, -9, 4, -6, 2];
```

## Task-18

```
Mətnlər massivini parametr kimi qəbul edən və massivin ilk üç simvoldan
 ibarət elementini qaytaran funksiya yazın.
```

## Task-19

```
Adlar massivi verilib. A hərfi ilə başlayan orijinal massivdəki
elementlərdən ibarət yeni massiv yaradın.
```

## Task-20

```
addTax() funksiyası yaradın. Verilmiş ƏDV-siz qiymətlərlə olan
price massivini ona ötürün. addTax() funksiyasının köməyi ilə ƏDV ilə
qiymətlərin daxil olduğu massiv yaradın və onu konsola çıxarın. ƏDV 20% təşkil edir.
```

## Task-21

```
Rəqəmlər massivini parametr kimi qəbul edən və massivdə neçə tək və cüt ədədin
olması barədə məlumatı qaytaran countEvensAndOdds() funksiyasını yazın.
Numune: Funksiya «Massivdə 4 cüt və 2 tək ədəd var» formasında mesaj qaytarır.
```
