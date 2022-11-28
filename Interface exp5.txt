public interface Shape {
	public void draw();
	public void colorfill();

}
public class Rectangle implements Shape {
	public void draw() {
		System.out.println("Rectangle is drawn");
	}
	public void colorfill() {
		System.out.println("Rectangle is filled in Green color");
	}

}

public class Circle implements Shape{
	public void draw() {
		System.out.println("Circle is drawn");
	}
	public void colorfill() {
		System.out.println("Circle is filled in Yellow color");
	}
}

public class Triangle implements Shape {
	public void draw() {
		System.out.println("Triangle is drawn");
	}
	public void colorfill() {
		System.out.println("Triangle is filled in Red color");
	}
}

public class Square implements Shape {
	public void draw() {
		System.out.println("Square is drawn");
	}
	public void colorfill() {
		System.out.println("Square is filled in Blue color");
	}
}

public class ShapeMain {

	public static void main(String[] args) {
		Rectangle r = new Rectangle();
		Circle c = new Circle();
		Triangle t = new Triangle();
		Square s = new Square();
		r.draw();
		r.colorfill();
		c.draw();
		c.colorfill();
		t.draw();
		t.colorfill();
		s.draw();
		s.colorfill();

	}

}