# Task-1
Codsoft Internship Task-1
public class Task1 {
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        Random rand=new Random();
        int x=rand.nextInt(100-0+1)+0;
        int n=0;
        while(n!=x){
            n=sc.nextInt();
            if(n==x) {
                System.out.print("Yaah!! You guessed correct one");
                break;
            }
            if(n>x)
                System.out.print("You guessed greater number try again");
            else
                System.out.print("You guessed lesser number try again");
        }

    }
}
