# lambda로 정렬하기

- 매개변수 x에 10을 더한 값을 반환하는 함수 만들기
    
    ```python
    f = lambda x:x+10
    print(f(10))
    ```
    
    - 코드가 간단해지며, 메모리를 효율적으로 사용할 수 있다.
    
- sorted() 함수
    
    ```python
    # 오름차순 정렬
    sorted(arr, key=lambda x:x[0])
    
    #내림차순 정렬
    sorted(arr, key=lambda x:-x[0])
    ```