# gitaction-tutorial

git action을 이용해 nodejs서버 ci/cd 구축 tutorial

### work flow

1. master branch에 pr이 온다.
2. test를 돌린다.
   - sucess
     - 다음 step으로 간다.
   - fail
     - pr을 closed 상태로 변경한다.
