1.<태그>써야함
2.가끔 속성넣기도 가능

```html
<a href="">
<img src="주소"> 
```

이런것들이 다 속성
3.태그안에 태그를 중복으로 넣을 수 있다.


css파일의 class는 점찍고 작명한다.
.class{
    이렇게
}

다음처럼 태그명으로도 모든p태그의 스타일에 적용하수도있다.
p {
    text-align: center;
}

#id스타일도 가능하다.

#specail{
    text-allign: center;
}

위의 내용을
 클래스 컬렉터
 태그 컬렉터
 아이디 컬렉터라고한다.

한 태그 컬렉터,아이디 컬렉터,클래스 컬렉터가 겹칠경우
1. id컬렉터
2. 클래스컬렉터
3. 태그 컬렉터 
순으로 우선순위를 지정하여 스타일링이 된다.

테두리가 겹칠땐 
1. margin-collapse가 발생할 수 있다.

position
* 좌표 이동 가능
* 공중에 뜸(다른 요소와 marigin,padding 등에 대한 걱정X)
1. static : 좌표이동X
2. relative : 현 위치 기준
3. fixed : 현 화면 기준
4. absolute: 부모태그가 기준

숙련자일수록 css파일 시작에 쓰는것들이 많음

1. box-sizing:border-box;
- 박스사이즈를 패딩을 포함한 사이즈로 설정
2. body{margin:0px;}
- 기본 마진값을 초기화함
3. normalize.css
- 브라우저간 호환성
