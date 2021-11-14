# Responsive_web

[드림 코딩 엘리 포트폴리오 웹](https://academy.dream-coding.com/courses/portfolio) 듣고 제작한 [이달의 소녀](https://namu.wiki/w/%EC%9D%B4%EB%8B%AC%EC%9D%98%20%EC%86%8C%EB%85%80) 소개 홈페이지
#### 사용 언어 : <br>

<table>
  <tr>
    <td align="left"><img src="https://img.shields.io/badge/-HTML5-313131?style=flat-square&labelColor=313131&logo=html5&logoColor=white&color=313131" width="100px" alt=""/></a>   </td>
    <td align="left"><img src="https://img.shields.io/badge/-CSS3-313131?style=flat-square&labelColor=313131&logo=css3&logoColor=white&color=313131" width="100px" alt=""/></a></td>
     <td align="left"><img src="https://img.shields.io/badge/-Javascript-313131?style=flat-square&labelColor=313131&logo=javascript&logoColor=white&color=313131" width="100px" alt=""/></a></td>
  </tr>
</table>

## 1 : CSS Concept

`box sizing`

- border box : padding + border (content도 그만큼 작아짐)
- content box : padding (content는 크기 변경 없음)

`Position`

- static : default (top, left 등 지정해도 적용 X)
- relative : 원래 있던 자리 기준 top, left 등 지정한 만큼 이동
- absolute : 근접한 부모 중에 static이 아닌 부모를 기준으로 top, left 등 지정한만큼 이동

`:root`
- color, font-size, font-weight, size-border-radius, animation-duration에 대한 Global한 soft-coding 처리

`Universal tags`
- *, body, a, ul, li, button에 default인 decoration, padding, margin, list-style 제거

`Typography`
- h1, h2, h3, p에 font-size, font-weight, color, margin 설정해 CSS에 일관된 타이포 적용



## 2 : Navbar

|Top|Scroll|
|------|---|
|![navbar](https://user-images.githubusercontent.com/67853616/131960748-fc0e8a90-b0a4-446b-ae0e-ff1055887fa8.png)|![navbar__scroll](https://user-images.githubusercontent.com/67853616/131961065-3a48ff24-e847-4037-9a00-d7ede4016933.png)|
|Navbar가 상단에 위치하는 경우 뒤에 대문 이미지를 가리지 않도록 투명 처리|scroll 하면 해당 classname에 navbar--dark를 추가하여 불투명해지는 CSS가 적용되도록 함|


|default|Toogle down|
|------|---|
|![navbar__mini](https://user-images.githubusercontent.com/67853616/131961468-1c7c3f97-bf6d-42d3-a7c9-19366afd0afc.png)|![navbar__toogle](https://user-images.githubusercontent.com/67853616/131962058-bb21d37a-38df-4cc3-88d6-e65e2df9deae.png)|
|작은 화면에서는 언제나 Navbar가 불투명하게 설정|햄버거 버튼 누르면 토글이 내려오도록 구현|


|Section Enter 1 |Section Enter 2|
|------|---|
|![Section__enter_1](https://user-images.githubusercontent.com/67853616/131962378-9bda65b4-365c-47c2-8cc5-7cb051ab4365.png)|![Section_enter_2](https://user-images.githubusercontent.com/67853616/131963024-643581e9-93f6-4552-bc3c-3a221639b4ae.png)|
|Scroll down해서 Member section에 진입하면 해당 메뉴 활성화|Scroll up해서 Album Section에 진입한 경우 해당 메뉴 활성화|




![Section__hover](https://user-images.githubusercontent.com/67853616/131962720-14ce2687-382a-4bef-9fd1-3aa1a49fee53.png)
> navbar에서 보고 싶은 section 칸에 Hover 하는 경우 칸에 진분홍 배경 CSS 적용됨



![Section__click](https://user-images.githubusercontent.com/67853616/131964038-cba67a6f-1acd-4d87-97b9-d89f30980535.png)
> navbar에서 보고 싶은 section 칸에 Click 하는 경우 해당 Section으로 scroll 이동됨

## 3 : About

|Wide View |Small View|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131964323-c88c4f87-610f-4fc3-b97b-43167b7a8926.png)|![image](https://user-images.githubusercontent.com/67853616/131964370-7a628c8d-72f2-4a89-8fed-088949632549.png)|


|Default|Animation|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131964753-8aed86b6-77e6-48b1-bd5d-f4fe15b2515d.png)|![image](https://user-images.githubusercontent.com/67853616/131964814-c408841c-6295-451a-a23c-53526be70895.png)|


## 4 : Members
|ALL|Filtering|
|--|--|
|![image](https://user-images.githubusercontent.com/67853616/131965027-73a97cb7-fdc4-4128-8c73-45f9c3b7d423.png)|![image](https://user-images.githubusercontent.com/67853616/131965257-9a3caa68-34d1-4216-af6e-fa9448934a28.png)|

|ALL|Filtering|
|--|--|
|![image](https://user-images.githubusercontent.com/67853616/131965027-73a97cb7-fdc4-4128-8c73-45f9c3b7d423.png)|![image](https://user-images.githubusercontent.com/67853616/131965440-098d2258-d388-448b-a0c3-e4224d466811.png)|


## 5 : Photos
|Wide View |Small View|
|--|--|
|![image](https://user-images.githubusercontent.com/67853616/131965667-78815a39-7900-43ba-ab01-2b38e055c61a.png)|![image](https://user-images.githubusercontent.com/67853616/131965799-68ff0858-e0cc-4abe-b390-e260e45f3c44.png)|

|마지막 사진|마지막에서 다음 눌러<br> 첫번째로|첫번째에서 이전 눌러<br> 마지막으로|
|--|--|--|
|![마지막 사진](https://user-images.githubusercontent.com/67853616/131965843-29ce0d53-fbf8-4849-9c0a-f78e5f14e11d.png)|![첫번째 사진](https://user-images.githubusercontent.com/67853616/131965931-2298a95c-609d-4143-98b2-7fe9b12866f0.png)|![마지막 사진](https://user-images.githubusercontent.com/67853616/131965843-29ce0d53-fbf8-4849-9c0a-f78e5f14e11d.png)


|Wide View |Small View|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131966489-419a21ba-f1e9-4d71-8592-f821b80345cf.png)|![image](https://user-images.githubusercontent.com/67853616/131966639-f756a68b-a22a-4e80-b5ca-9961e3f92ed5.png)|

## 6 : Talks
|Wide View |Small View|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131966858-4222686d-9bef-4460-9dd9-9ec2758ba867.png)|![image](https://user-images.githubusercontent.com/67853616/131966815-dd92516c-1e45-488c-905a-76b0796ef81c.png)|

## 7 : Contact
|Wide View |Small View|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131967044-b76ff970-8d78-491a-bd50-1cdab003c5d0.png)|![image](https://user-images.githubusercontent.com/67853616/131967105-608e0c76-6e72-4746-9be6-2ff24b3519d3.png)|

|트위터 아이콘 Hover|브라우저 아이콘 Hover|
|------|---|
|![image](https://user-images.githubusercontent.com/67853616/131967290-e2732209-38fd-4809-8a8d-6a7fdd0df18f.png)|![image](https://user-images.githubusercontent.com/67853616/131967339-46460a59-7d7b-42b5-b0e7-b3b08c80b412.png)|
|해당 아이콘 클릭시 [공식 트위터 계정](https://twitter.com/loonatheworld)으로 이동|해당 아이콘 클릭시 [공식 사이트](http://www.loonatheworld.com/)로 이동|
## 8 : Arrow - up
|Default|Arrow 아이콘<br> Hover|Arrow 아이콘 Click 후<br> 가장 위로 이동
|------|---|--|
|![image](https://user-images.githubusercontent.com/67853616/131967611-27a3d7b3-3a14-4faf-a097-3038ce3bdaa1.png)|![image](https://user-images.githubusercontent.com/67853616/131967563-e39bdbbb-8363-43f6-b47a-09e4df5a3a8d.png)|![image](https://user-images.githubusercontent.com/67853616/131967640-4a0dca92-b3cc-4f50-8159-2b13a215978b.png)|

