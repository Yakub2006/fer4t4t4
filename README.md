# fer4t4t4
import java.util.Scanner;
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class Main {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("Login: ");
       String Login = in.nextLine();

         Pattern p = Pattern.compile("[0-9][a-z]+",
          Pattern.CASE_INSENSITIVE     );
             Matcher m = p.matcher(Login);{
        System.out.println("Password: ");
        String Password = in.nextLine();
            Pattern h = Pattern.compile("[0-9][a-z]+",
                    Pattern.CASE_INSENSITIVE     );
            Matcher g = p.matcher(Password);{
                System.out.println("Your Email: ");
                String Email = in.nextLine();
                Pattern k = Pattern.compile("[0-9@][a-z]+",
                        Pattern.CASE_INSENSITIVE     );
                Matcher t = k.matcher(Email);
                int countElements=0;
                for (char element : Email.toCharArray() )
                    if (element == '@' && countElements < Email.length()  ){
                        System.out.println("Welcome");
                    }


                    }
                }


              }
}
