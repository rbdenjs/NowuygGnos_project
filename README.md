## POZALabs project 
## __TF-IDF와 Bag of word를 활용한 유사도 검사__

### 1) __아이디어 및 방법론__
> 표절에 대한 판례를 살펴보면 음악저작물은 멜로디,리듬,화성의 3요소로 구성되어 있으며, 이 3요소에 대한 질적, 양적 정도를 감안하여 표절 유무를 판단함. <br><br>
> 그렇지만 주어진 데이터를 통해 멜로디를 알 수 없으며 주어진 task는 코드 간 진행만을 통해 유사도를 판단하는 것임. <br><br>
> 따라서 코드 간 진행을 하나의 sequence로 인식하고 NLP의 방법론인 TF-IDF를 적용하고자함.
>> + 희소한 코드 간 진행을 찾고 그 진행을 공유하는 두 commu data를 표절이 아닌가 의심하고자함. 
