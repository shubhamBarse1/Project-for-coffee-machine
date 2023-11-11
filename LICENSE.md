package Coffee;

import java.util.Scanner;
public class Cofeemachine {

	 Cofeemachine(){
System.out.println("select an coffee out of the following");
System.out.println("garam coffee select 1");
System.out.println("thandi coffee select 2");
System.out.println("medium coffee select 3");

	}
	 void Main2() {
		 for(;;) {
		 Scanner sc=new Scanner(System.in);
		 int SS=sc.nextInt();
		 switch(SS) {
		 case(1):
		Scanner S1=new Scanner(System.in);
		 System.out.println("MRP is 60rs");
		 int s2=S1.nextInt(); 
		 break;
		 
		 case(2):
			 Scanner sc1=new Scanner(System.in);
			 System.out.println("MRP is 90rs");
		 int s3=sc1.nextInt();
		break;
	 
	 case(3):
		 Scanner sc2=new Scanner(System.in);
		 System.out.println("MRP is 90rs");
	 int s4=sc2.nextInt();
	 break;
		 
		 default:
			 System.out.println("you dont have money dont worry you have chaiii....");
		 }
		 }}
		 public static void main(String []args) {
			 Cofeemachine r=new Cofeemachine();
			 r.Main2();
		 
	 }
}
