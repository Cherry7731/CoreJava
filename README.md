# CoreJava
class Inheritance
{
    void call()
    {
      System.out.println("make a phone call");
    }
}
class User extends Inheritance
{
    void speak()
    {
      System.out.println("speaking");
    }
}
class Main 
{
    public static void main (String[]args)
    {
      User u = new User();
      s.call();
      s.speak();
    }
}
