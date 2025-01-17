# ❓ How Old Are You

# 1. 프로젝트 정보

> ### 프로젝트 소개
- ***" 나의 얼굴 나이는 몇 살일까? "***  
기계가 알려주는 나의 얼굴 나이를 확인해봅시다.

> ### 연관 GitHub
- [Front-end](https://github.com/angar2/HOAY-frontend)

> ### 개발 기간
- 2022.05.18 ~ 2022.05.24

> ### 프로젝트 형태
- 팀 프로젝트(4인)

<br>

# 2. 사용 기술

> Back-end
- Python 3  
- Flask
- Tensorflow  
- pandas 
- numpy  
- mongoDB  

> Front-end
- Javascript
- HTML
- CSS

<br>

# 3. 기획 및 설계
> ### ERD 설계
> 

> ### Mock-up
> ![image](https://user-images.githubusercontent.com/100769423/186613503-ea2c0bf9-3bd1-429c-a87b-0a875d54d79b.png)

<br>

# 4. 핵심 기능
### ❓ 얼굴 나이 측정

<details>
  <summary>기능 설명 펼치기</summary>
  
  ![HOAY](https://user-images.githubusercontent.com/100769423/187427228-8426850c-50a0-484f-9251-b20a3d4e2e62.gif)

  <br>

## 4.1 기능 흐름
  
  <br>
  
> ### 📌 Step 1. 이미지 업로드
- 측정하고자 하는 인물 사진을 업로드 창에 Drag-and-drop합니다.
- 측정 버튼을 클릭해 API 요청을 보냅니다.
  
  <br>
  
> ### 📌 Step 2. 이미지 머신러닝 측정
- 이미지를 서버에 저장한 후 학습된 model을 이용해 결과를 도출합니다.
  
  <br>
  
> ### 📌 Step 3. 데이터 응답 
- 준비가 완료된 데이터로 클라이언트에 응답합니다.

  <br>
</details>


### ✔ 그 외 기능
- 회원가입 및 로그인(소셜)
