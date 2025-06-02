# Repo-36
Calculate radius of circle
//Area of circle program
import java.util.Scanner;
class circle{
    public static void main(String[] args) {
    final double PI=3.14,area;
    int r;
    System.out.println("Enter radius of circle");
    Scanner ref =new Scanner(System.in);
    r=ref.nextInt();
    
    area=PI*r*r;
    System.out.println("Area of circle " +area);
    
    }
