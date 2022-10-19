package hw02;
interface Data{
	public void showData();
}
interface Test{
	public void showScore();
	public double calcu();
}

class CStu implements Data,Test{
	protected String id;
	protected String name;
	protected int mid;
	protected int finl;
	protected int comm;
	public Cstu(String s1,String s2,int m,int f, int c) {
		this.id=s1;
		this.name=s2;
		this.comm=c;
		this.finl=f;
		
	}
	
	
	public void showData() {
		System.out.print("學號"+id);
		System.out.print("姓名"+name);
	}
	public void showScore() {
		System.out.println("期中:"+mid);
		System.out.println("期末:"+finl);
		System.out.println("平時:"+comm);
	}
	public double calcu() {
		return(mid*.3+finl*.3+comm*.4);
	}
	public void show();
		showData();
		showScore();
}
public class hw11 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		CStu stu = new Cstu("940001","Fiona",90,92,85);
		stu.show();
	}
}	
