
# Sorting Algorithms Project

This project contains implementations of various sorting algorithms in Java, as well as a controller class to handle sorting operations. The algorithms included are:

- Bucket Sort
- Heap Sort
- Insertion Sort
- Shell Sort
- Merge Sort
- Quick Sort
- Radix Sort

## Files

1. **BucketSort.java**
   - Contains the implementation of the Bucket Sort algorithm.

2. **HeapSort.java**
   - Contains the implementation of the Heap Sort algorithm.

3. **InsertionSort.java**
   - Contains the implementation of the Insertion Sort algorithm.

4. **ShellSort.java**
   - Contains the implementation of the Shell Sort algorithm.

5. **MergeSort.java**
   - Contains the implementation of the Merge Sort algorithm.

6. **QuickSort.java**
   - Contains the implementation of the Quick Sort algorithm.

7. **RadixSort.java**
   - Contains the implementation of the Radix Sort algorithm.

8. **SortsController.java**
   - Servlet that handles sorting requests and returns the results.

9. **web.xml**
   - Servlet configuration file that maps the `SortsController` servlet to the `/sort` URL pattern.

10. **sort-result.jsp**
    - JSP file for displaying the sort result. It includes a form for user input to specify the array and the sort type, and sections for displaying the sorting result, including the sort type, time taken, input array, and sorted array. The JSP file also includes navigation buttons for previous and next results.

## Usage

1. **Setup**
   - Ensure you have a Java servlet container (e.g., Apache Tomcat) installed and configured.
   - Place the provided files in the appropriate directories within your web application structure.

2. **Running the Application**
   - Deploy the web application to your servlet container.
   - Access the application through your web browser.
   - Enter an array (comma-separated values) and select a sorting algorithm from the dropdown menu.
   - Submit the form to view the sorted array, time taken, and other details.

3. **Navigating Results**
   - Use the "Previous" and "Next" buttons to navigate through the sorting results.
