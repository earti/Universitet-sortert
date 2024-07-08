
> [!abstract] %%Oppsummering%%
> 

> [!warning] %%Begrensninger%%

``` python
i = 1
while i < length(A):
    j = i
    while j > 0 and A[j-1] > A[j]:
        temp = A[j]
        A[j] = A[j-1]
        A[j-1] = temp
        j = j - 1
    i = i + 1
```

> [!info] %%Kjøretid og annen info%%

> [!success] %%Fordeler%%

> [!failure] %%Ulemper%%