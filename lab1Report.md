```
{
    "cd" = "[user@sahara ~]$",
    "cd lecture1" = "[user@sahara ~/lecture1]$ ",
    "cd Hello.Class" = "bash: cd: Hello.java: Not a directory"
}
```

```
{
    "ls" = "lecture1",
    "ls messages/" = "en-us.txt  es-mx.txt  ja.txt  zh-cn.txt",
    "ls Hello.java" = "Hello.java"

}
```

```
{
    #with an initial input of test
    "cat" = "test\n test",
    "cat lecture1/" = "cat: lecture1/: Is a directory",
    "ls Hello.class" = "import java.io.IOException;
                        import java.nio.charset.StandardCharsets;
                        import java.nio.file.Files;
                        import java.nio.file.Path;

                        public class Hello {
                            public static void main(String[] args) throws IOException {
                            String content = Files.readString(Path.of(args[0]), StandardCharsets.UTF_8);    
                                System.out.println(content);
                          }
                        }"

}
```
