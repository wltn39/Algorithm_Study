[문제출처 : 프로그래머스](https://programmers.co.kr/)

### 문제소개 

파이썬을 파이썬답게 입문테스트
- 각 원소의 길이를 담은 리스트를 리턴하도록 solution 함수를 작성해주세요.

input        | output  |
:-------------------------:|:-------------------------:  
[[1], [2]] | [1,1] |
[[1, 2], [3, 4], [5]] | [2,2,1] |

### 내가 푼 코드


```python
mylist = [[1, 2], [3, 4], [5]]
```


```python
def solution(mylist):
    answer = []
    for i in mylist: 
        answer.append(len(i))    
        
    return answer

solution(mylist)
```




    [2, 2, 1]



### 코드 해설

- 딱 내가 짠 코드대로 했다면 이 강의를 수강해야한다고 말씀해주심.. ㄷㄷ
- 내가 푼 코드는 C 언어나 자바에 가까운 코드


```python
def solution(mylist):
    return list(map(len, mylist))
```
