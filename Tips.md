<div dir="rtl" align="center">

- [فهرست](/README.md)

##### index

|     | فهرست                      |
| --- | -------------------------- |
| ۱   | [جاوااسکریپت](#javascript) |
| ۲   | [ری‌اکت](#reactjs)         |

</div>

---

### javascript

---

---

<div dir="rtl">

#### ۱. خروجی چیست؟

</div>

```javascript
const shape = {
  radius: 10,
  diameter() {
    return this.radius * 2;
  },
  perimeter: () => 2 * Math.PI * this.radius,
};

console.log(shape.diameter());
console.log(shape.perimeter());
```

<div dir="rtl">
<details><summary><b>جواب</b></summary>
<p>

### 20

### NAN

<div dir="rtl">
توضیح : همانطور که می بینید مقدار ‍‍‍diameter‍  یک فانکشن معمولی است
و مقدار perimeter یک arrow فانکش است

در فانکشن معمولی کلمه کلیدی ‍`this` به آبجکت shape اشاره می کند
اما در arrow فانکشن به آبجکت window اشاره دارد که در آن radius وجود ندارد

</div>
</p>
</details>

**[⬆ برو بالا](#index)**

## </div>

<div dir="rtl">

#### ۲. خروجی چیست؟

</div>

```javascript
const job = {
  name: "programmer",
};

const person = {
  name: "Hassan",
  programmer: true,
};

console.log(person[job["name"]]);
console.log(person[job.name]);
```

<div dir="rtl">
<details><summary><b>جواب</b></summary>
<p>

### true

### true

</p>
</details>

**[⬆ برو بالا](#index)**

## </div>

<div dir="rtl">

#### ۳. خروجی چیست؟

</div>

```javascript
let c = { name: "hassan" };
let d;

d = c;
c.name = "akbar";

console.log(d.name);
```

<div dir="rtl">
<details><summary><b>جواب</b></summary>
<p>

### akbar

<div dir="rtl">
در جاوااسکریپت تمام آبجکت ها با ریفرنس ذخیره می شوند لذا یک آبجکت را مساوی آبجکت دیگر قرار می دهیم در فضای حافظه به یک مکان اشاره دارند
</div>

</p>
</details>

**[⬆ برو بالا](#index)**

## </div >

<div dir="rtl">

#### ۴. خروجی چیست؟

</div>

```javascript
let number = 0;

console.log(number++);
console.log(++number);
console.log(number);
```

<div dir="rtl">
<details><summary><b>جواب</b></summary>
<p>

##### 0 (اول مقدار قبلی نشان داده می شود یعنی صفر و بعد اضافه می شود الان مقدار ۱ است اما صفر نشان داده میشود)

##### 2 (مقدار اضافه می شود بعد نشان داده می شود یعنی ۲ و الان مقدار ۲ است)

##### 2

</p>
</details>

**[⬆ برو بالا](#index)**

## </div>

<div dir="rtl">

#### ۵.globalThis چیست؟

</div>
<div dir="rtl">
<details><summary><b>جواب</b></summary>
<p>

globalThis آبجکت گلوبال کانتکس جاری را به ما بر می گرداند

- در مرورگر window

* در nodejs گلوبال یا global

* در ورکر ها self

</p>
</details>

**[⬆ برو بالا](#index)**

</div>

---

### Reactjs

---

---

###### ۱. ری اکت چیست؟

<details><summary><b>جواب</b></summary>
<p>

<div dir="rtl">
ری اکت یک کتابخانه فرانت اند اوپن سورس جاوااسکریپت است که برای ساخت رابط کاربری خصوصا برای اپلکیشن های تک صفه ای بکار می رود.

ری اکت در فیسبوک در سال ۲۰۱۱ ایجاد شد و تا به امروز در حال گسترش است

</div>
</p>
</details>

**[⬆ برو بالا](#index)**

---

###### ۱. سوال

<details><summary><b>جواب</b></summary>
<p>

<div dir="rtl">
شرح
</div>
</p>
</details>

**[⬆ برو بالا](#index)**

###### ادامه دارد و به مرور بروز رسانی خواهد شد ..........

## Javascript objects in nutshell

<img src="https://pbs.twimg.com/media/EiMvuJCU4AcwIpQ?format=jpg&name=4096x4096">
