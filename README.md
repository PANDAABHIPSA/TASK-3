# TASK-3
package ass1;
import java.util.Scanner;
public class gradecalculator {

	public static void main(String[] args) {
int marks[]= new int[6];
int i, total=0, avg;
Scanner sc= new Scanner(System.in);

for(i=1;i<6;i++) {
	System.out.println("Enter the mark of subject"+ i );
	marks[i]=sc.nextInt();
	total= marks[i]+ total;
}
avg=total/i;
System.out.println("Grade of the student is:");
if(avg>=80)
{
    System.out.print("A");
}
else if(avg>=60 && avg<80)
{
   System.out.print("B");
} 
else if(avg>=40 && avg<60)
{
    System.out.print("C");
}
else
{
    System.out.print("D");
}
System.out.println("Total marks secured is"+ total);
System.out.println("Average is "+ total/5);
System.out.println("Average% is "+ (avg/5)*100);
}
	
}
