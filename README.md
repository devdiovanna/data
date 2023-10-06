import java.time.LocalDate;

public class Main {

    public static void main(String[] args) {
        //Olá, {nome}. Hoje é {dia-da-semana}, BOM DIA.

        String nome = "Jessé";

        // ISO 8601
        LocalDate hoje = LocalDate.now();
        System.out.println(hoje);

    }
}
