/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package exercicio01;

import javax.swing.JOptionPane;



public class Conta {
    
String Tipo;
double saldo;
String titular;
double limite;



//Construtor
public Conta(){
    
saldo = 50;
limite = 100;
}
//metodo sacar
public void sacar(double valor){
    
    saldo = saldo - valor;   
}

public void depositar (double valor){
    
    saldo = saldo + valor;}

public void transferir(){
//Depois faremos
}

public void imprimir(){

    JOptionPane.showMessageDialog(null, "\nTitular: "+titular+"\nTipo: "+Tipo+"\nSaldo: "+saldo+"\nLimite: "+limite);
}
    
}


