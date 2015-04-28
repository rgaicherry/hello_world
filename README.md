# hello_world
Sample respository

public MyTest {
  
  String myMesg = "Hollow, world! ";
  int num = 0;
  
  public void main() {
    System.out.println(myMesg);
    
    String newMesg = "tThis is addtional content ";
  
    updateMesg(newMEsg, num);
    num ++;
  }
  
  public void updateMesg (String newMEsg, int count) {
    System.out.println(">>>>> MyTest::updateMEsg()");
    
    String updateStr = newMesg + count;
    String myMesg += updateStr;
  
    System.out.println(myMesg);
  }
}
