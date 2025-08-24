

## 1. Renkler

|Özellik|Class / Örnek|
|---|---|
|Text Rengi|`text-gray-800` / `text-red-500` / `text-blue-600` / `text-[#f8f1f0]`|
|Arka Plan Rengi|`bg-white` / `bg-gray-100` / `bg-blue-500` / `bg-[#f8f1f0]`|
|Border Rengi|`border-gray-300` / `border-red-400`|
|Hover Rengi|`hover:bg-blue-600` / `hover:text-red-500`|
|Focus / Ring|`focus:ring-2 focus:ring-blue-500`|
|Dark Mode|`dark:bg-gray-800 dark:text-white`|

**React Örnek:**
```jsx
<div className="text-gray-800 bg-[#f8f1f0] hover:bg-gray-200 focus:ring-2 focus:ring-blue-500 p-4 rounded">Örnek Metin</div>
```

---
## 2. Typography

| Özellik        | Class / Örnek                                                                         |
| -------------- | ------------------------------------------------------------------------------------- |
| Font Boyutu    | `text-xs` / `text-sm` / `text-base` / `text-lg` / `text-xl` / `text-2xl` / `text-4xl` |
| Font Kalınlığı | `font-thin` / `font-normal` / `font-semibold` / `font-bold` / `font-extrabold`        |
| Font Style     | `italic` / `not-italic`                                                               |
| Font Family    | `font-sans` / `font-serif` / `font-mono`                                              |
| Text Hizalama  | `text-left` / `text-center` / `text-right`                                            |
| Satır Aralığı  | `leading-none` / `leading-tight` / `leading-loose`                                    |
| Harf Aralığı   | `tracking-tight` / `tracking-normal` / `tracking-wide`                                |
| Word Break     | `break-normal` / `break-words` / `truncate`                                           |
| Responsive     | `text-sm md:text-lg lg:text-xl`                                                       |

**React Örnek:**
```jsx
<p className="text-sm md:text-lg font-semibold italic leading-tight text-gray-800">
  Responsive ve stilize metin
</p>
```

---
## 3. Spacing (Margin & Padding)

|Özellik|Class / Örnek|
|---|---|
|Margin|`m-4` / `mt-2` / `mr-4` / `mb-6` / `ml-8`|
|Padding|`p-4` / `pt-2` / `pr-4` / `pb-6` / `pl-8`|
|X-Y ekseni|`mx-4` / `my-6`|
|Negatif margin|`-mt-2` / `-ml-4`|
|Responsive|`p-4 md:p-6 lg:p-8`|

**React Örnek:**
```jsx
<div className="m-4 md:m-6 p-4 lg:p-8 bg-gray-100 rounded">
  İçerik kutusu
</div>
```


---

## 4. Width & Height

| Özellik      | Class / Örnek                           |
| ------------ | --------------------------------------- |
| Width Sabit  | `w-10` / `w-40` / `w-64`                |
| Width Oran   | `w-1/2` / `w-1/3` / `w-3/4` / `w-full`  |
| Height Sabit | `h-10` / `h-40` / `h-64`                |
| Height Oran  | `h-1/2` / `h-full` / `h-screen`         |
| Min/Max      | `min-h-screen` / `max-w-xl`             |
| Responsive   | `w-full md:w-1/2 lg:w-1/3 h-40 md:h-56` |

**React Örnek:**
```jsx
<div className="w-full md:w-1/2 lg:w-1/3 h-40 md:h-56 bg-blue-200 rounded">
  Responsive kutu
</div>
```

## 5. Border & Radius & Shadow

| Özellik          | Class / Örnek                                                        |
| ---------------- | -------------------------------------------------------------------- |
| Border Kalınlığı | `border` / `border-2` / `border-4`                                   |
| Border Rengi     | `border-gray-400` / `border-blue-500`                                |
| Radius           | `rounded` / `rounded-lg` / `rounded-xl` / `rounded-full`             |
| Shadow           | `shadow-sm` / `shadow-md` / `shadow-lg` / `shadow-xl` / `shadow-2xl` |
| Responsive       | `md:border-2 lg:border-4`                                            |

**React Örnek:**
```jsx
<div className="border border-gray-400 rounded-xl shadow-lg p-4">
  Kart içeriği
</div>
```


---

## 6. Flex & Grid

| Özellik        | Class / Örnek                                                          |
| -------------- | ---------------------------------------------------------------------- |
| Flex Container | `flex`                                                                 |
| Yön            | `flex-row` / `flex-col`                                                |
| Flex Wrap      | `flex-wrap` / `flex-nowrap`                                            |
| Hizalama (X)   | `justify-start` / `justify-center` / `justify-end` / `justify-between` |
| Hizalama (Y)   | `items-start` / `items-center` / `items-end`                           |
| Gap            | `gap-2` / `gap-4` / `gap-8`                                            |
| Grid           | `grid grid-cols-2` / `grid-cols-3` / `grid-cols-12`                    |
| Grid Aralık    | `gap-x-4` / `gap-y-2`                                                  |
| Col Span       | `col-span-2` / `col-span-3`                                            |

**React Örnek:**
<div className="flex flex-wrap justify-center items-center gap-4">
  <Card /> <Card /> <Card />
</div>

```jsx
<div className="flex flex-wrap justify-center items-center gap-4">
  <Card /> <Card /> <Card />
</div>

<div className="grid grid-cols-3 gap-4">
  <Card /> <Card /> <Card />
</div>
```


---

## 7. Display & Position

| Özellik                     | Class / Örnek                                                |
| --------------------------- | ------------------------------------------------------------ |
| Display                     | `block` / `inline-block` / `inline` / `hidden` / `invisible` |
| Position                    | `relative` / `absolute` / `fixed` / `sticky`                 |
| Z-index                     | `z-0` / `z-10` / `z-50` / `-z-10`                            |
| Top / Right / Bottom / Left | `top-0` / `left-4` / `bottom-2`                              |
| Responsive                  | `md:relative lg:absolute`                                    |

**React Örnek:**
```jsx
<div className="relative md:absolute top-4 left-4 z-10">
  Overlay içerik
</div>
```

---

## 8. Transition & Animation

| Özellik           | Class / Örnek                                                        |
| ----------------- | -------------------------------------------------------------------- |
| Transition        | `transition` / `transition-all`                                      |
| Duration          | `duration-200` / `duration-500`                                      |
| Easing            | `ease-in` / `ease-out` / `ease-in-out`                               |
| Scale / Transform | `transform` / `hover:scale-105`                                      |
| Ready Animations  | `animate-bounce` / `animate-pulse` / `animate-spin` / `animate-ping` |

**React Örnek:**

```jsx
<button className="bg-blue-500 text-white p-2 rounded transition-transform duration-300 hover:scale-105">
  Hover Buton
</button>
```

## 9. Responsive

- Mobile-first: küçük ekranda default → büyük ekranlarda `sm:`, `md:`, `lg:`

**Örnekler**
```jsx
<div className="text-sm md:text-lg lg:text-xl p-2 md:p-4 lg:p-6">
  Responsive Metin ve Padding
</div>

<div className="w-full md:w-1/2 lg:w-1/3">
  Responsive Box
</div>
```

## 10. Dark Mode

| Özellik       | Class / Örnek            |
| ------------- | ------------------------ |
| Background    | `dark:bg-gray-800`       |
| Text Color    | `dark:text-white`        |
| Border Color  | `dark:border-gray-600`   |
| Hover / Focus | `dark:hover:bg-gray-700` |

**React Örnek:**
```jsx
<div className="bg-white dark:bg-gray-800 text-gray-800 dark:text-white p-4 rounded">
  Dark Mode destekli kutu
</div>
```

---

## 11. Tailwind vs Bootstrap 

| Özellik              | Tailwind                                   | Bootstrap                                               |
| -------------------- | ------------------------------------------ | ------------------------------------------------------- |
| **Text rengi**       | `text-red-500` / `text-[#f8f1f0]`          | `text-danger`                                           |
| **Background rengi** | `bg-blue-500` / `bg-[#f8f1f0]`             | `bg-primary`                                            |
| **Font boyutu**      | `text-sm` / `text-lg` / `text-xl`          | `fs-6` / `fs-5` / `fs-4`                                |
| **Font kalınlığı**   | `font-light` / `font-bold`                 | `fw-light` / `fw-bold`                                  |
| **Text hizalama**    | `text-left` / `text-center` / `text-right` | `text-start` / `text-center` / `text-end`               |
| **Margin**           | `m-4` / `mt-2` / `mx-8`                    | `m-3` / `mt-2` / `mx-5`                                 |
| **Padding**          | `p-4` / `pt-2` / `px-6`                    | `p-3` / `pt-2` / `px-5`                                 |
| **Width / Height**   | `w-64` / `w-full` / `h-40`                 | `w-25` / `w-50` / `w-100` / `h-50`                      |
| **Border**           | `border` / `border-2` / `border-red-500`   | `border` / `border-0` / `border-primary`                |
| **Border Radius**    | `rounded` / `rounded-lg` / `rounded-full`  | `rounded` / `rounded-0` / `rounded-circle`              |
| **Shadow**           | `shadow-sm` / `shadow-lg`                  | `shadow-sm` / `shadow-lg`                               |
| **Flex**             | `flex justify-center items-center gap-4`   | `d-flex justify-content-center align-items-center`      |
| **Grid**             | `grid grid-cols-3 gap-4`                   | `row` + `col-4`                                         |
| **Display**          | `block` / `inline-block` / `hidden`        | `d-block` / `d-inline-block` / `d-none`                 |
| **Position**         | `relative` / `absolute` / `fixed`          | `position-relative` / `position-absolute` / `fixed-top` |
| **Responsive**       | `sm:` / `md:` / `lg:` / `xl:` / `2xl:`     | `col-sm-6` / `col-lg-4`                                 |



