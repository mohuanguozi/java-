# 文件输入与输出
想要对文件进行读取，就需要一个用File对象构造一个Scanner对象
    例如：Scanner in = new Scanner(Paths.get("file.txt")."UTF-8");
    注意：文件名中包含反斜杠符号，需要记住在每个反斜杠前在加一个“\”,例如：“c:\\举例\\file.txt”。
想要写入文件，就需要构造一个PrintWriter对象
    例如：PrintWriter out = new PrintWrite("file.txt"."UTF-8");
