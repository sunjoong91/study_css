# 내장방식
<style>
  div{
      color: red;
      margin: 20px;
  }
</style>

# 인라인 방식
- 선택자 없음
- 우선 순위 높음
<div style="color: red; margin:20px;"></div>

# 링크방식
- css문서를 가져와서 연결하는 방식
- 병렬 연결
<link rel="stylesheet" href="./css/main.css">

# @import 방식
- css 문서 안에서 또다른 css 문서를 가져와 연결하는 방식
- 직렬 연결

css 파일내
@import url("./box.css");


