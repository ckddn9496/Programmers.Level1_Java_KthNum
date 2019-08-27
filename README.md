# Programmers.Level1_Java_KthNum
Programmers 정렬 Level1_KthNum

파라미터로 넘겨받은 int[] arrays에 대해 특정 부분을 복사하려고 할때 for문으로 index를 지정해주어 풀어냈지만
Arrays 라이브러리 안의 copyOfRange를 이용하면 쉽게 해결할 수 있었다.
```java
Arrays.copyOfRange(int[] original, int from, int to)
Arrays.copyOf(int[] original, int newLength))
```
### copyOfRange
from 부터 to까지의 인덱스 값을 original 배열에서 복사해 original과 같은 자료형의 배열을 반환한다
### copyOf
original의 길이 newLength의 배열을 반환한다.
original배열 길이 보다 작은 값이 들어오면 첫 인덱스부터 newLength까지의 값들을 복사한 배열을 반환하며,
더 큰 값이 들어오면 original배열을 복사 이후 뒤 0으로 채워진 길이 newLength의 배열을 반환해 준다.
