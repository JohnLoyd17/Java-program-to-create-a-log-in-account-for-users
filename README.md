# Java-program-to-create-a-log-in-account-for-users
This is a java program that check the password and email that is entered by the user if those are true then it will output will be “You have log-in"”



package userLog_in;
import java.util.Scanner;

public class logIn {

  public static void main(String[] args) {
   
   System.out.println("Program to Log-in User");
   System.out.println("");
   
   Scanner input = new Scanner(System.in);
   
   String userName,userPassword,u,p;
   
   System.out.print("Enter New Username:");
   userName = input.nextLine();
   
   System.out.print("Enter New Password:");
   userPassword = input.nextLine();
   
   System.out.println("");
   System.out.println("You just created new account!");
   System.out.println("-------------------------");
   System.out.println("-------------------------");
   
   System.out.println("");
   System.out.println("Please continue to login...");
   System.out.println("");
   System.out.println("");
   
   
   System.out.print("Enter Username:");
   u = input.nextLine();
   
   System.out.print("Enter Password:");
   p = input.nextLine();
   
   
   if( userName.equals(u) && userPassword.equals(p) )
   {
    System.out.println("");
    System.out.println("You have login!");}
   

   else
   {
   System.out.println("");
   System.out.println("Invalid Username or Password");}
   
   
  }
}
