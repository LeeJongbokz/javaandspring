


### 다시 보는 main() 메서드: 메서드 스택 프레임 


- main() 메서드는 프로그램이 실행되는 시작점임  
  main() 메서드가 실행될 때 메모리, 특히 T 메모리에는 어떤 일이 일어날까?
  예제 2-1의 Start.java가 한 줄씩 실행될 때마다 T 메모리가 어떻게 변화하는지 살펴봄 
  
```
public class Start{
  public static void main(String[] args){
    System.out.println("Hello OOP!!!");
  }
}
```

- T 메모리 구조는 그림 2-4와 같음 . 
  여기서는 어떤 요소들이 각 영역을 사용하게 될지 비유적으로 표현함  
  해당 비유를 기억해 두기 바람  
  
 
  
