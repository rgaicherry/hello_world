# hello_world
Sample respository

public MyTest {
  
  String myMesg = "Hollow, world! ";
  int num = 0;
  
  public void main() {
    System.out.println(myMesg);
  
    String updateStr = "This is the updated content " + num;
    num ++;
    String myMesg += updateStr;
  
    System.out.println(myMesg);
  }
}
