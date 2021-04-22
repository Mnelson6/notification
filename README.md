# notification
import java.util.Scanner;
import java.util.ArrayList;

public class notification{
    
  public static void main(String[] args){

    Scanner sc = new Scanner(System.in);
         
    System.out.println("What departments in the School of Natural Science & Mathematics would you like to chat in?");

//Creating the list

    ArrayList<String> list = new ArrayList<String>();
    list.add("1-Biology");
    list.add("2-Chemistry");
    list.add("3-Mathematics & Computer Science");
    list.add("4-Nursing");

   
    ArrayList<String> time = new ArrayList<String>();
    time.add("1-Professor 1: ");
    time.add("2-Professor 2: ");
    time.add("1-Professor 3: ");
    time.add("2-Professor 4: ");
    time.add("1-Professor 5: ");
    time.add("2-Professor 6: ");
    time.add("1-Professor 7: ");
    time.add("2-Professor 8: ");
    
    ArrayList<String> schd = new ArrayList<String>();
    schd.add("1-8:15am");
    schd.add("2-9:30am");  
    schd.add("3-12:00pm");
    schd.add("1-9:15am");
    schd.add("2-10:30am");  
    schd.add("3-12:45pm");
    schd.add("1-10:15am");
    schd.add("2-11:30am");  
    schd.add("3-1:00pm");  
    schd.add("1-11:15am");
    schd.add("2-12:30pm");  
    schd.add("3-1:00pm");  
    schd.add("1-12:15pm");
    schd.add("2-1:30pm");  
    schd.add("3-2:00pm");  
    schd.add("1-1:15pm");
    schd.add("2-2:30pm");  
    schd.add("3-3:00pm");  
    schd.add("1-2:15pm");
    schd.add("2-3:30pm");
    schd.add("3-4:00pm");
    schd.add("1-3:15pm");
    schd.add("2-4:30pm");

  //Convert to object array
  
  Object[] array = list.toArray();
  Object[] schedule = time.toArray();
   
  //Iterate and convert to desired type
  
  for(Object o : list){
    String s = (String) o;
  System.out.println(s);
  }
  
    int choice = sc.nextInt();
 
 //If user typed the department
  
  
      if(choice == 1) {
      System.out.println("You have chosen The Department of Biology. Please choose what professor and time you would prefer.");
      
      String professor1 = time.get(0);
          
      String time1 = schd.get(0);
      String time2 = schd.get(1);
      String time3 = schd.get(2);
          
      String professor2 = time.get(1);

      String time4 = schd.get(3);
      String time5 = schd.get(4);
      String time6 = schd.get(5);
          
      System.out.println(professor1 + time1 + ", " + time2 + ", " + time3);
      System.out.println(professor2 + time4 + ", " + time5 + ", " + time6);

       int choice2 = sc.nextInt();
       //User choice professor
    }
    
      if( choice == 2){
       System.out.println("You have chosen The Department of Chemistry. Please choose what professor and time you would prefer.");
      String professor3 = time.get(2);
         
      String time7 = schd.get(6);   
      String time8 = schd.get(7); 
      String time9 = schd.get(8);
          
      String professor4 = time.get(3); 

      String time10 = schd.get(9);
      String time11 = schd.get(10);
      String time12 = schd.get(11); 
          
      System.out.println(professor3 + time7 + ", " + time8 + ", " + time9);
      System.out.println(professor4 + time10 + ", " + time11 + ", " + time12);
       
          int choice2 = sc.nextInt();
    }
   
    if( choice == 3){
      System.out.println("You have chosen The Department of Mathematics & Science. Please choose what professor and time you would prefer.");
      String professor5 = time.get(4);
        
      String time13 = schd.get(12);
      String time14 = schd.get(13);
      String time15 = schd.get(14); 
        
      String professor6 = time.get(5); 

      String time16 = schd.get(15);
      String time17 = schd.get(16);
      String time18 = schd.get(17);
        
      System.out.println(professor5 + time13 + ", " + time14 + ", " + time15);
      System.out.println(professor6 + time16 + ", " + time17 + ", " + time18);
       
        int choice2 = sc.nextInt();
    }
   
    if( choice == 4){
      System.out.println("You have chosen The Department of Nursing. Please choose what professor and time you would prefer.");
      String professor7 = time.get(6);
        
      String time19 = schd.get(18);
      String time20 = schd.get(19);
      String time21 = schd.get(20);
        
      String professor8 = time.get(7); 

      String time22 = schd.get(21);
      String time23 = schd.get(22);
      

      System.out.println(professor7 + time19 + ", " + time20 + ", " + time21);
      System.out.println(professor8 + time22 + ", " + time23);
      
       int choice2 = sc.nextInt();
       
       
       
       System.out.println(choice2);

       
    }
      
     System.out.println("Which time would you prefer?" );
     int choice3 = sc.nextInt();
     
     //If user typed time
      
      if( choice3 == 1){
          System.out.println("Request Sent");
      }
      if( choice3 == 2){
          System.out.println("Request Sent");
      }
      if( choice3 == 3){
          System.out.println("Request Sent");
      }
      
      
      
     
  }
    
     }
      
