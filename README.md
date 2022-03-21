//in java staic blocks run first before loding class object by compiler(static memory me static varrible load hone ke pahle hi static block run hoga, yha tak ke print ke pahle hi print hoga) 
 class Prince {
     static int a = 10;

     static void fun() {
         System.out.println("kjdfn");
     }

     Prince() {
         System.out.println("jkd");

     }


     static {
         System.out.println("knnlknkln");
     }
 }




 class Diff {
     public static void main(String[] args) {
          int a=10;
         System.out.println("heloo");
         Prince a1=new Prince();
         //a1.fun();
     }
     static{
         System.out.println("vhj");
     }


 }
