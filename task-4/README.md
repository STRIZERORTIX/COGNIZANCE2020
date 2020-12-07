# COGNIZANCE2020
---
> ## **_A BASIC README FILE WHICH CONTAINS A C PRGM AND SOME  STUFF_**
---

### **_A BASIC C++ PRGM FOR BUBBLE SORT_**

```C++
#include<iostream.h>
#include<conio.h>
void bubblesort(int a[],int n)
void main()
{
    int A[20],n;
    clrscr();
    cout<<endl<<"ENTER THE NO. OF ELEMENTS:";
    cin>>n;
    cout<<endl<<"ENTER THY ELEMENTS:";
    for(int i=0;i<=n;i++)
    {
        cin>>A[i];
           
     }
     bubblesort(A,n);
     getch();
     }
 void bubblesort(int a[],int n)    
 {
     int temp;
     for(int i=1;i<=n;i++)
     {
         for(int j=0;j<n-i;j++)
         {
             if(a[j]>a[j+1])
             {
                 temp=a[j];
                 a[j]=a[j+1];
                 a[j+1]=temp;
             }
         }
        cout<<endl<<"AFTER PASS:"<<i+1;
        for(int k=0;k<n;k++)
        cout<<a[k]; 
     }
 }
 ```
 #
 >### **_THE ALGORITHM FOR THE ABOVE PRGM_**
 >1. get the number of elements the user wants to insert and get the value for each element and save it in a[].
 >1. initialise the i value used in the for loop to 1 and run the loop till n-1 times
 >1. initialise the j value used in the for loop used for swapping to 1 and run it till n-i times
 >1. initialise a temporary variable to store the elements while swapping
 >1. if a[j+1]>a[j] then swap the elements 
 >1. repeat the above steps till the conditions satisfies
 >1. display the end sorted lisr
 >1. stop
#
## _**ABOUT MYSELF**_
>### **THE NAME'S ABHINANDHAN**
| MY HOBBIES |
|------------|
|listen to english pop|
|code|
|learn new things|
|
#
>### _**TASK STATUS GIVEN FROM COGNIZANCE 2020 BASED ON GIT AND GITHUB**_
>* [x] task 1
>* [x] task 2
>* [x] task 3
>* [X]  task 4(on process/gonna complete)

#
### _**A HYPERLINK TO GOOGLE SEARCH ENGINE**_
>[_**GOOGLE**_](https://www.google.com/ 
"google search")
#
 ### _**DISPLAYIN A BASIC MARKDOWN LANG IMAGE**_
 
 ![BUBBLE SORT EXAMPLE](https://www.productplan.com/uploads/bubble-sort-1024x683-2.png)
 
