---
description: 조건부 액션을 만들어보겠습니다.
---

# 조건부 액션 예시

## ① 객관식 문제 맞추기 \(태그값 변경\)

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyO2skDAgFBXZ9gzXn%2F1010.png?alt=media&token=093438d2-0716-407d-9b85-7c5e4fb11557)

#### \[정답이 ①②인 문제 만들기\]

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyP2IaF1sZubQWufUD%2Fimage.png?alt=media&token=a343404e-1cc8-4c4f-8292-0174d38c252a)

#### \(1\) 액션을 실행시킬 투명한 도형의 객체 만들기 

먼저, 문제와 정답표시를 작업창에 배치 한 뒤, 문제 위에 사용자가 클릭할 수 있는 투명한 도형을 만들어 놓습니다. 각 번호에 맞게 레이어 이름을 수정합니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyP9k57gWay5CYBou4%2Fimage.png?alt=media&token=b90c0c0e-d808-48b1-8eee-8cd1a371adff)

#### \(2\) ‘1번클릭’ 레이어에 태그 교체 액션 넣기 

1번 클릭 레이어를 ‘누르기’ 트리거로 액션을 만들어 액션 타입을 ‘태그값 교체’로 선택합니다. from의 사용자 입력 체크박스를 선택해서 값을 ‘1’로 지정합니다. = 1번 클릭 객체를 ‘누르기’했을 때 1번 클릭의 태그값이 ‘1’이 됩니다. 2번 클릭, 3번 클릭 레이어도 ‘누르기’ 트리거로 액션을 만든 뒤, 액션 타입을 ‘태그갑 교체’로 선택해서 2번 클릭의 태그는 ‘2’, 3번 클릭의 태그는 ‘3’으로 변경이 되도록 합니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyPDQjDtf5UF8FgkaY%2Fimage.png?alt=media&token=8f9d81b6-104f-4915-8f84-c6671d9f4ed8)

#### \(3\) 1번 클릭의 태그를 비교하는 조건부 만들기 

1번 클릭과 태그값을 비교하는 조건부를 만듭니다. 1번 클릭 객체의 태그값이 ‘1’과 같을 땐 2번 조건부를 확인하도록 타켓을 2번 조건부를 액션 타켓으로 선택합니다. 1번 클릭 객체의 태그값이 ‘1’이 아닐 땐 오답 표시 그림이 보이도록 액션을 넣습니다. 2번 클릭 객체의 태그값이 ‘2’ 와 비교하는 ‘조건부2’으로 만듭니다. 조건부 1번과 똑같이 2번 클릭 객체의 태그가 ‘2’ 로 같을 경우엔, 3번 조건부을 액션 타켓으로 선택합니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyPGRBieka43WZbirX%2Fimage.png?alt=media&token=2cf44b39-bb9b-4cd0-8aa5-ec17f1906dbd)

3번 클릭 객체의 태그값이 ‘3’일 경우를 비교하는 ‘조건부3‘으로 만듭니다. 3번 클릭 객체의 태그값이 ’3‘으로 같을 경우엔 오답 표시가 보이도록 합니다. ’3‘이 아닐 경우엔 정답 표시가 보이도록 합니다. = 정답은 ①,②번이기 때문에, ③번까지 태그값이 맞는 경우엔 오답표시, 아닐 경우엔 정답 표시가 보이도록 합니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyPL6TKJ4WqrB14VBe%2Fimage.png?alt=media&token=076b857c-046f-4170-ae46-7dd0d55a9cd6)

#### \(4\) 조건부를 실행시킬 객체에 액션 넣기 

마지막으로, 만들어 놓을 조건부 액션을 실행시킬 정답 확인 버튼에 액션을 넣습니다. 트리거를 선택한 뒤 타켓을 1번 조건부로 설정해놓으면, 조건부 안에 조건부가 이어져있기 때문에 정답 확인이 한번에 가능합니다.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LstKT5CJ2oikjE8938t%2F-LsyMtxlYP8HtMVd6l9O%2F-LsyPOVHlYWAHE3o3PkR%2Fimage.png?alt=media&token=454cdc52-edeb-4c34-beba-c9c51dde88f9)

#### \(5\) 미리보기에서 조건부 액션을 확인할 수 있습니다. 

액션 작업을 완료한 뒤, 미리보기에서 액션을 바로 확인할 수 있습니다.

