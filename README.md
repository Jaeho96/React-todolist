## [React로 Todolist 만들기]

---

컴포넌트 정리

1. TodoTemplate

```
이 컴포넌트는 Todolist의 레이아웃을 설정하는 컴포넌트입니다.
페이지의 중앙에 그림자가 적용된 흰색 박스를 보여줍니다.
```

2. TodoHead

```
오늘의 날짜와 요일을 보여주고, 앞으로 해야 할 일이 몇개 남았는지 보여줍니다.
```

3. TodoList

```
할 일에 대한 정보가 들어있는 todos 배열을 내장함수 map을 사용하여 여러개의 Todoitem 컴포넌트를 렌더링해줍니다.
```

4. TodoItem

```
각 할일에 대한 정보를 렌더링해주는 컴포넌트입니다. 좌측에 있는 원을 누르면 할 일의 완료 여부를 toggle 할 수 있습니다.
할 일이 완료됐을 땐 좌측에 체크가 나타나고 텍스트의 색상이 연해집니다.
그리고, 마우스를 올리면 휴지통 아이콘이 나타나고 이를 누르면 항목이 삭제됩니다.
```

5. TodoCreate

```
새로운 할 일을 등록할 수 있게 해주는 컴포넌트입니다. TodoTemplate의 하단부에 초록색 원 버특을 렌더링해주고, 
이를 클릭하면 할 일을 입력할 수 있는 폼이 나타납니다. 버튼을 다시 누르면 폼이 사라집니다.
```
|화면|사진|
|--|--|
|화면1||<img width="514" alt="2" src="https://user-images.githubusercontent.com/63542000/108585378-a624a580-738b-11eb-8ca5-bef730c6da58.png">|

<img width="514" alt="2" src="https://user-images.githubusercontent.com/63542000/108585378-a624a580-738b-11eb-8ca5-bef730c6da58.png">

