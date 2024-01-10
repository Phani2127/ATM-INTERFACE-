import java.util.*;
public class ATM
{
    public static void main(String args[])
    {
        int pin=6839;
        int balance=50000;
        int deposit_amount=0;
        int withdrawl_amount=0;
        Scanner sc=new Scanner(System.in);
        System.out.println("welcome to SBI ATM");
        System.out.println("please insert your card");
        System.out.println("***********************");
        while(true)
        {
        System.out.println("State Bank of India");
        System.out.println("select transaction");
        System.out.println("1.Balance eneqery \t\t2.Deposit ");
        System.out.println("3.withdrawl \t\t4.mini statement");
        System.out.println("5.Exit\n");
        int opt=sc.nextInt();
        switch(opt)
        {
            case 1:
                System.out.println("enter pin number");
                int password=sc.nextInt();
                if(password==pin)
                {
                System.out.println("your current balance is:"+balance);
                }
                else{
                    System.out.println("incorrect pin number");
                }
                System.out.println("***********************");
                break;
            case 2:
                System.out.println("enter pin number");
                password=sc.nextInt();
                if(password==pin)
                {
                System.out.println("how much amount did you want to Deposit to your account");
                deposit_amount=sc.nextInt();
                System.out.println("Successfully credited");
                balance=deposit_amount+balance;
                }
                else{
                    System.out.println("incorrect pin number");
                }
                System.out.println("***********************");
                break;
            case 3:
                System.out.println("enter pin number");
                password=sc.nextInt();
                if(password==pin)
                {
                System.out.println("how much of amount is you withdraw:");
                withdrawl_amount=sc.nextInt();
                if(withdrawl_amount>balance)
                {
                    System.out.println("your balance is insufficient");
                    System.out.println("try lessthan your available balance");
                }
                else
                {
                    System.out.println("successfully withdraw");
                    balance=balance-withdrawl_amount;
                }
                }
                else{
                    System.out.println("incorrect pin number");
                }
                System.out.println("***********************");
                break; 
            case 4:
                System.out.println("enter pin number");
                password=sc.nextInt();
                if(password==pin)
                {
                System.out.println("welcome to all in one mini ATM");
                System.out.println("Available Balance:"+balance);
                System.out.println("Amount deposited"+deposit_amount);
                System.out.println("withdrawl amount:"+withdrawl_amount);
                System.out.println("Thanks for visiting ATM");
                }
                else{
                    System.out.println("incorrect pin number");
                }
                System.out.println("***********************");
                break;
            default:
                System.out.println("choose correct transaction");
                System.out.println("***********************");
                break;

        }
        if(opt==5)
        {
            System.out.println("Thankyou");
            System.out.println("please take your card");
            break;
        }
        }
    }
}
