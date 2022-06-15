# air-bnb-cloning

practice html &amp; css

## CSS - position : fixed로 중앙정렬하기<br/>

```css
element {
  position: fixed;
  left: 50%;
  transform: translate(-50%, 0);
}
```

상위 element 기준 좌측에서 우측으로 50% 이,, 다음으로 x축 방향(왼쪽)으로 50% 이동해서 중앙정렬<br/><br/><br/>

## 가로,세로 스크롤바 없애기<br/>

```css
body {
  overflow-x: hidden; /*가로 스크롤바 없애기*/
  overflow-y: hidden; /*세로 스크롤바 없애기*/
}
```

#overflow - 요소 안의 컨텐츠가 너무 커서 다 보여주기 힘들 때, 어떻게 처리할지

- visible : 기본값. 넘치면 컨텐츠가 상자 밖으로 보임 (스크롤박스 X)
- hidden : 넘치는 부분은 잘라버림 (스크롤바X)
- scroll : 스크롤바 추가 (가로,세로 모두 추가)
- auto : 컨텐츠 양에 따라 스크롤바 추가할지 자동으로 결정 (가로,세로 중 필요한 부분만)

가로세로 각각 overflow-x , overflow-y로 제어 가능<br/><br/><br/>

## HTML 특수문자 입력하기<br/>

1. &엔티티 코드(Entity Code) 사용

```css
&period;
&middot;
```

2. &#엔티티 넘버 사용

```css
&#46; /* &period; */
&#183; /* &middot; */
&#8361; /*원화 표시 */
```

<br/><br/><br/>

## 텍스트 사이 간격 설정<br/>

1. 글자 사이 간격 letter-spacing : 단어 사이 간격도 같이 변함
2. 단어 사이 간격 word-spacing : 글자 사이 간격은 변하지 않음
3. 줄간격 line-height

값에 따라 간격 비례. 음수일 경우 겹쳐질 수 있음<br/><br/><br/>
