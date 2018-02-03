# algorithm1
alforithm challenge 1
## 1. ¿Cual es la complejidad de tiempo de la función example()?

```c++
int example(int n)
{
  int count = 0;
  for (int i = n; i > 0; i /= 2)
     for (int j = 0; j < i; j++)
        count += 1;
  return count;
}
```
La complejidad es O(n*Log(n))

## 2. ¿Cual es la complejidad de tiempo de la función example2()?

```c++
void example2(int n, int arr[])
{
    int i = 0, j = 0;
    for(; i < n; ++i)
        while(j < n && arr[i] < arr[j])
            j++;
}
```
La complejidad es O(n^2)

## 3. ¿Cuál es la mejor complejidad de tiempo de bubbleSort?
La complejidad es O(n)
