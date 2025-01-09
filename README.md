# Student_Grade_Calculator
# CodeSoft
program of Student grade Calculator 
import java.util.Scanner;
public class grade_calculator{
    public static void main(String args []){
        Scanner Sc=new Scanner(System.in);
        System.out.println("Enter physics marks : ");
        int phy=Sc.nextInt();
        System.out.println("Enter chemistry marks : ");
        int chem=Sc.nextInt();
        System.out.println("Enter maths marks : ");
        int math=Sc.nextInt();
        System.out.println("Enter biology marks : ");
        int bio=Sc.nextInt();
        System.out.println("Enter history marks : ");
        int hist=Sc.nextInt();
        int total= ((phy+chem+math+bio+hist)*100)/500;
        System.out.println("total average percentage is = "+total+"%");
        if(total==35){
            System.out.println("grade = c");
        }else if(total>=35 && total<=50){
            System.out.println("grade =b");
        }else if(total>=50 && total<85){
            System.out.println("grade = A");
        }else{
            System.out.println("grade A++");
        }
    }
}
