```java


public void bla() {
    int a = 0;
    int a = 10;// erro
}

```

```java

class Bla {
    static int a;
    int a; // erro de compilação,
}
...

System.out.println(new Bla().a); // qual variável estamos
                                 // acessando?

```

```java


class Pessoa {

    static int x = 0;
    int y = 0;

    public static void setX(int x) {
        // Usando a referência da classe
        Pessoa.x = x;
    }

    public void setY(int y) {
        // usando o this
        this.y = y;
    }
}

```


```java

class X {
    int a = 10;

    public void metodo() {
        int a = 20; // shadowing
        System.out.println(a); // imprime 20
    }
}

```
