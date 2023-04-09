# Arrays-C
An array is defined as the collection of similar type of data items stored at contiguous memory locations. Arrays are the derived data type in C programming language which can store the primitive type of data such as int, char, double, float, etc. It also has the capability to store the collection of derived data types, such as pointers, structure, etc.
Array is beneficial if you have to store similar elements. For example, if we want to store the marks of a student in 6 subjects, then we don't need to define different variables for the marks in the different subject. Instead of that, we can define an array which can store the marks in each subject at the contiguous memory locations.
In  Array whatever size, we define at the time of declaration of the array, we can't exceed the limit. So, it doesn't grow the size dynamically like LinkedList.

We can declare an array in the c language in the following way:
data_type array_name[array_size];  
For example:-
int marks[5];  
Here, int is the data_type, marks are the array_name, and 5 is the array_size.

![c-array-declaration](https://user-images.githubusercontent.com/125913981/230794152-aa1f6d6d-80e5-4d3b-b941-7a76f2350748.png)

One thing to note is that the indexing in the array always starts with 0, i.e., the first element is at index 0 and the last element is at N – 1 where N is the number of elements in the array.
For example:

int arr[6] = {7,8,0,2,5,4};
The above array is an integer array that consists of 6 elements. The elements are indexed from 0 through 5, so to retrieve the 32rd element of arr, the following code will have to be used:

printf("%d", arr[1]);

RESULT:
![image](https://user-images.githubusercontent.com/125913981/230794619-916cb106-fa68-4ea9-addb-0ee9f1111cee.png)
