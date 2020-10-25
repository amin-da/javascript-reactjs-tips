<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  <img src="https://img.icons8.com/nolan/64/react-native.png"/>
  <h1>نکات جاوااسکریپت و ری اکت جی اس</h1>

---

<a href="https://twitter.com/HoomanAmini">Twitter</a>
|| <a href="youtube.com/c/hoomanamini">youtube</a>
|| <a href="https://virgool.io/@amini.hooman">Blog</a>

</div>

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
توضیح : همانطور که می بینید مقدار ‍‍‍`diameter‍` یک فانکشن معمولی است
و مقدار `premeter‍‍` یک arrow فانکش است

در فانکشن معمولی کلمه کلیدی ‍`this` به آبجکت shape اشاره می کند
اما در arrow فانکشن به آبجکت window اشاره دارد که در آن radius وجود ندارد

</div>
</p>
</details>

---
