# abstractorinterface
package abstractorinterface;
public abstract class AbstractOrInterface extends Kot
{
    protected String imie;
    public AbstractOrInterface(String imie)
    {
    this.imie=imie;
    }
    public String PodajImie()
    {
        return imie;
    }
abstract public void wydajOdglos();
}

 class Kot implements miesozerca
{
     public String mieso;
   public void zjedzMieso()
   {
       System.out.println("jem sobie : "+mieso);
   }
   
   
public void wydajOdglos()
{
    System.out.println("Meow");
}
}
interface miesozerca
{
public void zjedzMieso();
        }
interface roslinozerca
{
public void jestesVege();
}
