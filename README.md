# AiffelQ1

리뷰어: 김진홍

def palindrome():  # 회문 지정
  word = input()   # 입력 값 넣어주기
  reverse_word = "" # 역으로 출력할 값 지정

  for i in range(1, len(word)+1): # 입력 값 길이 까지
    reverse_word += word[-i] # 값이 같은지 확인 (회문인지)

  print("뒤집힌 단어는: ", reverse_word) # 뒤집힌 단어 출력

  if word == reverse_word: # if 문을 사용하여 회문이 맞다면
    print('입력된 단어는 회문입니다.') # 출력
  else: # 아니라면
    print('입력된 단어는 회문이 아닙니다.')  # 출력
    
- [O] 1.코드가 정상적으로 동작하나요?
- [O] 2.문제를 제대로 이해했나요?
- [O] 3.함수가 작동하는 방식을 잘 설명했나요?
- [O] 4.발생 가능한 에러를 찾아서 디버깅을 했나요?
- [O] 5.코드를 더 개선시켰나요?
