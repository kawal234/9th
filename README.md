# 9th
#include<iostream>
using namespace std;
// Arrays- data structure store a collection homogeneous of items
// It stores in contiguous memory- means in continous manner
 // Arrays are 0-indexed

// Syntax for Array 
// int main(){
//     int arr[5] = {1,2,3,4,5};
    // printing the array by for loop
    // for(int i=0;i<5;i++){
    //     cout<<arr[i]<<endl;
    // }
    // cout<<sizeof(arr)<<endl;

    // printing a array by while loop
    // int idx =0;
    // while(idx<sizeof(arr)){
    //     cout<<arr[idx]<<endl;
    //     idx++;
    // }

    // taking input of array
//     char vowel[5];
//     for(int i=0;i<5;i++){
//         cin>>vowel[i];
//     }
//     for(int i=0;i<5;i++){
//         cout<<vowel[i]<<endl;
//     }
//     return 0;
// }

// Problem 1 - to print the sun of the array
// int main(){
//     int arr[] = {3,4,5,7,8,9};
//     int size = sizeof(arr)/sizeof(arr[0]);
//     int sum = 0;

//     for(int i=0;i<size;i++){
//         sum+=arr[i];
//     }
//     cout<<sum<<endl;
//     return 0;
// }

// Problem -2 - to find the maximum number of the array

// int main(){
//     int arr[] = {3,4,18,9,11};
//     int max = arr[0];
//     for(int i=1;i<5;i++){
//         if(arr[i]>max){
//             max=arr[i];
//         }
//     }
//     cout<<max<<endl;
//     return 0;
// }

// problem 3 - to do a linear search inthe array

int main(){
    int arr[] = {3,9,18,11,7};
    int key = 3;
    int ans = -1;
    for(int i=0;i<5;i++){
        if(arr[i]==key){
            ans=i+1;
            break;
        }
    }
    cout<<ans<<endl;
    return 0;
}
