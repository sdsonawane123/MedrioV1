# MedrioV1
Clinical trial
package JavaBasic;

public class fibnoci {
	
	
				public static void main(String[] args) {
					
					int a=0;
					int b=1;
					int temp=0;
					
					System.out.print(a + " " + b );
					
					for(int i=0; i<10; i++)
					{
						temp= a+b;
						// 1 2 3
						
						a = b;
						
						b=temp;
						
						System.out.print(" " +temp+ " ");
					}
					
					
				}

}

