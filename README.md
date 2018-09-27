# proyecto1
import java.util.Scanner;

public class MyClass {
    public static void main(String args[]) {
    int x, c, a, b;
    Scanner cal = new Scanner(System.in);
    System.out.println("que operacion matematica desea utilizar:");
    System.out.println("1.Suma");
    System.out.println("2.resta");
    System.out.println("3.multiplicacion");
    System.out.println("4 division");
     x = cal.nextInt();
    switch(x){
    
    case 1:
        System.out.println("ingrese su primer numero:");
        a = cal.nextInt();
        System.out.println("ingrese su segundo numero:");
        b = cal.nextInt();
        c = a+b;
        System.out.println("su resultado es:"+ c);
        break; 
        
    case 2:
        System.out.println("ingrese su primer numero: ");
        a = cal.nextInt();
        System.out.println("ingrese su segundo numero:");
        b = cal.nextInt();
        c = a-b;
        System.out.println("su resultado es:" + c);
        break; 
    case 3:
        System.out.println("ingrese su primer numero:");
        a = cal.nextInt();
        System.out.println("ingrese su segundo numero:");
        b = cal.nextInt();
        c = a*b;
    
        System.out.println("su resultado es:" + c);
        break; 
    case 4:
        System.out.println("ingrese su primer numero:" );
        a = cal.nextInt();
        System.out.println("ingrese su segundo numero:");
        b = cal.nextInt();
        c = a/b;
        System.out.println("su resultado es:" + c);
        break; 
        
    
        
        
        
    }
    
    
    }
}

