# 오작뀨 :: 탄생석 악세사리 주문제작 쇼핑몰

<div>

</div>

<br />

## 1. 서비스 소개

#### 세상에 하나뿐인 추억을 선물할 수 있는 탄생석 악세서리 주문 제작 쇼핑몰입니다.
1. 제품을 탄생석별 / 악세사리 별로 확인 할 수 있습니다 
2. 원하는 문구를 이니셜로 각인할 수 있는 서비스를 제공합니다
3. 회원 가입을 하지 않아도 상품을 구경하고 장바구니에 넣을 수 있습니다.

<br />

### 1-1. 데모 영상




<br />

### 1-2. 페이지 별 화면




## 2. 기술 스택

![image](https://i.ibb.co/N34mXzy/image.png)

<br />

### 2-1. 프론트엔드

- **Vanilla javascript**, html, css (**Bulma css**)
- Font-awesome 
- Daum 도로명 주소 api 

### 2-2. 백엔드 

- **Express** (nodemon, babel-node로 실행됩니다.)
- Mongodb, Mongoose
- cors




## 3. 인프라 구조

![image](https://i.ibb.co/9tGxmx0/image.png)<br />

### 3-1. 폴더 구조
- 프론트: `src/views` 폴더 
- 백: src/views 이외 폴더 전체
- 실행: **프론트, 백 동시에, express로 실행**

<br />

## 4. 제작자

| 이름 | 담당 업무 |
| ------ | ------ |
| 김진영 | 프론트엔드 |
| 이다노 | 프론트엔드 |
| 이유정 | 프론트엔드 |
| 유의석 | 백엔드 |
| 정지헌 | 백엔드 |

<br />

## 5. 실행 방법

1. 레포지토리를 클론하고자 하는 디렉토리에서 아래 명령어를 수행

```bash
git clone https://github.com/eksh7080/o-jak-kku.git
```


2. 클론한 디렉토리에서 backend 디렉토리로 들어가 아래 명령어를 통해 backend에서 필요한 module 설치

```bash
npm install
```


3. backend에서 필요한 `.env` 설정

```bash
MONGODB_URL=<몽고DB URL>
PORT=5000
JWT_SECERT_KEY=<랜덤 문자열>
```

  앱을 테스트하고 싶은 경우 다음의 몽고DB URL을 이용하세요.

  - mongodb+srv://elice:W8RsZsSX2Xs1ydE4@cluster0.4gz9ij3.mongodb.net/?retryWrites=true&w=majority

  단, 해당 URL은 READ만 가능하며 회원 가입을 하거나 상품 정보를 추가하는 등의 동작은 할 수 없습니다. <br>
  주어진 URL은 테스트 용이므로 실제 개발을 할 때는 해당 URL을 사용하지 않고, 반드시 직접 설치한 몽고DB의 URL을 사용하시기를 바랍니다.



4. express 앱을 실행

```bash
npm start
```

<br>

## 6. 버전
### 0.0.1

<br>

## 7. FAQ
<details><summary>1. 배포된 페이지는 어디에서 확인할 수 있나요?</summary>

  <p>
    프로젝트 기본 코드는 따로 배포하지 않았습니다, 레포지토리를 클론하여 직접 실행해보세요.
  </p>

</details>
<details><summary>2. env 파일이 보이지 않습니다.</summary>

  <p>
    해당 파일은 직접 만들어서 코드를 작성해야 합니다, DB를 비롯한 서비스의 계정 정보는 <b>절대로</b> Git에 함부로 공유하면 안되기 때문에 유의 바랍니다.
  </p>

</details>

---

본 프로젝트에서 제공하는 모든 코드 등의는 저작권법에 의해 보호받는 ㈜엘리스의 자산이며, 무단 사용 및 도용, 복제 및 배포를 금합니다.
Copyright 2022 엘리스 Inc. All rights reserved.
