# fileWriter
import java.io.FileWriter; 
public class Patika { 
public static void main(String[] args) { 
String data = "Java Dersleri"; 
try { FileWriter output = new FileWriter("output.txt");            
output.write(data);

            output.close();
} catch (Exception e) {             
e.getStackTrace();

        }
    }
}
