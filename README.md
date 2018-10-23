[TOC]
## 这是Typora风格

### 第一组

1. description 1
2. description 2
3. description 3

### 第二组

1. **description** 2_1
2. *description* 2_2

## vs2015key

```
Visual Studio Professional 2015

Key : HMGNV-WCYXV-X7G9W-YCX63-B98R2

Visual Studio Enterprise 2015

Key :HM6NR-QXX7C-DFW2Y-8B82K-WTYJV

Visual Studio Enterprise 2015

Key :2XNFG-KFHR8-QV3CP-3W6HT-683CH
```

## mermaid测试

```mermaid
graph LR
AA(AA)-->B(B)
B-->C(C)
C-->H(H)
V(V)-->D(D)
C-->D(D)
D-->E(E)
D-->F(F)
E-->G(G)
E-->F

Z(Z)-->Y)
Z-->W(W)
Z-->V(V)
V-->H
```

## 代码块格式测试

1. java格式

   ```java
   public class P1 {
       public P1() {
           System.out.println("没卵用");
       }
       
       public static void main(String[] args) {
       	P1 p1 = new P1();
           System.out.println("hello world");
       }
   }
   ```

2. html

   ```html
   <html>
   	<head>This is a page</head>
   	<body>
   		<input type="text" placeholder="this is a text"></input>
   		<button>jump</button>
   	</body>
   	<foot></foot>
   </html>
   ```

3. sql

   ```mysql
   # 查询1830000的手机号，且是90后的用户
   SELECT * FROM USER u WHERE INSTR(u.`mobile_number`, '1830000') AND u.`birthday` BETWEEN '1990' AND '1999';
   ```
