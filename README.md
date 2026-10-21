# Matematik funksiyalar (math moduli)

## math_func01

Allamurodning dumaloq stoli radiusi r (m) berilgan. Stol yuzasini (π·r²) hisoblang va 2 xona aniqlikda yaxlitlab qaytaring. `math.pi` dan foydalaning.

**Misol 1:**

```Python
Kirish: r = 0.6
Chiqarish: 1.13
```

**Misol 2:**

```Python
Kirish: r = 1
Chiqarish: 3.14
```

---

## math_func02

Allamurodning kvadrat shaklidagi yeri maydoni berilgan. Yer tomonini `math.sqrt()` yordamida topib qaytaring.

**Misol 1:**

```Python
Kirish: maydon = 144
Chiqarish: 12.0
```

**Misol 2:**

```Python
Kirish: maydon = 2500
Chiqarish: 50.0
```

---

## math_func03

Allamurod do'stlari bilan sayohatga chiqmoqda. Har bir taksiga 4 kishi sig'adi. Odamlar soni berilgan. Kerakli taksilar sonini `math.ceil()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: odamlar = 23
Chiqarish: 6
```

**Misol 2:**

```Python
Kirish: odamlar = 8
Chiqarish: 2
```

---

## math_func04

Allamurodda pul bor, bitta kitob narxi berilgan. U nechta kitob sotib ola olishini `math.floor()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: pul = 100000, narx = 28000
Chiqarish: 3
```

**Misol 2:**

```Python
Kirish: pul = 56000, narx = 28000
Chiqarish: 2
```

---

## math_func05

Allamurodda n ta har xil kitob bor. Ularni javonga necha xil tartibda terish mumkinligini `math.factorial()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: n = 5
Chiqarish: 120
```

**Misol 2:**

```Python
Kirish: n = 3
Chiqarish: 6
```

---

## math_func06

Allamurodda a ta olma va b ta nok bor. U ulardan bir xil tarkibli eng ko'p nechta sovg'a paketi tayyorlay olishini `math.gcd()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: a = 48, b = 36
Chiqarish: 12
```

**Misol 2:**

```Python
Kirish: a = 10, b = 7
Chiqarish: 1
```

---

## math_func07

Allamurodning velosiped g'ildiragi radiusi r (m) berilgan. G'ildirak bir marta aylanganda bosib o'tadigan masofani (2·π·r) hisoblang va 2 xona aniqlikda yaxlitlab qaytaring.

**Misol 1:**

```Python
Kirish: r = 0.35
Chiqarish: 2.2
```

**Misol 2:**

```Python
Kirish: r = 0.5
Chiqarish: 3.14
```

---

## math_func08

Allamurodning kub shaklidagi akvariumi qirrasi a (m) berilgan. Akvarium hajmini `math.pow()` yordamida hisoblab qaytaring.

**Misol 1:**

```Python
Kirish: a = 0.5
Chiqarish: 0.125
```

**Misol 2:**

```Python
Kirish: a = 2
Chiqarish: 8.0
```

---

## math_func09

Toshkentda havo harorati kasr son ko'rinishida berilgan. Uning butun qismini `math.trunc()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: harorat = -3.7
Chiqarish: -3
```

**Misol 2:**

```Python
Kirish: harorat = 27.9
Chiqarish: 27
```

---

## math_func10

Allamurodning monitori eni va bo'yi (dyuym) berilgan. Ekran diagonalini `math.hypot()` yordamida hisoblang va 2 xona aniqlikda yaxlitlab qaytaring.

**Misol 1:**

```Python
Kirish: en = 16, boy = 9
Chiqarish: 18.36
```

**Misol 2:**

```Python
Kirish: en = 3, boy = 4
Chiqarish: 5.0
```

---

## math_func11

Allamurod tug'ilgan kuniga n ta do'stidan k tasini taklif qilmoqchi. Necha xil usulda tanlash mumkinligini `math.comb()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: n = 10, k = 3
Chiqarish: 120
```

**Misol 2:**

```Python
Kirish: n = 5, k = 5
Chiqarish: 1
```

---

## math_func12

Allamurod sport zaliga har a kunda, akasi esa har b kunda boradi. Bugun ikkalasi birga borishdi. Necha kundan keyin yana birga borishlarini hisoblab qaytaring (EKUK). `math.gcd()` dan foydalaning.

**Misol 1:**

```Python
Kirish: a = 4, b = 6
Chiqarish: 12
```

**Misol 2:**

```Python
Kirish: a = 6, b = 10
Chiqarish: 30
```

---

## math_func13

Allamurod bankka pul qo'ydi, yillik foiz berilgan (murakkab foiz). Pul necha to'liq yilda ikki baravar ko'payishini hisoblang: log(2) / log(1 + foiz/100) ni yuqoriga yaxlitlang. `math.log()` va `math.ceil()` dan foydalaning.

**Misol 1:**

```Python
Kirish: foiz = 20
Chiqarish: 4
```

**Misol 2:**

```Python
Kirish: foiz = 10
Chiqarish: 8
```

---

## math_func14

Allamurodning maoshi n berilgan. Sonda nechta raqam borligini `math.log10()` yordamida hisoblab qaytaring.

**Misol 1:**

```Python
Kirish: n = 6500000
Chiqarish: 7
```

**Misol 2:**

```Python
Kirish: n = 1000
Chiqarish: 4
```

---

## math_func15

Allamurod tog'ga chiqmoqda. U qiyalik bo'ylab masofa (m) yurdi, qiyalik burchagi gradusda berilgan. Ko'tarilgan balandlikni (masofa·sin(burchak)) hisoblang va 2 xona aniqlikda yaxlitlab qaytaring. `math.radians()` va `math.sin()` dan foydalaning.

**Misol 1:**

```Python
Kirish: masofa = 100, burchak = 30
Chiqarish: 50.0
```

**Misol 2:**

```Python
Kirish: masofa = 200, burchak = 90
Chiqarish: 200.0
```

---

## math_func16

Allamurodning uchburchak shaklidagi gulzori tomonlari a, b, c berilgan. c tomon qarshisidagi burchakni kosinuslar teoremasi bo'yicha gradusda toping: C = arccos((a² + b² − c²) / (2ab)). Natijani 1 xona aniqlikda yaxlitlab qaytaring. `math.acos()` va `math.degrees()` dan foydalaning.

**Misol 1:**

```Python
Kirish: a = 3, b = 4, c = 5
Chiqarish: 90.0
```

**Misol 2:**

```Python
Kirish: a = 5, b = 5, c = 5
Chiqarish: 60.0
```

---

## math_func17

Allamurod maydoni berilgan doira shaklidagi gulzor qilmoqchi. Gulzor radiusini (√(maydon/π)) hisoblang va 2 xona aniqlikda yaxlitlab qaytaring.

**Misol 1:**

```Python
Kirish: maydon = 50
Chiqarish: 3.99
```

**Misol 2:**

```Python
Kirish: maydon = 314.16
Chiqarish: 10.0
```

---

## math_func18

Allamurod noutbukni kreditga oldi. Kredit summasi, yillik foiz va oylar soni berilgan. Oylik foiz r = foiz / 12 / 100. Annuitet oylik to'lovini hisoblang: summa · r / (1 − (1 + r)⁻ᵒʸˡᵃʳ). Natijani `math.ceil()` yordamida yuqoriga yaxlitlab qaytaring.

**Misol 1:**

```Python
Kirish: summa = 12000000, foiz = 24, oylar = 12
Chiqarish: 1134716
```

**Misol 2:**

```Python
Kirish: summa = 6000000, foiz = 12, oylar = 6
Chiqarish: 1035291
```

---

## math_func19

Allamurodda n dona kvadrat kafel bor. U ulardan iloji boricha katta to'liq kvadrat yasamoqchi. Nechta kafel ortib qolishini `math.isqrt()` yordamida hisoblab qaytaring.

**Misol 1:**

```Python
Kirish: n = 150
Chiqarish: 6
```

**Misol 2:**

```Python
Kirish: n = 144
Chiqarish: 0
```

---

## math_func20

Allamurodning jamg'armasi boshlang'ich summadan yil yil davomida oxirgi summaga yetdi. O'rtacha yillik o'sish foizini hisoblang: ((oxirgi / boshlangich)^(1/yil) − 1) · 100. Natijani 2 xona aniqlikda yaxlitlab qaytaring. `math.pow()` dan foydalaning.

**Misol 1:**

```Python
Kirish: boshlangich = 5000000, oxirgi = 8640000, yil = 3
Chiqarish: 20.0
```

**Misol 2:**

```Python
Kirish: boshlangich = 10000000, oxirgi = 12100000, yil = 2
Chiqarish: 10.0
```

