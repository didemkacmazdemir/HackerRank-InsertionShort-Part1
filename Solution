import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Solution {

    // Complete the insertionSort1 function below.
    static void insertionSort1(int n, int[] arr) {

            int temp = arr[n-1];
            for(int i = n-1; i > 0; i--){
                if(arr[i-1] > temp){
                    arr[i] = arr[i-1];
                    printArr(arr);
                }else if(arr[i-1] < temp){
                    arr[i] = temp;
                    printArr(arr);
                    return;
                }
            }
            if(arr[0] > temp){
                arr[0] = temp;
                printArr(arr);
            }
    }
        static void printArr(int[] arr){
            for(int i : arr){
                System.out.print(i);
                System.out.print(" ");
            }
            System.out.println(" ");
        }
    private static final Scanner scanner = new Scanner(System.in);

    public static void main(String[] args) {
        int n = scanner.nextInt();
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");

        int[] arr = new int[n];

        String[] arrItems = scanner.nextLine().split(" ");
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");

        for (int i = 0; i < n; i++) {
            int arrItem = Integer.parseInt(arrItems[i]);
            arr[i] = arrItem;
        }

        insertionSort1(n, arr);

        scanner.close();
    }
}
