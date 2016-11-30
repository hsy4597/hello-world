# hello-world
java
package 周报第二周涉及到的程序;

public class Max {
    public static void main(String[] args) {
      int i = 5;
      int j = 2;
      int k = max(i, j);
      System.out.println( i + " 和 " + j + " 比较，最大值是：" + k);
   }
 

   public static int max(int i, int j) {
      int result;
      if (i > j)
         result = i;
      else
         result = j;
 
      return result; 
   }
}
