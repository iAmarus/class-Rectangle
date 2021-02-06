public class Rectangle {
	private double width;	
	private double height;	
	
	Rectangle() {
		width = 1;
		height = 1;
	} 
	
	Rectangle(double newWidth, double newHeight) {
		width = newWidth;
		height = newHeight;
	}
	
	public double setHight(double height) {
		return this.height = height;
	}
	public double setWidth(double width) {
		return this.width = width;
	}
	public double getArea() {
		return width * height; 
	}
	
	public double getPerimeter() {
		return 2 * (width + height);
	}

}
