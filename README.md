# Task-1
Codsoft Internship Task-1
public class Task1 {
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        Random rand=new Random();
        int x=rand.nextInt(100-0+1)+0;
        int n=0;
        int score=100;
        while(n!=x){
            n=sc.nextInt();
            if(n==x) {
                System.out.print("Yaah!! You guessed correct one");
                break;
            }
            score-=5;
            if(n>x)
                System.out.print("You guessed greater number try again");
            else
                System.out.println("You guessed lesser number try again");
        }
        System.out.println("Your score out of 100 is"+" "+score);

    }
}
