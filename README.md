# 0930 Django 게시판 만들기 페어 프로젝트

## 페어 프로젝트 후기

혼자 하는 것 보다 조금 더 느렸을수도 있지만, 같이 했기에 몰랐던 부분도 배울 수 있었고, 혼자였으면 놓쳤을 작은 실수들도 함께 찾으니 좋았다. 그리고 무엇보다 페어프로젝트를 하면 확실히 더 몰입이 잘 되는 것 같다.

## 게시판 만들기 후기

이론으로만 배울 때 보다 직접 적용해보니 어떤 곳에서 어떻게 함수들을 사용하고, 데이터를 보내야 할지 훨씬 더 배우기 좋았다.

## 프로젝트 둘러보기

### index 페이지

![image-20220930181619289](README.assets/image-20220930181619289.png)

올린 게시글들을 글 번호순으로 조회 할 수 있다. 작성 시간 또한 조회 가능하다.

### create 페이지

![image-20220930181711508](README.assets/image-20220930181711508.png)

글을 작성 할 수 있다. 제목과 내용은 반드시 작성되어야 하며, 작성하지 않을 시 경고문구가 뜨며 제출 되지 않는다.

### detail 페이지

작성한 글의 상세 정보를 확인 할 수 있다. 제목, 글번호, 최종 수정 날짜 등이 표시되며 글을 수정하거나 삭제 할 수 있다.

### update 페이지

작성한 글을 수정 할 수 있다. detail페이지에서 수정 버튼을 누를 시 넘어오며, 작성한 제목과 내용이 그대로 남아있다.

