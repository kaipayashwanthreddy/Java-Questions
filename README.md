//   import java.util.Scanner;

// public class main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         System.out.print("Enter an operator (+, -, *, /): ");
//         char ch = sc.next().charAt(0);
//         System.out.print("first number: ");
//         int a = sc.nextInt();
//         System.out.print("second number: ");
//         int b = sc.nextInt();
//         int result = 0;
//         boolean valid = true;
//         switch (ch) {
//             case '+':
//                 result = a + b;
//                 break;
//             case '-':
//                 result = a - b;
//                 break;
//             case '*':
//                 result = a * b;
//                 break;
             
//             case '/':
//                 if (b != 0) {
//                     result = a / b;
//                 } else {
//                     System.err.println("Error: Division by zero");
//                     valid = false;
//                 }
//                 break;
//             default:
//                 System.err.println("Error Invalid operator");
//                 valid = false;
//         }

//         if (valid) {
//             System.out.println("Result: " + result);
//         }

//         sc.close(); 
//     }
// }


// write a program to find that a number is divisible by 5 & 10





// class Main {
//     public static void main(String[] args) {
//         Scanner input = new Scanner(System.in);

//         System.out.print("Enter a number: ");
//         int number = input.nextInt();

//         if (number % 5 == 0 && number % 10 == 0) {
//             System.out.println("true");
//         } else {
//             System.out.println("false");
//         }
//     }
// }

 
//  fourth case :  write a program to find that the given character is a vowel o not input is output is true input is m output is false

//  //class main{
//     public static void main(String[] args) {
//         Scanner input = new Scanner(System.in);

//         System.out.print("Enter a character: ");
//         char ch = input.next().toLowerCase().charAt(0);

//         if (ch == 'a' || ch == 'e'|| ch == 'i' || ch == 'o' || ch == 'u'){
//             System.out.println("true");
//         }else {
//             System.out.println("false");
//         }

//         }

//     }
 

// fifth form : write a program to find the average of the numbers

// public class main
// {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int total = sc.nextInt();
//         int count = sc.nextInt();
//         System.out.println(average(total,count));
//         System.out.println(percentage(total,count));
//     }
//  static float average(int total,int count){

//     float ans = total/count;
//     return ans;
//     }
//  static float percentage(int total,int count){
//      float perc = (total/count*100)*100;
//      return perc;
//     }

// }


// sixth case : write a function to check that a given mo is print or not

// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner input = new Scanner(System.in);

//         System.out.print("Enter a number to check if it's prime: ");
//         int number = input.nextInt();

//         if (isPrime(number)) {
//             System.out.println(number + " is a Prime Number.");
//         } else {
//             System.out.println(number + " is NOT a Prime Number.");
//         }

//         input.close(); // Always good to close the scanner
//     }

//     public static boolean isPrime(int n) {
//         if (n <= 1) return false;
//         if (n == 2) return true;
//         if (n % 2 == 0) return false;

//         for (int i = 3; i <= Math.sqrt(n); i += 2) {
//             if (n % i == 0) return false;
//         }
//         return true;
//     }
// }

//  seventh case :

// write a program to find that a given number is factorial or not


// import java.util.Scanner;

// // public class main {
//     public static void main(String[] args) {
//         Scanner input = new Scanner(System.in);

//         System.out.print("Enter a number: ");
//         int num = input.nextInt();

//         if (isFactorial(num)) {
//             System.out.println(num + " is a factorial of some number.");
//         } else {
//             System.out.println(num + " is NOT a factorial of any number.");
//         }
//     }

//     public static boolean isFactorial(int n) {
//         int fact = 1;
//         int i = 1;

//         while (fact < n) {
//             i++;
//             fact *= i;
//         }
//         return fact == n;
//     }
// }
  

// eight case : write a program to find all the factors of a number and return the count

// import java.util.Scanner;

// public class main {
//     public static void main(String[] args) {
//         Scanner input = new Scanner(System.in);

//         System.out.print("Enter a number: ");
//         int number = input.nextInt();

//         int factorCount = 0;

//         System.out.println("Factors of " + number + " are:");
//         for (int i = 1; i <= number; i++) {
//             if (number % i == 0) {
//                 System.out.print(i + " ");
//                 factorCount++;
//             }
//         }

//         System.out.println("\nTotal number of factors: " + factorCount);
//     }
// }


// ninth case : write a program an input from the use and print all the elements of the array

// import java.util.Scanner;

// public class Main
// {
//     public static void main(String[] args){
//         Scanner sc = new Scanner(System.in);
//         int[] arr = new int[5];
//         for(int i=0;i<arr.length;i++){
//             arr[i] = sc.nextInt();
//         }
//         for(int i=0;i<arr.length;i++){
//             System.out.println(arr[i]);
//         }
//     }
// }

  


//  TENTH CASE : wap to find sum of all the elements of an array

// import java.util.Scanner;
// public class Main
// {
// public static void main(String[] args){
//     Scanner sc = new Scanner(System.in);
//     int[] arr = new int[5];
//     for(int i=0;i<arr.length;i++){
//         arr[i] = sc.nextInt();
//    }
//    int sum = 0;
//    for(int i=0;i<arr.length;i++){
//      sum = sum +arr[i];
//    }
//    System.out.println(sum);
//  }



// Eleventh case : wap to find the max element in an array
  

// import java.util.Scanner;

// public class Main{
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int[] arr = {1,2,3,4,5};
//         int min = arr[0];
//         for (int i = 1; i < arr.length; i++) {
//             if (arr[i] < min){
//                 min = arr[i];
//         }
//         for (int i = 1; i < arr.length; i++) {
//             if (arr[i] > min) {
//                 min = arr[i];
//             }
//         }
//         System.out.println(min);
//     }
// }  
// } 


//  twovalth case :  wap to the find the second max element in the array
   

// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         // Input array size
//         System.out.print("Enter the number of elements in the array: ");
//         int n = sc.nextInt();

//         if (n < 2) {
//             System.out.println("Array must contain at least two elements.");
//             return;
//         }

//         int[] arr = new int[n];

//         // Input elements
//         System.out.println("Enter the elements:");
//         for (int i = 0; i < n; i++) {
//             arr[i] = sc.nextInt();
//         }

//         int max = Integer.MIN_VALUE;
//         int secondMax = Integer.MIN_VALUE;

//         // Find max and second max
//         for (int i = 0; i < n; i++) {
//             if (arr[i] > max) {
//                 secondMax = max;
//                 max = arr[i];
//             } else if (arr[i] > secondMax && arr[i] != max) {
//                 secondMax = arr[i];
//             }
//         }

//         if (secondMax == Integer.MIN_VALUE) {
//             System.out.println("There is no second maximum element (all elements might be the same).");
//         } else {
//             System.out.println("The second maximum element is: " + secondMax);
//         }
//     }
// }



//  thirteenth case : wap to find the second min element in ana array

// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         // Input array size
//         System.out.print("Enter the number of elements in the array: ");
//         int n = sc.nextInt();

//         if (n < 2) {
//             System.out.println("Array must contain at least two elements.");
//             return;
//         }

//         int[] arr = new int[n];

//         // Input elements
//         System.out.println("Enter the elements:");
//         for (int i = 0; i < n; i++) {
//             arr[i] = sc.nextInt();
//         }

//         int min = Integer.MAX_VALUE;
//         int secondMin = Integer.MAX_VALUE;

//         // Find max and second max
//         for (int i = 0; i < n; i++) {
//             if (arr[i] > min) {
//                 secondMin = min;
//                 min = arr[i];
//             } else if (arr[i] > secondMin && arr[i] != min) {
//                 secondMin = arr[i];
//             }
//         }

//         if (secondMin  == Integer.MIN_VALUE) {
//             System.out.println("There is no second maximum element (all elements might be the same).");
//         } else {
//             System.out.println("The second maximum element is: " + secondMin);
//         }
//     }
// }


//  fourthenth case : write a program to find that the array contains duplicate or not


// import java.util.HashSet;
// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         // Input array size
//         System.out.print("Enter the number of elements in the array: ");
//         int n = sc.nextInt();

//         int[] arr = new int[n];

//         // Input elements
//         System.out.println("Enter the elements:");
//         for (int i = 0; i < n; i++) {
//             arr[i] = sc.nextInt();
//         }

//         // Use a HashSet to track unique elements
//         HashSet<Integer> seen = new HashSet<>();
//         boolean hasDuplicate = false;

//         for (int i = 0; i < n; i++) {
//             if (seen.contains(arr[i])) {
//                 hasDuplicate = true;
//                 break;
//             } else {
//                 seen.add(arr[i]);
//             }
//         }

//         // Output result
//         if (hasDuplicate) {
//             System.out.println("The array contains duplicate elements.");
//         } else {
//             System.out.println("The array does not contain any duplicate elements.");
//         }
//     }
// }


// fifteenth case :  
  

// public class Main {
//     public static void main(String[] args) {
//         int[] arr = {2,9,1,14,10,15,4};
//         int n= arr.length;
//         int even=0;
//         int odd=0;
//         for(int i=0;i<n;i++){
//             if(arr[i]%2==0){
//                 even++;
//             }else{
//                 odd++;
//             }    
//         }


//         System.out.println("even:"+ even);
        

//  sixteenth case : write a program to find the prime factors in 0(5n) 


// public class Main {
//     public static void primeFactors(int n) {
//         while (n % 2 == 0) {
//             System.out.print(2 + " ");
//             n /= 2;
//         }
//         for (int i = 3; i <= Math.sqrt(n); i += 2) {
//             while (n % i == 0) {
//                 System.out.print(i + " ");
//                 n /= i;
//             }
//         }
//         if (n > 2) System.out.print(n);
//     }

//     public static void main(String[] args) {
//         int n = 90;
//         primeFactors(n);
//     }
// }


//   seventeenth case :  find that the elements of array is unique


// import java.util.*;

// public class Main {
//     public static boolean areElementsUnique(int[] arr) {
//         Set<Integer> set = new HashSet<>();
//         for (int num : arr) {
//             if (!set.add(num)) return false;  
//         }
//         return true;  
//     }

//     public static void main(String[] args) {
//         int[] arr = {1, 2, 3, 4, 5};
//         System.out.println(areElementsUnique(arr));  
//     }
// }


//    eighteenth case : wap to reverse a string 


// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         System.out.print("Enter a string: ");
//         String original = sc.nextLine();

//         String reversed = "";
//         for (int i = original.length() - 1; i >= 0; i--) {
//             reversed += original.charAt(i);
//         }

//         System.out.println("Reversed string: " + reversed);
        
//         sc.close();
//     }
// }



//  ninetenth case : wap to check that given string in palindrome
 

// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);

//         System.out.print("Enter a string: ");
//         String original = scanner.nextLine();
//         String cleaned = original.replaceAll("[^a-zA-Z0-9]", "").toLowerCase();

//         String reversed = "";
//         for (int i = cleaned.length() - 1; i >= 0; i--) {
//             reversed += cleaned.charAt(i);
//         }
//         if (cleaned.equals(reversed)) {
//             System.out.println("The string is a palindrome.");
//         } else {
//             System.out.println("The string is NOT a palindrome.");
//         }

//         scanner.close();
//     }
// }



// twenteenth case : wap to check the no of vowels in a string



// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);

//         System.out.print("Enter a string: ");
//         String input = scanner.nextLine();

//         input = input.toLowerCase();

//         int vowelCount = 0;

//         for (int i = 0; i < input.length(); i++) {
//             char ch = input.charAt(i);
//             if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
//                 vowelCount++;
//             }
//         }
//         System.out.println("Number of vowels: " + vowelCount);
//         scanner.close();
//     }
// }


//  twentyone case : wap to court the frequency of a character


// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         // Scanner to read input
//         Scanner scanner = new Scanner(System.in);

//         System.out.print("Enter a string: ");
//         String input = scanner.nextLine();

//         System.out.print("Enter the character to count: ");
//         char target = scanner.next().charAt(0);

//         // Convert both input string and character to lowercase (optional)
//         input = input.toLowerCase();
//         target = Character.toLowerCase(target);

//         int count = 0;

//         // Count frequency
//         for (int i = 0; i < input.length(); i++) {
//             if (input.charAt(i) == target) {
//                 count++;
//             }
//         }

//         System.out.println("Frequency of '" + target + "' = " + count);

//         scanner.close();
//     }
// }


//  twentytwo case : wap to compare two strings without using equals method


// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);

//         // Read two strings from user
//         System.out.print("Enter first string: ");
//         String str1 = scanner.nextLine();

//         System.out.print("Enter second string: ");
//         String str2 = scanner.nextLine();

//         boolean areEqual = true;

//         // Check if lengths are equal
//         if (str1.length() != str2.length()) {
//             areEqual = false;
//         } else {
//             // Compare each character one by one
//             for (int i = 0; i < str1.length(); i++) {
//                 if (str1.charAt(i) != str2.charAt(i)) {
//                     areEqual = false;
//                     break;
//                 }
//             }
//         }

//         // Print result
//         if (areEqual) {
//             System.out.println("Strings are equal.");
//         } else {
//             System.out.println("Strings are NOT equal.");
//         }

//         scanner.close();
//     }
// }


// twentythree case : wap toi remove spaces in the given string



// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);

//         // Input string
//         System.out.print("Enter a string: ");
//         String input = scanner.nextLine();

//         // Remove all spaces using replaceAll
//         String result = input.replaceAll(" ", "");

//         System.out.println("String without spaces: " + result);

//         scanner.close();
//     }
// }

 
//  twentyfourth case : write a program tp count the frequency of target element


// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         System.out.print("Enter the number of elements in the array: ");
//         int n = sc.nextInt();

//         int[] array = new int[n];
//         System.out.println("Enter " + n + " elements:");
//         for(int i = 0; i < n; i++) {
//             array[i] = sc.nextInt();
//         }

//         System.out.print("Enter the target element: ");
//         int target = sc.nextInt();

//         int count = 0;
//         for(int num : array) {
//             if(num == target) {
//                 count++;
//             }
//         }

//         System.out.println("Frequency of " + target + " is: " + count);
//     }
// }



//  twentyfive case : write a program to find that array contains duplicates or not 



// import java.util.HashSet;
// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         System.out.print("Enter number of elements in the array: ");
//         int n = sc.nextInt();

//         int[] array = new int[n];
//         System.out.println("Enter " + n + " elements:");
//         for(int i = 0; i < n; i++) {
//             array[i] = sc.nextInt();
//         }

//         boolean hasDuplicate = false;
//         HashSet<Integer> seen = new HashSet<>();
//         for(int num : array) {
//             if(seen.contains(num)) {
//                 hasDuplicate = true;
//                 break;
//             }
//             seen.add(num);
//         }

//         if(hasDuplicate) {
//             System.out.println("The array contains duplicates.");
//         } else {
//             System.out.println("The array does not contain duplicates.");
//         }
//     }
// }



//  twentysix case : write a program to find the indorea of two elememts , whole sum is equals to target



// import java.util.HashMap;
// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);

//         System.out.print("Enter number of elements in the array: ");
//         int n = sc.nextInt();

//         int[] nums = new int[n];
//         System.out.println("Enter " + n + " elements:");
//         for (int i = 0; i < n; i++) {
//             nums[i] = sc.nextInt();
//         }

//         System.out.print("Enter the target sum: ");
//         int target = sc.nextInt();

//         HashMap<Integer, Integer> map = new HashMap<>(); 

//         boolean found = false;
//         for (int i = 0; i < nums.length; i++) {
//             int complement = target - nums[i];
//             if (map.containsKey(complement)) {
//                 System.out.println("Indices: " + map.get(complement) + " and " + i);
//                 found = true;
//                 break;
//             }
//             map.put(nums[i], i);
//         }

//         if (!found) {
//             System.out.println("No two elements found whose sum is equal to the target.");
//         }
//     }
// }


// twentyseveenth case : write a function to compare two strings without using equals and uptochararray();


//  public class Main {

//     public static boolean compareStrings(String str1, String str2) {

//         if (str1 == null && str2 == null) return true;
//         if (str1 == null || str2 == null) return false;
//         if (str1.length() != str2.length()) return false;

//         for (int i = 0; i < str1.length(); i++) {
//             if (str1.charAt(i) != str2.charAt(i)) {
//                 return false;
//             }
//         }

//         return true; 
//     }

//     public static void main(String[] args) {
//         System.out.println(compareStrings("Java", "Java"));    
//         System.out.println(compareStrings("Java", "java"));    
//         System.out.println(compareStrings("Test", "Testing")); 
//         System.out.println(compareStrings(null, null));        
//         System.out.println(compareStrings("abc", null));       
//     }
// }


// twentyeighth case : write a progarm to convert uppercase letters to lowercase letters, using character array ,with no inbuild find out


//   public class Main {

//     public static String toLowerCaseManual(String input) {
//         if (input == null) return null;

//         // Convert string to char array
//         char[] chars = input.toCharArray();

//         for (int i = 0; i < chars.length; i++) {
//             // Check if character is uppercase (ASCII A-Z)
//             if (chars[i] >= 'A' && chars[i] <= 'Z') {
//                 chars[i] = (char) (chars[i] + 32); // Convert to lowercase
//             }
//         }

//         // Construct a new string from the modified char array
//         return new String(chars);
//     }

//     public static void main(String[] args) {
//         String original = "HeLLo WoRLd 123!";
//         String lower = toLowerCaseManual(original);
//         System.out.println("Original: " + original);
//         System.out.println("Lowercase: " + lower);
//     }
// }
  
        

//  twentynine case : write a program to check that how much swapping is required to sort the given array


// import java.util.Arrays;

// public class Main {
//     public static int countSwapsToSort(int[] arr) {
//         int n = arr.length;
//         int[] sortedArr = arr.clone();
//         Arrays.sort(sortedArr);

//         boolean[] visited = new boolean[n];
//         int swaps = 0;

//         for (int i = 0; i < n; i++) {
//             if (visited[i] || arr[i] == sortedArr[i]) {
//                 continue;
//             }

//             int cycleSize = 0;
//             int j = i;

//             while (!visited[j]) {
//                 visited[j] = true;
//                 j = indexOf(sortedArr, arr[j]);
//                 cycleSize++;
//             }

//             if (cycleSize > 1) {
//                 swaps += (cycleSize - 1);
//             }
//         }

//         return swaps;
//     }

//     private static int indexOf(int[] arr, int value) {
//         for (int i = 0; i < arr.length; i++) {
//             if (arr[i] == value) {
//                 return i;
//             }
//         }
//         return -1; // Should never happen
//     }

//     public static void main(String[] args) {
//         int[] arr = {4, 3, 2, 1};
//         System.out.println("Number of swaps required to sort the array: " + countSwapsToSort(arr));
//     }
// }


// thirty case : check that the given string is palindrome or not by using stringbuilder


// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner scanner = new Scanner(System.in);

//         System.out.print("Enter a string: ");
//         String original = scanner.nextLine();
//         String cleaned = original.replaceAll("[^a-zA-Z0-9]", "").toLowerCase();

//         StringBuilder sb = new StringBuilder(cleaned);
//         String reversed = sb.reverse().toString();

//         if (cleaned.equals(reversed)) {
//             System.out.println("The string is a palindrome.");
//         } else {
//             System.out.println("The string is NOT a palindrome.");
//         }

//         scanner.close();
//     }
// }
