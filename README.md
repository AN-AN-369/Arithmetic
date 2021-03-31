# Arithmetic

1.#冒泡排序
  x=[6,2,5,3,1]
  n=len(x)
  for i in range(n-1):
      for j in range(n-1-i):
          if x[j]>x[j+1]:
              x[j],x[j+1]=x[j+1],x[j]
  print(x)
