# javaquestions
//leap year
import java.util.*;
public class FirstProgram{
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int year=sc.nextInt();
        if(year%4==0){
            System.out.println("Leap year");
        }
        else{
            System.out.println("Not leap year");
        }
    }
}
