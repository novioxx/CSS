# 1. 공유 방법은 2가지가 있다.


## 1. clone 같이 쓰기
- clone 으로 쓸 폴더 만들기
- 만든 폴더에서 git bash 실행
-
git bash 에서 
0. git clone http://githeb.com/novioxx/cooptest.git -> code에 주소 복사 붙이기
1. cd 만든파일명/
2. git branch -M lki   <!--main은 합쳐지는 branch라서 나의 brach를 생성한다 예) lki-->
3. git add .
4. git commit -m "파일명" 
5. git push -u origin lki


- 수정한 파일이 있을 때 git 에 동기화 해주는 방법
git bash에서 해야할 일

1. git add .
2. git commit -m "메세지"
3. git push -u origin lki

github에서 해야할 일(main branch에 올리는 방법)
1. pull requests -> New pull requests 클릭
2. comparisons 에서 해당 branch 클릭 (lki)
3. 페이지에 오면 수정된 내용이 보이는 페이지가 있음
    오른쪽 상단에 create pull requests 클릭
4. 메시지 남길 수 있는 페이지/ create pull requests 클릭.
5. merge 체크 검사를 하고 이상이 없으면 
    1. Merge pull request 클릭
    2. confirm merge 클릭

## 2. fork 사용
