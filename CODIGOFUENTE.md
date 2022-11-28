package salud.bienestar;
import java.util.*;

public class SALUDBIENESTAR {

    public static void main(String[] args) {
        Scanner teclado= new Scanner (System.in);
        String Nom = "";
        String Edad = "";
        System.out.println("--------------------");
        System.out.println("¿Cómo Te Llamas?");
        Nom= teclado.nextLine();
        System.out.println("¿Que Edad tienes?");
        Edad= teclado.nextLine();
        System.out.println("--------------------");
        System.out.println("");
        
        System.out.println("*******************************************************************");
        System.out.println("Primero Necesitamos que nos diga cuanto pesa y cuanto mide");
        System.out.println("");
        float IMC, P, E;
        System.out.println("Cuánto Pesa en Kg");
        P= teclado.nextFloat();
        System.out.println("Cuánto Mide en M");
        E= teclado.nextFloat();
        System.out.println("*******************************************************************");
        System.out.println("");
        
        IMC= P/(E*E);
        System.out.println("Hola " +Nom+ " Que gusto es atenderte, tu Indice de Masa Corporal " +Nom+  " es de: " +IMC+ ".");
        
        if (IMC <= 18.5) {
            System.out.println("Desnutrición");
            System.out.println("");
            System.out.println("¿Estarias dispuesto a seguir un regimen alimenticio para mejorar tu calidad de vida y salud? " +Nom);
            System.out.println("");
            System.out.println("1.- SI ");
            System.out.println("");
            System.out.println("2.- NO ");
            System.out.println("");
            System.out.println("3.- NO TENGO TIEMPO");
            System.out.println("");
            String op = "";
            op = teclado.next();
            
            switch (op) {
                case "s": String S = "";
                System.out.println("Si");
                S = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N = "";
                System.out.println("No");
                N = teclado.next();
                System.out.println("");
                break;
                
                case "nt": String NTiemp ="";
                System.out.println("No tengo tiempo");
                NTiemp = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("1.- ¿Género?");
            System.out.println("--------------------");
            System.out.println("O P C I O N E S: ");
            System.out.println("--------------------");
            System.out.println("M A S C U L I N O ");
            System.out.println("");
            System.out.println("F E M E N I N O");
            System.out.println("");
            System.out.println("O T R O S");
            System.out.println("");
            String op1 = "";
            op1=teclado.next();
            switch (op1) {
                case "m": String M = "";
                System.out.println("Masculino");
                M = teclado.next();
                System.out.println("");
                break;
                
                case "f": String F = "";
                System.out.println("Femenino");
                F = teclado.next();
                System.out.println("");
                break;
                
                case "e": String O = "";
                System.out.println("Otros");
                O = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("2.- ¿En tu dieta regular incluyes Carnes? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op2 = "";
            op2 = teclado.next();
            switch (op2) {
                case "cf": String CF1 = "";
                System.out.println("CON FRECUENCIA");
                CF1 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV1 = "";
                System.out.println("A VECES");
                AV1 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA1 = "";
                System.out.println("NO ACOSTUMBRO");
                NA1 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N1 = "";
                System.out.println("NUNCA");
                N1 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("3.- ¿En tu dieta regular incluyes Frutas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op3 = "";
            op3 = teclado.next();
            switch (op3) {
                case "cf": String CF2 = "";
                System.out.println("CON FRECUENCIA");
                CF2 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV2 = "";
                System.out.println("A VECES");
                AV2 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA2 = "";
                System.out.println("NO ACOSTUMBRO");
                NA2 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N2 = "";
                System.out.println("NUNCA");
                N2 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("4.- ¿En tu dieta regular incluyes Verduras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op4 = "";
            op4 = teclado.next();
            switch (op4) {
                case "cf": String CF3 = "";
                System.out.println("CON FRECUENCIA");
                CF3 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV3 = "";
                System.out.println("A VECES");
                AV3 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA3 = "";
                System.out.println("NO ACOSTUMBRO");
                NA3 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N3 = "";
                System.out.println("NUNCA");
                N3 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("5.- ¿En tu dieta regular incluyes Cereales? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op5 = "";
            op = teclado.next();
            switch (op5) {
                case "cf": String CF4 = "";
                System.out.println("CON FRECUENCIA");
                CF4 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV4 = "";
                System.out.println("A VECES");
                AV4 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA4 = "";
                System.out.println("NO ACOSTUMBRO");
                NA4 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N4 = "";
                System.out.println("NUNCA");
                N4 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("6.- ¿Que tan frecuentemente incluyes Alimentos Chatarras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op6 = "";
            op6 = teclado.next();
            switch (op6) {
                case "cf": String CF5 = "";
                System.out.println("CON FRECUENCIA");
                CF5 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV5 = "";
                System.out.println("A VECES");
                AV5 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA5 = "";
                System.out.println("NO ACOSTUMBRO");
                NA5 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N5 = "";
                System.out.println("NUNCA");
                N5 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("7.- ¿Que tan frecuentemente incluyes Refrescos o Gaseosas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op7 = "";
            op7 = teclado.next();
            switch (op7) {
                case "cf": String CF6 = "";
                System.out.println("CON FRECUENCIA");
                CF6 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV6 = "";
                System.out.println("A VECES");
                AV6 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA6 = "";
                System.out.println("NO ACOSTUMBRO");
                NA6 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N6 = "";
                System.out.println("NUNCA");
                N6 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("8.- ¿Eres alergico a algún alimento o producto? digame cuales. " +Nom);
            String Alergia = teclado.next();
            
            System.out.println("");
            System.out.println("9.- ¿Cuántas horas del día le dedicas a tu Trabajo? " +Nom);
            String HorasT = teclado.next();
            
            System.out.println("");
            System.out.println("10.- ¿Cuántas horas del día le dedicas a  tu Sueño o Descanso? " +Nom);
            String Sueño = teclado.next();
            
            System.out.println("");
            System.out.println("11.- ¿Cuántas horas del día le dedicas al Ocio o Esparcimiento? " +Nom);
            String Ocio = teclado.next();
            
            
            System.out.println("");
            System.out.println("12.- ¿Cuántas horas del día le dedicas al Acondicionamiento Físico? " +Nom);
            String AF = teclado.next();
            
            System.out.println("");
            System.out.println("13.- ¿Cuántas Comidas haces al día? " +Nom); 
            String ComidaD = teclado.next();
            
            System.out.println("");
            System.out.println("14.- ¿Que cantidad consumes de Agua Simple al día en Litros? " +Nom); 
            String Consumes = teclado.next();
            
            System.out.println("");
            System.out.println("15.- ¿Padece alguna Enfermedad Crónica o Degenerativa? " +Nom);
            String Enfermedad = teclado.next();
            
            System.out.println("");
            System.out.println("16.- ¿Tiene algún impedimento Físico? " +Nom);
            String Impedimento = teclado.next();
            
            System.out.println("");
            System.out.println("17.- ¿Esta Dispuesto a modificar sus rutinas diarias y ajustarse a un correcto regimen de alimentación para tener una vida Saludable? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("1.- SI");
            System.out.println("");
            System.out.println("2.- NO");
            System.out.println("");
            String op9 = "";
            op9 = teclado.next();
            switch (op9) {
                case "s1": String S1 = "";
                System.out.println("Si");
                S1 = teclado.next();
                System.out.println("");
                break;
                
                case "n1": String N1 = "";
                System.out.println("No");
                N1 = teclado.next();
                System.out.println("");
                break;

                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            System.out.println("");
            System.out.println("**************************************************************************************************************************************");
            System.out.println("UNA VEZ CONCLUIDO EL CUESTIONARIO Y CONOCERTE MEJOR " +Nom+ " AHORA SI, CONTINUEMOS CON LA DIETA.");
            System.out.println("SE LE PIDE DE FAVOR QUE LOS HORARIOS QUE SE LE ASIGNE POR COMIDA LOS SIGA, DE PREFERENCIA PONER RECORDATORIO EN EL CELULAR.");
            System.out.println("PORQUE UNA DIETA REQUIERE DE CONSTANCIA, PERSEVERANCIA, ORDEN Y TIEMPO PARA LLEVAR A CABO LAS COMIDAS.");
            System.out.println("**************************************************************************************************************************************");
            System.out.println("");
            
            System.out.println("****************************************************************************************");
            System.out.println("DESAYUNO A LAS 08:30a.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE LECHE DE 250ml");
            System.out.println("");
            System.out.println("2.- PORCIÓN DE 350g DE FRUTAS VARIADA ");
            System.out.println("");
            System.out.println("3.- TOMAR UNA PASTILLA DE HIERRO CON ÁCIDO FÓLICO DESPUES DE ACABARSE EL DESAYUNO");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("COLACIÓN MATUTINA A LAS 11:30a.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE JUGO DE 250ml NATURAL");
            System.out.println("");
            System.out.println("2.- UNA PORCIÓN DE PALANQUETA DE 100g");
            System.out.println("");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("COMIDA A LAS 03:30p.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE AGUA DE SABOR DE 250ml NATURAL");
            System.out.println("");
            System.out.println("2.- SOPA AL GUSTO ACOMPAÑADO DE GUISADO DE TU PREFERENCIA CON GUARNICIÓN DE FRIJOL");
            System.out.println("");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("COLACIÓN VESPERTINA A LAS 05:30p.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE AGUA SIMPLE DE 250ml");
            System.out.println("");
            System.out.println("2.- ENSALADA DE TU PREFERENCIA");
            System.out.println("");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("CENA A LAS 09:00p.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE LECHE DE 250ml");
            System.out.println("");
            System.out.println("2.- CENAR LO QUE GUSTES PERO SIN EXAGERAR");
            System.out.println("");
            System.out.println("ANTES DE ACOSTARSE, CAMINAR UNOS 10 MINUTOS");
            System.out.println("****************************************************************************************");
            
            System.out.println("HACER ESTA DIETA DURANTE DOS SEMANAS, VARIANDO EL ORDEN");
            System.out.println("POR QUE EL ORDEN DE LOS FACTORES NO ALTERA EL PRODUCTO");
            
        }else
            
            if (IMC >= 18.5 && IMC <=24.9) {
            System.out.println("Saludable");
            System.out.println("");
            System.out.println("¿Estarias dispuesto a seguir un regimen alimenticio para mejorar tu calidad de vida y salud? " +Nom);
            System.out.println("");
            System.out.println("1.- SI ");
            System.out.println("");
            System.out.println("2.- NO ");
            System.out.println("");
            System.out.println("3.- NO TENGO TIEMPO");
            System.out.println("");
            String op18 = "";
            op18 = teclado.next();
            
            switch (op18) {
                case "s": String S2 = "";
                System.out.println("Si");
                S2 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N2 = "";
                System.out.println("No");
                N2 = teclado.next();
                System.out.println("");
                break;
                
                case "nt": String NTiemp2 ="";
                System.out.println("No tengo tiempo");
                NTiemp2 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("1.- ¿Género?");
            System.out.println("--------------------");
            System.out.println("O P C I O N E S: ");
            System.out.println("--------------------");
            System.out.println("M A S C U L I N O ");
            System.out.println("");
            System.out.println("F E M E N I N O");
            System.out.println("");
            System.out.println("O T R O S");
            System.out.println("");
            String op10 = "";
            op10=teclado.next();
            switch (op10) {
                case "m": String M = "";
                System.out.println("Masculino");
                M = teclado.next();
                System.out.println("");
                break;
                
                case "f": String F = "";
                System.out.println("Femenino");
                F = teclado.next();
                System.out.println("");
                break;
                
                case "e": String O = "";
                System.out.println("Otros");
                O = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("2.- ¿En tu dieta regular incluyes Carnes? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op11 = "";
            op11 = teclado.next();
            switch (op11) {
                case "cf": String CF1 = "";
                System.out.println("CON FRECUENCIA");
                CF1 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV1 = "";
                System.out.println("A VECES");
                AV1 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA1 = "";
                System.out.println("NO ACOSTUMBRO");
                NA1 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N1 = "";
                System.out.println("NUNCA");
                N1 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("3.- ¿En tu dieta regular incluyes Frutas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op12 = "";
            op12 = teclado.next();
            switch (op12) {
                case "cf": String CF2 = "";
                System.out.println("CON FRECUENCIA");
                CF2 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV2 = "";
                System.out.println("A VECES");
                AV2 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA2 = "";
                System.out.println("NO ACOSTUMBRO");
                NA2 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N2 = "";
                System.out.println("NUNCA");
                N2 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("4.- ¿En tu dieta regular incluyes Verduras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op13 = "";
            op13 = teclado.next();
            switch (op13) {
                case "cf": String CF3 = "";
                System.out.println("CON FRECUENCIA");
                CF3 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV3 = "";
                System.out.println("A VECES");
                AV3 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA3 = "";
                System.out.println("NO ACOSTUMBRO");
                NA3 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N3 = "";
                System.out.println("NUNCA");
                N3 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("5.- ¿En tu dieta regular incluyes Cereales? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op14 = "";
            op14 = teclado.next();
            switch (op14) {
                case "cf": String CF4 = "";
                System.out.println("CON FRECUENCIA");
                CF4 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV4 = "";
                System.out.println("A VECES");
                AV4 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA4 = "";
                System.out.println("NO ACOSTUMBRO");
                NA4 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N4 = "";
                System.out.println("NUNCA");
                N4 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("6.- ¿Que tan frecuentemente incluyes Alimentos Chatarras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op15 = "";
            op15 = teclado.next();
            switch (op15) {
                case "cf": String CF5 = "";
                System.out.println("CON FRECUENCIA");
                CF5 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV5 = "";
                System.out.println("A VECES");
                AV5 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA5 = "";
                System.out.println("NO ACOSTUMBRO");
                NA5 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N5 = "";
                System.out.println("NUNCA");
                N5 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("7.- ¿Que tan frecuentemente incluyes Refrescos o Gaseosas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op16 = "";
            op16 = teclado.next();
            switch (op16) {
                case "cf": String CF6 = "";
                System.out.println("CON FRECUENCIA");
                CF6 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV6 = "";
                System.out.println("A VECES");
                AV6 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA6 = "";
                System.out.println("NO ACOSTUMBRO");
                NA6 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N6 = "";
                System.out.println("NUNCA");
                N6 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("8.- ¿Eres alergico a algún alimento o producto? digame cuales. " +Nom);
            String Alergia = teclado.next();
            
            System.out.println("");
            System.out.println("9.- ¿Cuántas horas del día le dedicas a tu Trabajo? " +Nom);
            String HorasT = teclado.next();
            
            System.out.println("");
            System.out.println("10.- ¿Cuántas horas del día le dedicas a  tu Sueño o Descanso? " +Nom);
            String Sueño = teclado.next();
            
            System.out.println("");
            System.out.println("11.- ¿Cuántas horas del día le dedicas al Ocio o Esparcimiento? " +Nom);
            String Ocio = teclado.next();
            
            
            System.out.println("");
            System.out.println("12.- ¿Cuántas horas del día le dedicas al Acondicionamiento Físico? " +Nom);
            String AF = teclado.next();
            
            System.out.println("");
            System.out.println("13.- ¿Cuántas Comidas haces al día? " +Nom); 
            String ComidaD = teclado.next();
            
            System.out.println("");
            System.out.println("14.- ¿Que cantidad consumes de Agua Simple al día en Litros? " +Nom); 
            String Consumes = teclado.next();
            
            System.out.println("");
            System.out.println("15.- ¿Padece alguna Enfermedad Crónica o Degenerativa? " +Nom);
            String Enfermedad = teclado.next();
            
            System.out.println("");
            System.out.println("16.- ¿Tiene algún impedimento Físico? " +Nom);
            String Impedimento = teclado.next();
            
            System.out.println("");
            System.out.println("17.- ¿Esta Dispuesto a modificar sus rutinas diarias y ajustarse a un correcto regimen de alimentación para tener una vida Saludable? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("1.- SI");
            System.out.println("");
            System.out.println("2.- NO");
            System.out.println("");
            String op17 = "";
            op17 = teclado.next();
            switch (op17) {
                case "s1": String S3 = "";
                System.out.println("Si");
                S3 = teclado.next();
                System.out.println("");
                break;
                
                case "n1": String N3 = "";
                System.out.println("No");
                N3 = teclado.next();
                System.out.println("");
                break;

                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            System.out.println("");
            System.out.println("*******************************************************************************************************************************************");
            System.out.println("UNA VEZ CONCLUIDO EL CUESTIONARIO Y CONOCERTE MEJOR " +Nom+ " AHORA SI, CONTINUEMOS CON LOS EJERCICIOS.");
            System.out.println("SE LE PIDE DE FAVOR QUE LOS HORARIOS QUE SE LE ASIGNE POR RUTINA DE EJERCICIO LOS SIGA, DE PREFERENCIA PONER RECORDATORIO EN EL CELULAR.");
            System.out.println("PORQUE LAS RUTINAS DE EJRCICIOS REQUIERE DE CONSTANCIA, PERSEVERANCIA, ORDEN Y TIEMPO PARA LLEVAR A CABO LOS EJERCICIOS.");
            System.out.println("*******************************************************************************************************************************************");
            System.out.println("");
            
            System.out.println("****************************************************************************************");
            System.out.println("RUTINA 1");
            System.out.println("");
            System.out.println("1.- 10 REPETICIONES DE ABDOMINALES");
            System.out.println("");
            System.out.println("2.- 5 REPETICIONES DE LAGARTIJAS");
            System.out.println("");
            System.out.println("EN CASO DE QUE TENGAS CAMINADORA HACER: ");
            System.out.println("3.- 10 MINUTOS DE CAMINADORA ");
            System.out.println("SI NO CUENTAS CON CAMINADORA, NO TE PREOCUPES: ");
            System.out.println("10 MINUTOS TROTANDO EN LA CALLE Ó 20 MINUTOS CAMINANDO EN LA CALLE");
            System.out.println("");
            System.out.println("DESCANSAR 15 MINUTOS, HIDRATANDOSE CON ELECTROLITOS Ó AGUA.");
            System.out.println("NO BEBER BEBIDAS ENERGETIZANTES");
            System.out.println("DESPUES DE 15 MINUTOS DE DESCANSO, HACER LOS MISMOS EJERCICIOS OTRA VEZ.");
            System.out.println("DESCANSAR 10 MINUTOS Y POR ÚLTIMO VOLVER A REALIZAR LOS EJERCICIOS.");
            System.out.println("****************************************************************************************");
            
            System.out.println("HACER ESTOS EJERCICIOS TODOS LOS DÍAS POR 1 SEMANA");
            System.out.println("PASANDO LA SEMANA INTENTAR AUMENTAR LOS NUMEROS DE REPETICIONES EN CADA EJERCICIOS");
            System.out.println("LLEGAR HACIA UN OBJETIVO, TOMA DE ESFUERZO Y DEDICACIÓN.");

                }else
                
                    if (IMC >= 25 && IMC <=29.9) {
                    System.out.println("Con Sobrepeso");
                    System.out.println("");
                    System.out.println("¿Estarias dispuesto a seguir un regimen alimenticio para mejorar tu calidad de vida y salud? " +Nom);
            System.out.println("");
            System.out.println("1.- SI ");
            System.out.println("");
            System.out.println("2.- NO ");
            System.out.println("");
            System.out.println("3.- NO TENGO TIEMPO");
            System.out.println("");
            String op19 = "";
            op19 = teclado.next();
            
            switch (op19) {
                case "s": String S4 = "";
                System.out.println("Si");
                S4 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N4 = "";
                System.out.println("No");
                N4 = teclado.next();
                System.out.println("");
                break;
                
                case "nt": String NTiemp4 ="";
                System.out.println("No tengo tiempo");
                NTiemp4 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("1.- ¿Género?");
            System.out.println("--------------------");
            System.out.println("O P C I O N E S: ");
            System.out.println("--------------------");
            System.out.println("M A S C U L I N O ");
            System.out.println("");
            System.out.println("F E M E N I N O");
            System.out.println("");
            System.out.println("O T R O S");
            System.out.println("");
            String op20 = "";
            op20=teclado.next();
            switch (op20) {
                case "m": String M = "";
                System.out.println("Masculino");
                M = teclado.next();
                System.out.println("");
                break;
                
                case "f": String F = "";
                System.out.println("Femenino");
                F = teclado.next();
                System.out.println("");
                break;
                
                case "e": String O = "";
                System.out.println("Otros");
                O = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("2.- ¿En tu dieta regular incluyes Carnes? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op21 = "";
            op21 = teclado.next();
            switch (op21) {
                case "cf": String CF1 = "";
                System.out.println("CON FRECUENCIA");
                CF1 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV1 = "";
                System.out.println("A VECES");
                AV1 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA1 = "";
                System.out.println("NO ACOSTUMBRO");
                NA1 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N1 = "";
                System.out.println("NUNCA");
                N1 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("3.- ¿En tu dieta regular incluyes Frutas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op22 = "";
            op22 = teclado.next();
            switch (op22) {
                case "cf": String CF2 = "";
                System.out.println("CON FRECUENCIA");
                CF2 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV2 = "";
                System.out.println("A VECES");
                AV2 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA2 = "";
                System.out.println("NO ACOSTUMBRO");
                NA2 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N2 = "";
                System.out.println("NUNCA");
                N2 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("4.- ¿En tu dieta regular incluyes Verduras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op23 = "";
            op23 = teclado.next();
            switch (op23) {
                case "cf": String CF3 = "";
                System.out.println("CON FRECUENCIA");
                CF3 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV3 = "";
                System.out.println("A VECES");
                AV3 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA3 = "";
                System.out.println("NO ACOSTUMBRO");
                NA3 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N3 = "";
                System.out.println("NUNCA");
                N3 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("5.- ¿En tu dieta regular incluyes Cereales? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op24 = "";
            op24 = teclado.next();
            switch (op24) {
                case "cf": String CF4 = "";
                System.out.println("CON FRECUENCIA");
                CF4 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV4 = "";
                System.out.println("A VECES");
                AV4 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA4 = "";
                System.out.println("NO ACOSTUMBRO");
                NA4 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N4 = "";
                System.out.println("NUNCA");
                N4 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("6.- ¿Que tan frecuentemente incluyes Alimentos Chatarras? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op25 = "";
            op25 = teclado.next();
            switch (op25) {
                case "cf": String CF5 = "";
                System.out.println("CON FRECUENCIA");
                CF5 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV5 = "";
                System.out.println("A VECES");
                AV5 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA5 = "";
                System.out.println("NO ACOSTUMBRO");
                NA5 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N5 = "";
                System.out.println("NUNCA");
                N5 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("7.- ¿Que tan frecuentemente incluyes Refrescos o Gaseosas? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("CON FRECUENCIA");
            System.out.println("");
            System.out.println("A VECES");
            System.out.println("");
            System.out.println("NO ACOSTUMBRO");
            System.out.println("");
            System.out.println("NUNCA");
            String op26 = "";
            op26 = teclado.next();
            switch (op26) {
                case "cf": String CF6 = "";
                System.out.println("CON FRECUENCIA");
                CF6 = teclado.next();
                System.out.println("");
                break;
                
                case "av": String AV6 = "";
                System.out.println("A VECES");
                AV6 = teclado.next();
                System.out.println("");
                break;
                
                case "na": String NA6 = "";
                System.out.println("NO ACOSTUMBRO");
                NA6 = teclado.next();
                System.out.println("");
                break;
                
                case "n": String N6 = "";
                System.out.println("NUNCA");
                N6 = teclado.next();
                System.out.println("");
                break;
                
                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            
            System.out.println("");
            System.out.println("8.- ¿Eres alergico a algún alimento o producto? digame cuales. " +Nom);
            String Alergia = teclado.next();
            
            System.out.println("");
            System.out.println("9.- ¿Cuántas horas del día le dedicas a tu Trabajo? " +Nom);
            String HorasT = teclado.next();
            
            System.out.println("");
            System.out.println("10.- ¿Cuántas horas del día le dedicas a  tu Sueño o Descanso? " +Nom);
            String Sueño = teclado.next();
            
            System.out.println("");
            System.out.println("11.- ¿Cuántas horas del día le dedicas al Ocio o Esparcimiento? " +Nom);
            String Ocio = teclado.next();
            
            
            System.out.println("");
            System.out.println("12.- ¿Cuántas horas del día le dedicas al Acondicionamiento Físico? " +Nom);
            String AF = teclado.next();
            
            System.out.println("");
            System.out.println("13.- ¿Cuántas Comidas haces al día? " +Nom); 
            String ComidaD = teclado.next();
            
            System.out.println("");
            System.out.println("14.- ¿Que cantidad consumes de Agua Simple al día en Litros? " +Nom); 
            String Consumes = teclado.next();
            
            System.out.println("");
            System.out.println("15.- ¿Padece alguna Enfermedad Crónica o Degenerativa? " +Nom);
            String Enfermedad = teclado.next();
            
            System.out.println("");
            System.out.println("16.- ¿Tiene algún impedimento Físico? " +Nom);
            String Impedimento = teclado.next();
            
            System.out.println("");
            System.out.println("17.- ¿Esta Dispuesto a modificar sus rutinas diarias y ajustarse a un correcto regimen de alimentación para tener una vida Saludable? " +Nom);
            System.out.println("--------------------");
            System.out.println("O P C I O N E S");
            System.out.println("--------------------");
            System.out.println("1.- SI");
            System.out.println("");
            System.out.println("2.- NO");
            System.out.println("");
            String op28 = "";
            op28 = teclado.next();
            switch (op28) {
                case "s1": String S5 = "";
                System.out.println("Si");
                S5 = teclado.next();
                System.out.println("");
                break;
                
                case "n1": String N5 = "";
                System.out.println("No");
                N5 = teclado.next();
                System.out.println("");
                break;

                case "error": System.out.println("ERROR: OPCIÓN INVALIDA");
                break;
            }
            System.out.println("");
            System.out.println("**************************************************************************************************************************************");
            System.out.println("UNA VEZ CONCLUIDO EL CUESTIONARIO Y CONOCERTE MEJOR " +Nom+ " AHORA SI, CONTINUEMOS CON LA DIETA.");
            System.out.println("SE LE PIDE DE FAVOR QUE LOS HORARIOS QUE SE LE ASIGNE POR COMIDA LOS SIGA, DE PREFERENCIA PONER RECORDATORIO EN EL CELULAR.");
            System.out.println("PORQUE UNA DIETA REQUIERE DE CONSTANCIA, PERSEVERANCIA, ORDEN Y TIEMPO PARA LLEVAR A CABO LAS COMIDAS.");
            System.out.println("**************************************************************************************************************************************");
            System.out.println("");
            
            System.out.println("****************************************************************************************");
            System.out.println("DESAYUNO A LAS 08:30a.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE TÉ DE SU PREFERENCIA DE 250ml SIN AZUCAR");
            System.out.println("");
            System.out.println("2.- PORCIÓN DE 350g DE FRUTAS VARIADA ");
            System.out.println("");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("COLACIÓN MATUTINO A LAS 11:30a.m");
            System.out.println("");
            System.out.println("1.- UN VASO AGUA DE SABOR DE 250ml NATURAL");
            System.out.println("");
            System.out.println("2.- GALLETAS HABANERAS CON TIRAS DE QUESO PANELA. MAXIMO 5 GALLETAS");
            System.out.println("");
            System.out.println("****************************************************************************************");

            
            System.out.println("****************************************************************************************");
            System.out.println("COMIDA A LAS 03:30p.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE AGUA SIMPLE DE 250ml");
            System.out.println("");
            System.out.println("2.- ENSALADA DE CHAYOTE CON PRCHUGA ASADA");
            System.out.println("");
            System.out.println("****************************************************************************************");
            
            System.out.println("****************************************************************************************");
            System.out.println("COLACIÓN VESPERTINA A LAS 05:30p.m");
            System.out.println("");
            System.out.println("1.- UNA TAZA DE CAFÉ O TÉ DE 250ml SIN AZUCAR");
            System.out.println("");
            System.out.println("2.- FRUTAS EN RODAJAS");
            System.out.println("");
            System.out.println("****************************************************************************************");

            
            System.out.println("****************************************************************************************");
            System.out.println("CENA A LAS 10:00p.m");
            System.out.println("");
            System.out.println("1.- UN VASO DE ADES DE 250ml");
            System.out.println("");
            System.out.println("2.- UNA PAPA MEDIANA HERVIDA CORTADA EN CUARTOS CON ENSALADA PICO DE GALLO.");
            System.out.println("");
            System.out.println("ANTES DE ACOSTARSE, CAMINAR UNOS 15 MINUTOS");
            System.out.println("****************************************************************************************");
            
            System.out.println("NO SE PUEDE COMER COMIDA CHATARRA, DULCES, ETC.");
            System.out.println("NO SE PUEDE TOMAR REFRESCO, AGUA DE SABOR ARTIFICIAL, ETC.");
            System.out.println("");
            System.out.println("EN CASO DE COMER TORTILLAS, NO COMER MÁS DE 2 TORTILLAS");
            System.out.println("O EN EL CASO DE COMER PAN, NO COMER MÁS DE 1 PAN");
            System.out.println("PREFERENTEMENTE COMER PAN BIMBO: TOSTADO O NORMAL.");
            System.out.println("");
            System.out.println("HACER ESTA DIETA DURANTE DOS SEMANAS, VARIANDO EL ORDEN");
            System.out.println("POR QUE EL ORDEN DE LOS FACTORES NO ALTERA EL PRODUCTO");
        }
    }
}
