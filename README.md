# fragile calendar

콘텐츠는 `entries.js` 하나만 수정하면 됩니다.

이미지는 `public/images` 폴더에 넣습니다.

```txt
public/images/2026-06-14_01.jpg
public/images/2026-06-14_02.jpg
```

`entries.js`에 항목을 추가합니다.

```js
globalThis.FRAGILE_ENTRIES = [
  {
    date: "2026-06-14",
    note: "short memo for this day.",
    columns: 1,
    images: [
      "public/images/2026-06-14_01.jpg",
      "public/images/2026-06-14_02.jpg",
    ],
  },
];
```

현재 레이아웃은 모든 이미지를 1열로 보여줍니다.
