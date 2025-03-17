import javax.swing.JOptionPane;
package areaquadrado;

public class Areaquadrado {

    public static void main(String[] args) {
        double lado, area;
        lado=Double.parseDouble(JOptionPane.showInputDialog("Insira o valor do Lado do Quadrado: "));
        area=lado*lado;
       
        JOptionPane.showMessageDialog(null, "A área do quadrado é: "+area);
    }
    
}
