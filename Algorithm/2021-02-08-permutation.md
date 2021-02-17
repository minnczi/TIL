# 순열 (Permutation)

서로 다른 것들을 뽑아 한 줄로 나열하는 것 (순서 상관 O)

서로 다른 총 n개의 원소 중에서 r개를 택하는 순열은 `nPr`

```
# 서로 다른 n개의 원소중에서 r개를 나열 할 수 있는 unique한 경우의 수
nPr = n * (n-1) * (n-2) ... (n-r+1)

# n개의 원소를 나열하는 경우의 수
nPn = n * (n-1) * (n-2) ... 2 * 1
```
