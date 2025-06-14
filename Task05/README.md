# Javascript Object Tasks

## Task-01

```
Adınız, cinsiniz və doğum tarixiniz olan user obyekti
yaradın (name, gender, birthday).
Konsola doğum tarixini çıxarın.
```

## Task-02

```
Bu obyektə yaş (age) əlavə edin və doğum tarixini silin.
Alınmış obyekti konsola çıxarın.
```

## Task-03

```
Obyektə metodlar əlavə edin.
    setAge — istifadəçi yaşını dəyişdirən metoddur.
    getYearsBeforeRetirement — pensiyaya qədər istifadəçinin
qalan illərinin sayını qaytaran metoddur.
Bu metodları çağırın.
```

## Task-04

Müştəri Kredit kartı ilə işləmək üçün obyekt yaradın.
Müştərinin hesabı haqqında əsas məlumatları və onunla işləmə
metodlarını əhatə edən client obyekti yaradın.

#### =>client obyekti yaradın.

```
	Kredit kartı müştərisi üçün aşağıdakı xüsusiyyətlərə malik obyekt yaradın:
	- Tam adı müştərinin (fullName).
	- Kredit limiti (creditLimit).
	- Cari balans (balans).
	- Minimum ödənişin faizi (precentOfMinPayment).
```

#### =>Cari balans əldə etmək üçün getBalance metodu əlavə edin.

```
    getBalance metodu, balans mənfi olarsa, müştərinin balansı və ya onun borcu haqqında bir mesaj qaytarır.
    Metodun çağırılma nümunəsi:
    console.log(client.getBalance()).
    Mesaj nümunələri:
    «Balansınız 3000»,
    «Borcunuz 2000».

```

#### =>Minimum ödəniş məbləği üçün getMinPaymant metodunu əlavə edin.

```
    getMinPaymant metodu borc məbləği və minimum ödəniş
    faizinə əsasən formalaşan minimum
    ödəniş məbləği haqqında mesaj qaytarır.
    Əgər borc yoxdursa, metod müvafiq mesajı qaytarır.
    Metodun çağırılma nümunəsi:
    console.log(client.getMinPaymant()).
    Mesaj nümunələri:
    «Minimum ödənişiniz 240»,
    «Sizin borcunuz yoxdur».
```

#### =>Hesabdan pul silmək üçün withdraw metodu əlavə edin.

```
    withdraw metodu cari balansı parametr kimi ötürülən
    pul məbləği qədər azaldır.
    Mövcud vəsait kifayət deyilsə (cari balans və kredit
    limitinin cəmi), metod konsola müvafiq mesajı çıxarır.
    client.widthdraw(900)
```

#### =>Hesaba pul əlavə etmək üçün refill metodu əlavə edin.

```
    refill metodu parametr kimi qəbul edilən məbləğ qədər balansı artırır.
    client.refill(1000)
```

## Task-05

```
Kalkulyator obyekti yaradın.
Əsas riyazi hesablamaları yerinə yetirən və nəticəni
yaddaşda saxlaya bilən kalkulyator obyekti yaradın.
	- Obyekt yaradın və toplama, çıxma, vurma,
    bölmə üçün metodlar əlavə edin.
	Metodlar parametr kimi 2 ədəd götürür və bu ədədlər
     üzərində müvafiq əməliyyatın nəticəsini qaytarır.
	Yaddaşla işləmək imkanı əlavə edin.
	- Obyektə dəyəri saxlamaq üçün özəllik əlavə edin.
    Onunla işləmək üçün metodlar yaradın:
	dəyərin yaddaşda saxlanması, yaddaşın təmizlənməsi,
    yaddaşdan dəyərin oxunması.
```


## Task-06

```
Verilmiş stringdə ən çox təkrarlanan elementi qaytaran `mostFrequent()` funksiyasını yazın.
Məsələn, `mostFrequent("1, 3, 2, 3, 4, 3, 5, 3")` çağırıldıqda `3` qaytarmalıdır.
```
