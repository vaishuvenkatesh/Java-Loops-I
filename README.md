/*# Java-Loops-I
Task
Given an integer,N , print its first  multiples. Each multiple (where ) should be printed on a new line in the form: N x i = result.
Output Format
Print  lines of output; each line  (where ) contains the  of  in the form:
N x i = result.
Sample Input
2
Sample Output
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
*/

import java.util.Scanner;
public class Main{
    public static void main(String[]args){
        Scanner scan=new Scanner(System.in);
        int N=scan.nextInt();
        
        for(int i=1;i<=10;i++){
            System.out.println(N + " x " + i + " = " + i*N);
           
        }
        
    }
}
