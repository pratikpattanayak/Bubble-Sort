# Bubble-Sort
This code will sort any list using a sorting technique called Bubble Sort.





def bubble_sort(a):
    n=len(a)
    for i in range (n):  # For different Passes
        for j in range(0,n-i-1):
            if(a[j]>a[j+1]):
                temp=a[j]
                a[j]=a[j+1]
                a[j+1]=temp
                
a=[2,1,8,3,9,10,6,5,7]   #The array or list  that is to be sorted.
bubble_sort(a)
for i in a:
    print(i)               
                
            
