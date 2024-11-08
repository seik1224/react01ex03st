# 인스타그램

public폴더의 이미지, 아이콘을 활용하여
실제 인스타그램을 참고하여 tailwindCSS로 완성해보세요.

VS Code 확장프로그램 : Tailwind CSS IntelliSense 설치하면 tailwindCSS 사용이 더 편해집니다.

---

## 1. Sidebar 만들기

header(좌측 사이드바)를 만드세요.

---

## 2. Card 컴포넌트

우측의 상세페이지는 Card라는 컴포넌트를 반복문으로 만들어 배치하세요.

---

## 3. 데이터 가져오기

데이터에서 내용을 가져오세요.

```bash
const data = [
  {
    id: 1,
    profile: "Mario",
    title: "nintendo product no.1",
    content:
      "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum",
    like: 0,
    comments: [],
  },
  {
    id: 2,
    profile: "Zelda",
    title: "nintendo product no.2",
    content:
      "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum",
    like: 0,
    comments: [],
  },
  {
    id: 3,
    profile: "Pokemon",
    title: "nintendo product no.3",
    content:
      "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum",
    like: 0,
    comments: [],
  },
];
```

---

## 4. 좋아요 처리

하트 클릭시
하트이미지(붉은색) 바뀌고 좋아요 1개

한번 더 누르면
하트이미지(회색) 좋아요 0개
