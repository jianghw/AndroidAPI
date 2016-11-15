# 单元测试
***
##JUnit
*[官网](http://junit.org/junit4/)*
* Assert
  - .assertEquals()
  > `public class CalculaterTest {  
    Calculater calculater = new Calculater();  
    @org.junit.Test  
    public void testAdd() {
        int a = 1;
        int b = 2;
        int result = calculater.add(a, b);
        Assert.assertEquals(result, 3); // 验证result==3，如果不正确，测试不通过
    }
}`

##Mockito
*[官网](http://site.mockito.org/)*

