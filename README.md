# hash-map
//HASHMAP

import java.util.*
class Testhashmap{  
 public static void main(String args[]){  
    
   HashMap<Integer,String> hm=new HashMap<Integer,String>();  
   
   hm.put(100,"Srini");  
   hm.put(101,"Vijay");  
   hm.put(102,"Ram");  
   
   for(Map.Entry m:hm.entrySet()){  
    System.out.println(m.getKey()+" "+m.getValue());  
   }  
  }  
 }  

//LINKED HASHMAP

import java.util.*;  
 class  testlinkhashmap{  
  public static void main(String args[]){  
       LinkedHashMap<Integer,String> lhm=new LinkedHashMap<Integer,String>();  
   
   lhm.put(100,"raghu");  
   lhm.put(101,"Vivek);  
   lhm.put(102,"muthu");  
   
 for(Map.Entry m:lhm.entrySet()){  
 System.out.println(m.getKey()+" "+m.getValue());  
   }  
  }  
 }  



