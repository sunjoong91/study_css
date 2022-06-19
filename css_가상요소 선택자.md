- 콜론 2개 붙음

# ABC:before
- 선택자 ABC 요소의 내부 앞에 내용을 삽입
- 인라인 요소
- .box::before{
  content : "앞"
}
=> box 클래스 안 요소 내부 앞에 "앞" 이라는 내용을 삽입

# ABC:atfer
- 선택자 ABC 요소의 내부 뒤에 내용을 삽입
- 인라인 요소
- .box::after{
  content : "뒤"
}
=> box 클래스 안 요소 내부 뒤에 "뒤" 이라는 내용을 삽입