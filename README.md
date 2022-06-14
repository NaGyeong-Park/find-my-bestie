

   



# 👭사이드 프로젝트 : 단짝 좀 찾아줘👨🏻‍🤝‍👨🏻

   

## 😮What is this?

![image-20220614215126655](README.assets/image-20220614215126655.png)

조 편성과 발표자 선택을 동시에 할 수 있는 HTML파일 한 장의 프로그램입니다.

- 조원을 설정하고 랜덤으로 조를 만들 수 있습니다
- Presenter 버튼을 클릭하여 랜덤으로 발표자를 선출할 수 있습니다  





   

## 📚 STACKS  
<div align=center>
    <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
    <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
    <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
    <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
</div>


  

***
# 📖How to use?
### 1. 결석 학생 학생명단에서 제외시키기  

![image-20220614211332776](README.assets/image-20220614211332776.png)

__두 가지 방법이 있습니다__  

- 결석한 학생의 이름을 클릭
- 검색창에 결석한 학생의 이름을 검색 

다시 활성화 시키고싶으면 그 학생을 클릭하거나 검색하면 활성화됩니다. 교탁 위에 Absent에서 결석한 학생들을 확인할 수 있습니다.

_주의 : 학생을 결석시키면 조가  초기화됩니다!_  

  

### 2. 조 편성하기

![image-20220614211708950](README.assets/image-20220614211708950.png)

`number of people` 검색창에 조원수를 입력하고 Enter를 누르면 랜덤으로 조편성이 됩니다!
LocalStorage에 편성된 조를 저장하였기에 새로고침해도 조가 바뀌지 않습니다.

  

### 3. 발표자 뽑기
![image-20220614212043500](README.assets/image-20220614212043500.png)

`Presenter`버튼을 클릭해 발표자를 랜덤으로 선출합니다.
발표자가 뽑히면 3초동안 🎀핑크색🎀으로 발표자를 가르킵니다.

  

  

​    

***

# 🚧 👷‍♀️⛏개선할 점👷🔧️ 🚧



#### 🎈코멘트와 이슈는 언제든 환영입니다🎈
  
- 결석 학생 또한 LocalStorage에 저장해 불러오기
  - Student List에 비활성화 상태로 만들어야 함
  - Absent 리스트에 보여야함
- 조원이 다른 조에 비해 월등히 적은 경우! : 다른 조 인원을 줄여서 나누기
- 패드보다 작은 사이즈에서는 반응형 view가 형성되지 않는다!

