# hello_world
Sample respository

public MyTest {
  
  String myMesg = "Hollow, world! ";
  int num = 0;
  
  public void main() {
    System.out.println(myMesg);
    
    String newMesg = "This is addtional content ";
  
    updateMesg(newMesg, num);
    num ++;
  }
  
  public void updateMesg (String newMesg, int count) {
    System.out.println(">>>>> MyTest::updateMEsg()");
    
    String updateStr = newMesg + count;
    String myMesg += updateStr;
  
    System.out.println(myMesg);
  }
}
