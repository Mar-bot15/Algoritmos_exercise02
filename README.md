# Algoritmos_exercise02
import javax.swing.*;

    public class Exercise_02 {
        public static void main(String[] args){

            int valor1, valor2, valor3, MA;
            valor1 = Integer.parseInt(JOptionPane.showInputDialog("Digite o primeiro valor"));
            valor2 = Integer.parseInt(JOptionPane.showInputDialog("Digite o segundo valor"));
            valor3 = Integer.parseInt(JOptionPane.showInputDialog("Digite o terceiro valor"));
            MA = (valor1 + valor2 + valor3)/3;
            JOptionPane.showMessageDialog(null,"O resulatdo é: " + MA);
        }
    }
