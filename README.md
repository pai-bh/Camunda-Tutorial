# Camunda-Tutorial
Camunda-Tutorial

참고 영상 : https://www.youtube.com/watch?v=sgcSm7YneTs&list=PLJG25HlmvsOVssaiPmavxv3htN_dXS3BW


### 1. Camunda Platform initializer 실행
- 링크 : https://start.camunda.com/
- 자바 8~15밖에 안되는듯?? 현재 18쓰고있어서 15jdk를 따로 설치해야 할 것 같음
![image](https://user-images.githubusercontent.com/83193687/173275635-8a6973b6-af8b-448d-8046-6ea7c854c563.png)

### 2. zip 파일 열고, pom.xml을 Intelij로 실행
- 코드를 확인 후 main 실행해도 안됨
- 안되는게 당연하다는데, 일단 PASS 
- (#TODO)
- `process.bpmn` 파일이 핵심

### 3. Camunda Modeler 설치
- google 에서 간단하게 설치 가능하다.
- 설치됐다면, Intellj에서 `process.bpmn`을 드래그해서 끌어온다.
![image](https://user-images.githubusercontent.com/83193687/173276944-0d460dbb-9c44-4810-bf64-a16c30582fe7.png)

### 4. 위 그림에서 왼쪽 동그라미를 더블클릭해서 StartEvent 작성
- `Lafayette want to be involved in a Revolutio`
- 라파예르는 프랑스 혁명 중에는 국민위병의 지휘관이라고 한다.

![image](https://user-images.githubusercontent.com/83193687/173277352-c0e1c053-b449-4afb-80c1-6299932f18fe.png)

### 5. 최종적으로 이와 같은 도식도(process.bpmn) 완료
<img width="778" alt="image" src="https://user-images.githubusercontent.com/83193687/173506747-c384ef4c-b413-41bf-8aac-af4e400dcea3.png">

### 5. File => New File => `Form` 클릭 후, 좌측 `Text Field` 드래그해서 필드 생성
