using System;

using System.collections.Generics;

Using System.Data.SQLite;

singing System.IO;


abstract class Empleado
{
    public string Cedula { get; set; }
    public string Codigo { get; set; }
    public string Nombre { get; set: }
    public string Departamento { get; set; }
    public double PrecioHora { get; set; }
    public int HoarasTrabajadores { get; set; }
    public double SalarioNeto { get; set; }



    public Empleado(string cedula, string nombre, string departamento, double preciohora,
        int horasTrabajo)
    {
        Cedula = cedula;
        Nombre = nombre;
        Departamento = departamento;
        PrecioHora = preeciohora;
        HoarasTrabajadores = HoarasTrabajadores;
        SalarioNeto = SalarioNeto;
    
    }



    public void CalcularSalario()
    {
        SalarioNeto = PrecioHora * HoarasTrabajadores

    }

    public string GenerarVoucher()
    {
        return $@


    }
}
