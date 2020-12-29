# Employee.java
public class Secretary extends Employee
{
   
     
     //Default<<constructor>>
  public Secretary()
  {
      System.out.println("Secretary  object now created");
  }
  
   public Secretary(String name)
    {
        super (name);
      
    }
    
  
  @Override
  
     public double getHours() {
         double hours;
         int numOfWeeks = 4;
         hours = 40*numOfWeeks;
        return hours;
    }
     
     
  @Override
    public void work()
  {
      System.out.println("Secretaries knows how to type");
  }

    
    
    
}
