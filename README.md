# Venda-de-ve-culos
Código simples de venda de veículos
package venda.de.veiculos;
import java.util.Scanner;

public class VendaDeVeiculos {
     
    public static void main(String[] args) {
       double carros,motos,caminhoes;
       int v1, v2, v3,v4, v5, v6,v7,v8;
       
       Scanner ler = new Scanner(System.in);
       //Sistema
       System.out.println("Esconha o veiculo q deseja comprar : ");
       System.out.println(" 1 - Carro");
       System.out.println(" 2 - Moto");
       System.out.println(" 3 - Caminhao");
       System.out.println(" 4 - Sair");
       v1 = ler.nextInt();
       
           //Carros
	if (v1 == 1) {
        Scanner ler1  = new Scanner(System.in);            
     System.out.println("#CARROS# ");
     System.out.println(" 1 - Audi = 1.000.000" );
     System.out.println(" 2 - Corolla = 3.445,00");
     System.out.println(" 3 - Kadett = 100.000");
     v2 = ler1.nextInt();
     
     // CODIGO PARA A COMPRA DOS CARROS
     //audi
         if(v2 == 1){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Audi ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "1.000.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "510.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "323.332"); 
         }
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
        //corolla
         if(v2 == 2){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Corolla ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //parcelas
            if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "3.445,00");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "1.807,95");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "1.182,7"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
     //Kadett
     if(v2 == 3){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Kadett ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "100.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "51.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "34.333,33"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
     
     
     //MOTOS
	}
        if (v1 == 2) {
        Scanner ler1  = new Scanner(System.in);            
     System.out.println("#MOTOS# ");
     System.out.println(" 1 - Suzuki = 1.000.000" );
     System.out.println(" 2 - Honda = 3.445,00");
     System.out.println(" 3 - Yamaha= 100.000");
     v2 = ler1.nextInt();
         //suzuki
         if(v2 == 1){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Suzuki ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "1.000.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "510.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "323.332"); 
         }
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
        //Honda
         if(v2 == 2){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Honda ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //parcelas
            if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "3.445,00");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "1.807,95");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "1.182,7"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
     //Yamaha
     if(v2 == 3){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Yamaha ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "100.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "51.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "34.333,33"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
   }
        //CAMINHAO
        if (v1 == 3) {
        Scanner ler1  = new Scanner(System.in);            
     System.out.println("#CAMINHOES# ");
     System.out.println(" 1 - Scania = 1.000.000" );
     System.out.println(" 2 - Volvo= 3.445,00");
     System.out.println(" 3 - Mercedes-Benz= 100.000");
     v2 = ler1.nextInt();
     //Scania
     if(v2 == 1){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Scania ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "1.000.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "510.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "323.332"); 
         }
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
        //Volvo
         if(v2 == 2){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Volvo ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //parcelas
            if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "3.445,00");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "1.807,95");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "1.182,7"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
     //Mercedes-Benz
     if(v2 == 3){
         Scanner ler2  = new Scanner(System.in); 
         System.out.println("Para efetuar a compra do Mercedes-Benz ");
         System.out.println("Digite seu nome: ");
         String nome = ler.next();
         System.out.println("Digite seu CPF:  ");
         v3 = ler2.nextInt();
         System.out.println("De quantas vezes deseja parcelar (maximo de parcelas 3):  ");
         v4 = ler2.nextInt();
         //Parcelas
         if(v4 ==1){
             System.out.println("Voce escolheu 1 parcela que ficara no valor de avista: " + "100.000");
         }
         if(v4 ==2){
             System.out.println("Voce escolheu  parcelar de 2 vezes que ficara no valor com acrecimo de juros de 2%: " + "51.000");
         }
         if(v4 ==3){
             System.out.println("Voce escolheu  parcelar de 3 vezes que ficara no valor com acrecimo de juros de 3%: " + "34.333,33"); 
         }
         
         System.out.println("SUA COMPRA FOI EFETUADA COM SUCESSO!!!" );
         System.exit(0);  
     }
    }
          //Botao sair
       if (v1 == 4) {
           System.out.println("Obrigada...");
           System.exit(0);  
           
         }
    }
    }
