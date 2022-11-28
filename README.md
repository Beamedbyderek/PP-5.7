# PP-5.7

import java.util.Scanner;

class main {
  public static void main(String[] args) {
    
    //input
   Scanner in = new Scanner(System.in);
   
   int wins = 0;  //score variables
   int losses = 0;  
   
   System.out.print.ln(" Enter rock, paper, scissor or quit");
   string playerMove = in.nextLine();
   
   if(playerMove.equals("quit")) {   //lets player leave
    break;
    }
    
    if(!playerMove.equals("rock") && !playerMove.equals("paper") && !playerMove.equals("scissor")) {
      system.out.println("invalid");   //checks if move is valid
      } else {
      
      //generates bots move
      int rand = (int)(math.random() * 3):
      String botMove = "";
      if(rand == 0) {
        botMove = "rock";
        } else if(rand == 1) {
        botMove = "paper";
        } else {
        botMove = "scissors";
        }
        System.out.println("Bots move" + botsMove);
        
        https://www.youtube.com/watch?v=RNusv_APZKM&ab_channel=JuniLearning
