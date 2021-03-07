# Ilya Ivanov

***

## Contacts:
E-mail: work.ivanov.in@gmail.com
Telegram: @ilyaivanovru
[Vk](https://vk.com/id160078642)

## About me:
My goal is to become a frontend developer.

## Skills:
*Java
*HTML
*CSS
*GIT

## Code examples: 
```
function partition(arr, start, end){
    // Taking the last element as the pivot
    const pivotValue = arr[end];
    let pivotIndex = start; 
    for (let i = start; i < end; i++) {
        if (arr[i] < pivotValue) {
        // Swapping elements
        [arr[i], arr[pivotIndex]] = [arr[pivotIndex], arr[i]];
        // Moving to next element
        pivotIndex++;
        }
    }
    
    // Putting the pivot value in the middle
    [arr[pivotIndex], arr[end]] = [arr[end], arr[pivotIndex]] 
    return pivotIndex;
};
```