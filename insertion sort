#include <stdio.h>
void insertionSort(int array[], int size){
int key, j;
for(int i = 1; i<size; i++) {
key = array[i];               
j = i;
while(j > 0 && array[j-1]>key) {
  array[j] = array[j-1];
j--;
}
array[j] = key; 
}
}
int main(){
    int choice;
    int n, arr[100];
    while(1) {
        printf("\n---Insertion sort menu---\n");
        printf("1. Perform insertion sort\n");
        printf("2. exit\n");
        printf("enter your choice: ");
        scanf("%d", &choice);
        if(choice==2){
            printf("exiting insertion sort program.\n");
            break;
        }
        printf("enter number of elements (max 100): ");
        scanf("%d", &n);
        if(n<=0 || n>100){
            printf("invalid size! try again. \n");
            continue;
        }
        printf("enter %d elements: \n", n);
        for(int i=0; i<n; i++){
            scanf("%d", &arr[i]);
        }
        printf("array before sorting: ");
        for(int i = 0; i<n; i++)
        printf("%d ",arr[i]);
        }
        printf("\n");
        insertionSort(arr, n);
        printf("Array after Sorting: ");
        for(int i = 0; i<n; i++)
        printf("%d ", arr[i]);
        printf("\n");
}


output:
---Insertion sort menu---
1. Perform insertion sort
2. exit
enter your choice: 1
enter number of elements (max 100): 5
enter 5 elements: 
25 50 10 5 35
array before sorting: 25 50 10 5 35 
---Insertion sort menu---
1. Perform insertion sort
2. exit
enter your choice: 2
exiting insertion sort program.

Array after Sorting: 5 10 25 35 50
