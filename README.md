# AiffelQ1

리뷰어: 김진홍

word = str(input("?:")) # 회문 입력
backword = word[::-1] # 역으로 리스트 확인

print(f"출력값 : {word}") # 입력 받은 단어 출력
print(f"뒤집힌 단어는 : {backword}") # 뒤집힌 단어 출력
if word == backword : # if문으로 회문이 맞다면
  print("입력된 단어는 회문입니다.") # 출력
else :  # 아니라면
  print("입력된 단어는 회문이 아닙니다.")  # 출력
  
🔑 **PRT(Peer Review Template)**

- [O]  코드가 정상적으로 동작하나요?
- [O]  문제를 제대로 이해했나요?
- [O]  함수가 작동하는 방식을 잘 설명했나요?
- [O]  발생 가능한 에러를 찾아서 디버깅을 했나요?
- [O]  코드를 더 개선시켰나요?
