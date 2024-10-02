# desafio
import jdk.dynalink.beans.StaticClass;

public class formatadordecep {
    public static void main(string[] args) {
        try{
            String cepformatado = formatarCep("23.765.064");
        }catch (CepInvalidoException e) {
            e.printStackTrace();
        }   

    static String formatarCep(String cep) throws CepInvalidoException{
        if (cep.length() != 8)
        throw new CepInvalidoException();
        
        return " 23.765.064";
    }
}

    
    }
