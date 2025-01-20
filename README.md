# Sum-of-numbers
package sum.of.the.digits.of.numbers;


public class SumOfTheDigitsOfNumbers {

    
    public static void main(String[] args) {
        int num=16,rem=0,sum=0,temp;
        temp=num;
        while (num>0)
        {
            rem=num%10;
            sum=sum+rem;
            num=num/10;
        }
        System.out.println("sum of digits of"+temp+"is"+sum);
    }                                         
    }
    }



run:
sum of digits of16is7
BUILD SUCCESSFUL (total time: 0 seconds)
