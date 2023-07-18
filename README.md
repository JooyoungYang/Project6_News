# Project6_News

# AIFFEL Campus Online 5th Code Peer Review Templete
- 코더 : 양주영
- 리뷰어 : 김석영


# PRT(PeerReviewTemplate) 
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [O] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
  > 네. 정상적으로 동작한 결과를 모두 확인할 수 있고,
  > 세 가지 평가문항 모두 충족하였습니다.
- [O] 주석을 보고 작성자의 코드가 이해되었나요?
  > 네. Task별 주제와 코드별 주석이 상세히 기재돼 있습니다.
- [O] 코드가 에러를 유발할 가능성이 없나요?
  > 네. 에러를 유발할 가능성이 있는 코드가 없어 보입니다.
- [O] 코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 네. 코드별로 주석처리가 상세히 잘 돼 있으며, 필요한 Task별 코드가 순서대로 상세히 잘 작성돼 있습니다.
- [O] 코드가 간결한가요?
  > 네. 중복되는 코드는 거의 찾기가 힘들고, 필요한 코드들로 작성돼 있습니다.

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
```python
import matplotlib.pyplot as plt

# Rouge 점수 추출
rouge1_precision = scores["rouge1"].mid.fmeasure
rouge1_recall = scores["rouge1"].mid.recall
rouge2_precision = scores["rouge2"].mid.fmeasure
rouge2_recall = scores["rouge2"].mid.recall
rougeL_precision = scores["rougeL"].mid.fmeasure
rougeL_recall = scores["rougeL"].mid.recall

# Rouge-1 그래프
plt.bar(["Precision", "Recall"], [rouge1_precision, rouge1_recall], color=['skyblue', 'lightgreen'])
plt.title("Rouge-1 Precision and Recall")
plt.ylabel("Score")
plt.ylim(0, 1)
plt.show()

# Rouge-2 그래프
plt.bar(["Precision", "Recall"], [rouge2_precision, rouge2_recall], color=['skyblue', 'lightgreen'])
plt.title("Rouge-2 Precision and Recall")
plt.ylabel("Score")
plt.ylim(0, 1)
plt.show()

# Rouge-L 그래프
plt.bar(["Precision", "Recall"], [rougeL_precision, rougeL_recall], color=['skyblue', 'lightgreen'])
plt.title("Rouge-L Precision and Recall")
plt.ylabel("Score")
plt.ylim(0, 1)
plt.show()
```

# 참고 링크 및 코드 개선
```python
학습한 노드 내용의 범위를 넘어서 분석까지 충실히 잘 반영하 코드입니다. 개선 사항에 대한 코멘트는 없습니다.
```
