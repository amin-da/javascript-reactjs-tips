<div align="center" dir="rtl">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  <img src="https://img.icons8.com/nolan/64/react-native.png"/>
  <h1>نکته ها و سوال های جاوااسکریپت </h1>
  <h1> و ری اکت جی اس</h1>

---

<a href="https://twitter.com/HoomanAmini">Twitter</a>
|| <a href="youtube.com/c/hoomanamini">Youtube</a>
|| <a href="https://virgool.io/@amini.hooman">Blog</a>

</div>

|     | فهرست                                                                      |
| --- | -------------------------------------------------------------------------- |
| ۱   | [جاوااسکریپت](#what-is-react)                                              |
| ۲   | [ری‌اکت](#%DB%B1-%D8%B1%DB%8C-%D8%A7%DA%A9%D8%AA-%DA%86%DB%8C%D8%B3%D8%AA) |

---

---

<div align="center" dir="rtl"> جاوااسکریپت</div>

---

---

###### ۱. خروجی چیست؟

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

---

###### ۲. خروجی چیست؟

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

<details><summary><b>جواب</b></summary>
<p>

### true

### true

</p>
</details>

---

###### ۳. خروجی چیست؟

```javascript
let c = { name: "hassan" };
let d;

d = c;
c.name = "akbar";

console.log(d.name);
```

<details><summary><b>جواب</b></summary>
<p>

### akbar

<div dir="rtl">
در جاوااسکریپت تمام آبجکت ها با ریفرنس ذخیره می شوند لذا یک آبجکت را مساوی آبجکت دیگر قرار می دهیم در فضای حافظه به یک مکان اشاره دارند
</div>

</p>
</details>

---

---

<div align="center" dir="rtl"> ری‌اکت</div>

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

###### ادامه دارد و به مرور بروز رسانی خواهد شد ..........
