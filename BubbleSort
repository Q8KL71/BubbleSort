# BubbleSort
//冒泡排序
//重复走访整个排序队列，一次比较两个相邻的元素
//外循环：循环n-1次
//内循环：循环n-i-1次
//最大时间复杂度O(n)=n^2

#include "stdafx.h"
#define SIZE 10
void BubbleSort(int a[], int n)
{
  int i,j,temp;
  for(i=0;i<n-1;i++)
    for(j=0;j<n-i-1;j++)
      if(a[j]>a[j+1])
      {
        temp = a[j];
        a[j] = a[j+1];
        a[j+1] = temp;
       }
 }
 
 int main()
 {
  int a[SIZE] = {10,9,8,7,6,5,4,3,2,1};
  int i;
  BubbleSort(a,SIZE);
  for(i=0;i<SIZE;i++)
    printf("%d, ",a[i]);
  return 0;
 }
