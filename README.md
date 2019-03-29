# code_summary
## 一些编程总结

***

## Java

一、语法

1.while，if中的break跳出的是整个循环。

eg:


```java
public class App 
{
    public static void main( String[] args )
    {
        System.out.println( "Hello World!" );
        System.out.println("1");
        int i=0;
        while(true){
            if(i==2){
                System.out.println(i+"if--------------------");
                break;
            }
            i++;
            System.out.println(i+"------------------------");
        }
    }
}
```

