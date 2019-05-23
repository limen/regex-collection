# regex-collection

常见的正则表达式

### 非空白字符串

- PHP风格 ```/\s*\S+?/```

### 中文

- PHP风格 ```/^[\x{4e00}-\x{9fa5}+$/u```

### 语句（中文、英文、数字、标点符号）

- PHP风格 ```/^[\x{4e00}-\x{9fa5}A-Za-z0-9\p{P}]+$/u```
