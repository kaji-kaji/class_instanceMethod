class StudentCard {  
  int id;   //学籍番号  
  String name;  //氏名    
  
  StudentCard(int id, String name) {  
    this.id = id;  
    this.name = name;  
  }  
  
  void printInfo() {
    System.out.println("学籍番号："　+ this.id);
    System.out.println("氏名：" + this.name);
  }
}

public class InstanceMethodExample {  
  public static void main(String[] args) {  
    StudentCard a = new StudentCard(1234, "鈴木太郎");  
    StudentCard b = new StudentCard(1235, "佐藤花子");
    a.printInfo();
    b.printInfo();
  }
}

実行結果  

学籍番号：1234
氏名：鈴木太郎
学籍番号：1235
氏名：佐藤花子
