# 14-10
Задача [https://www.codewars.com/kata/542c0f198e077084c0000c2e]
Любимое решение 
import java.util.stream.IntStream;
public class FindDivisor {
  public long numberOfDivisors(int n) {
    return IntStream.range(1, n+1).filter(i -> n%i==0).count();
  }
}
