# Sorting Algorithm Visualizer

A visualization tool for illustrating and comparing the mechanics and efficiency of various sorting algorithms in real-time. This tool allows you to experiment with different algorithms, adjust the dataset size, and control the sorting speed.

[**Live Demo**](https://himeshsankhala.github.io/SortingAlgorithms/)

## Built With

- **HTML5**
- **SASS**
- **JavaScript**

---

## Sorting Algorithms

This project includes the following sorting algorithms:

- **Quick Sort**  
  Selects a 'pivot' element from the array and partitions other elements into sub-arrays according to whether they are less than or greater than the pivot. Recursively sorts the sub-arrays.

- **Bubble Sort**  
  Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The process repeats until the list is sorted.

- **Insertion Sort**  
  Builds the sorted array one item at a time. While simple, it is less efficient for large datasets compared to more advanced algorithms.

- **Merge Sort**  
  A divide-and-conquer algorithm that splits the array into halves, recursively sorts each half, and then merges them.

- **Selection Sort**  
  Divides the input list into a sorted and an unsorted part. The smallest element in the unsorted part is repeatedly selected and moved to the sorted part.

- **Heap Sort**  
  A hybrid stable sorting algorithm derived from merge sort and insertion sort, designed to perform well on real-world data.

- **Radix Sort**  
  Sorts numbers digit by digit, starting from the least significant to the most significant digit, using counting sort as a subroutine.

- **Bucket Sort**  
  Distributes elements into a number of buckets. Each bucket is sorted individually using a different sorting algorithm.

---

## Features

- Real-time visualization of sorting algorithms.
- Adjustable dataset size (from 1 to 1000 elements).
- Variable sorting speeds (1ms to 1000ms).
- Comparison of algorithm efficiency.

---

## Development

To run the project locally, follow these steps:

1. **Clone the Repository**

   - **HTTPS:**
     ```bash
     git clone https://github.com/HimeshSankhala/SortingAlgorithms.git
     ```

   - **SSH:**
     ```bash
     git clone git@github.com:HimeshSankhala/SortingAlgorithms.git
     ```

2. **Install Dependencies**
   ```bash
   npm install
   ```
3. **Run the Project**
   ```bash
   npm run dev
   ```
4. **Build for Production**
   ```bash
   npm install
   ```

