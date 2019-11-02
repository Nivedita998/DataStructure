import java.util.Arrays;
import java.util.Scanner;

class LinearSearch {
  public static void main(String[] args) {
System.out.println("Enter Size");

Scanner sc=new Scanner(System.in);
int size=sc.nextInt();
int arr[]=new int[size];
for(int i=0;i<size;i++){
  System.out.println("Element position"+(i+1));
  arr[i]=sc.nextInt();
}
System.out.println("array followed" +Arrays.toString(arr));
System.out.println("enter element for search");
  int search=sc.nextInt();




for(int i=0;i<size;i++){
  if(arr[i]==search){
    System.out.println("search element"+search+"position of seached element"+(i+1));

  }else{
    System.out.println("not found");
    break;
  }
}

  }
}