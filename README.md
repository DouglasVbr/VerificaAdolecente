# VerificaAdolecente

package verificaadolecente;

import java.util.Scanner;

public class VerificaAdolecente {

   
    public static void main(String[] args) {
       
        Scanner Scanner = new Scanner (System.in);
        
        // solicita ao usuario que insira a idade 
        System.out.println("Digite sua idade");
        int idade = Scanner.nextInt();
        // verifica se a pessoa é adolecente
        if(idade >= 13 && idade <= 19){
            System.out.println("voce é adolecente");
        }else{
            System.out.println("voce não é adolecente");
            
        }
        // fecha Scanner 
        Scanner.close();
    }
    
}
