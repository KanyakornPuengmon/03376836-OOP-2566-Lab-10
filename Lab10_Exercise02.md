# Lab 10 Exercise 2

## 

1.สร้าง console application project

```cmd
dotnet new console --name Lab10_Ex02
```

2.เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
var shape = new Shape();
var circle = new Circle();
var rectangle = new Rectangle();
var triangle = new Triangle();

class Shape
{
    public Shape()
    {
        System.Console.WriteLine("This is some shape");
    }
}
class Circle :Shape
{
    public Circle()
    {
        System.Console.WriteLine("This is a circle");
    }
}
class Rectangle :Shape
{
    public Rectangle()
    {
        System.Console.WriteLine("This is a rectangle");
    }
}
class Triangle :Shape
{
   public Triangle()
    {
        System.Console.WriteLine("This is a triangle");
    }
}
```

3.Build project โดยการใช้คำสั่ง

```cmd
dotnet build  Lab10_Ex02
```

ถ้ามีที่ผิดพลาดในโปรแกรม ให้แก้ไขให้ถูกต้อง

4.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3

5.Run project โดยการใช้คำสั่ง

```cmd
dotnet run --project Lab10_Ex02
```

6.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5

7.อธิบายสิ่งที่พบในการทดลอง