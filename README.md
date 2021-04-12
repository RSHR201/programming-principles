# programming-principles
using System;

namespace Classes
{
    class Program
    {
        static void Main()
        {
            //Car._strColor = "Green";

            Car._nTotalCars = 0;

            Car objMyCar1 = new Car();
            //objMyCar1.newPurchase();
            int nTotalCars1 = objMyCar1.getTotalCars();
            //int nYear = objMyCar1._nYear;
            //string strMyCarColor = objMyCar1.getColor();
            //Console.WriteLine(strMyCarColor);

            objMyCar1.setColor("Black");
            //strMyCarColor = objMyCar1.getColor();
            //Console.WriteLine(strMyCarColor);

            Car objMyCar2 = new Car();
            //objMyCar2.newPurchase();
            int nTotalCars2 = objMyCar2.getTotalCars();
            //strMyCarColor = objMyCar2.getColor();
            //Console.WriteLine(strMyCarColor);

            objMyCar1.Year = 2021;
            objMyCar1.Price = 1500;
            objMyCar1._strMaker = "Honda";
            ///////////////////

            Shape objShape = new Shape();
            objShape.setColor("Red");

            Shape objShape2 = new Shape();



            int nId = objShape.getId();
            double fArea = objShape.getArea();
            string strColor = objShape.getColor();

            Console.WriteLine(nId);
            Console.WriteLine(fArea);
            Console.WriteLine(strColor);

            ////////////////
            Student objStu = new Student();
            objStu.setStuId(102);
            int nStuId = objStu.getStuId();

/*
 * string strName = "Matthew Michael is a Student";

Console.WriteLine(strName);

int nLen = strName.Length;
string strLen = Convert.ToString(nLen);
Console.WriteLine("My string length is " + strLen);

string strSub = strName.Substring(8, 7);

Console.WriteLine("My sub string is " + strSub);
*/

}
}
}
