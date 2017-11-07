# Utilizaci-n-Facturas
package utilizacionfactura;
/**
 *
 * @author Adirane
 */

//Clase principal
public class UtilizacionFactura {

    //Método main
    public static void main(String[] args) {
        
        Factura f1 = new Factura(); //Se instancia el objeto de la clase Factura
        
        //Se imprime el valor de PI definido en la clase factura
	System.out.println("Valor de la constante PI: " +f1.PI);
    }
    
}

//Clase Factura
class Factura{
    
    //Atributos de la clase Factura
    public static String TipoIva = "Iva del 16%";
    public final double PI;
    public String NombreTitular;
    public String ConceptoFactura;
    public double Precio;
    public double Total;
    public double Iva;

    //Constructor de la clase Factura
    public Factura(){

	//Inicialización de los miembros de la clase
	this.PI=3.1416;
	this.NombreTitular = "sin titular";
	this.ConceptoFactura = "sin concepto";
	this.Precio = 0.0;
	this.Iva = 0.0;
	this.Total = 0.0;
  }
}
