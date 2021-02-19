# statusmusica

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package com.mycompany.exercicio1poo;

/**
 *
 * @author Windows
 */
public class Musica {
    String Tipo;
    String Região;
    String Pais;
    float Andamento;
    int Duração;
    boolean Tocando;
             void status() {
                 System.out.println("Música " + this.Tipo);
                 System.out.println("de " + this.Região);
                 System.out.println("do " + this.Pais);
                 System.out.println("compasso "+ this.Andamento);
                 System.out.println("com tempo estimado "+ this.Duração + " minutos. ");
                 System.out.println("está " + this.Tocando);
                 
            
                 
             }
             void tocar(){
                 if (this.Tocando == true)
                     System.out.println("Está tocando!");
                 else
                     System.out.println("Não está tocando!");
                 
                 
         }
             
    
    
}
