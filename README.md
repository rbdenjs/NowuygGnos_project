## POZALabs project 
## __TF-IDF와 Bag of word를 활용한 유사도 검사__

### 0) __Data Set__
![image](https://user-images.githubusercontent.com/108792199/204002628-842b7991-04f3-4dfa-8040-d64766f9b4d1.png)

<br>

### 1) __아이디어 및 방법론__
> + 표절에 대한 판례를 살펴보면 음악저작물은 멜로디,리듬,화성의 3요소로 구성되어 있으며, 이 3요소에 대한 질적, 양적 정도를 감안하여 표절 유무를 판단함. <br><br>
> + 그렇지만 주어진 데이터를 통해 멜로디를 알 수 없으며 주어진 task는 코드 간 진행만을 통해 유사도를 판단하는 것임. <br><br>
> + 따라서 코드 간 진행을 하나의 sequence로 인식하고 NLP의 방법론인 TF-IDF를 적용하고자하며 희소한 코드 간 진행을 찾고 그 진행을 공유하는 두 commu data를 표절이 아닌가 의심하고자함. 

<br>

### 2) __수식 전개__
> + a) Step 1 마디 구분을 없앤 'chord_list' 변수 생성
>    + 코드 1개 당 8분의 1박자로 구분되어 마디수, 박자 구분이 되어있는 기존 'chord_progression' 변수에서 마디 구분을 없앰
![그림1](https://user-images.githubusercontent.com/102268412/204111013-dc9095f3-8163-4e3e-9514-605ff22ee301.jpg)

![그림2](https://user-images.githubusercontent.com/102268412/204111030-5dbb8766-56be-4304-a183-b53f161f3e9d.jpg)

![그림3](https://user-images.githubusercontent.com/102268412/204111059-d0263800-e6d5-4085-8521-8ff631a79ed9.jpg)

![그림4](https://user-images.githubusercontent.com/102268412/204111065-bf365f58-8b05-4281-9149-dc3c7c5b859e.jpg)

![그림5](https://user-images.githubusercontent.com/102268412/204111074-c767e81d-de69-4bf1-abb1-bfbb975d0eaf.jpg)


