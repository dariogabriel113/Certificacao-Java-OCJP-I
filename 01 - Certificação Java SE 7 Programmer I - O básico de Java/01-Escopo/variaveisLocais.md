```java
public void m1() { // início do bloco do método
    int x = 10; // variável local do método

    if (x >= 10) { // início do bloco do if
        int y = 50; // variável local do if
        System.out.print(y);

    } // fim do bloco do if

} // fim do bloco do método
```

```java
for (int i = 0, j = 0; i < 10; i++)
    j++;

System.out.println(j); // erro, já não está mais no escopo
```

```java
class Teste {
        public void m1(String bla) {
            System.out.print(bla);
        }

        public void m2() {
            // erro de compilação pois bla não existe neste
            // escopo
            System.out.println(bla);
        }
}
```
