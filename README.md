# lab_5_6_
public class Main {

    public static void main(String[] args) {
        {
            //№1
            System.out.println("№ 1");
            int a;
            a = 80 + 20;
            System.out.println("Рузультат : " + a);
            int b = a - 80;
            System.out.println("Рузультат : " + b);
            int c = a / b;
            System.out.println("Рузультат : " + c);
            int d = c % 2;
            System.out.println("Рузультат : " + d);
        }
        {
            //№2
            System.out.println(" № 2");
            int a = 15;
            int b = a%10;
            int c = (a/10)%10;
            System.out.println("Суму цифр двозначного числа " +a+"="+(b+c));
        }
        {
            //№3
            System.out.println("№ 3");
            int a;
            a = 306+99;
            System.out.println("Рузультат : "+a);
            int b = a-64;
            System.out.println("Рузультат : "+b);
            int c = a/b;
            System.out.println("Рузультат : "+c);
            double d = c;
            System.out.format("%3f",+ d );

        }

    }

