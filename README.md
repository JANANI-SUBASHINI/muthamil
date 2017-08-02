# muthamil
import java.io.*;
import java.util.*;
public class Vowels
{
  public static void main(String args[])
  {
    Scanner s=new Scanner(System.in);
    String str;
    String str1;
    String reverse="";
    System.out.println("Enter the string");
    str=s.nextLine();
    int len=str.length();
    for(int i=len-1;i>-1;i--)
    {
      
      reverse=reverse+str.charAt(i);
    }
    System.out.println("The reversed String is: "+reverse);
    str1=str.replaceAll("[aeiouAEIOU]","");
    
    System.out.println("The String after removing vowels : "+str1);
  }
}
