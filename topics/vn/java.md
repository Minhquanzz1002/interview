## Java

---

[🎯 Java là gì và có những đặc điểm gì?](#-java-là-gì-và-có-những-đặc-điểm-gì)  

[🎯 Khái niệm về final, finally, finalize trong Java?](#-khái-niệm-về-final-finally-finalize-trong-java)  

[🎯 Điều gì xảy ra khi một exception không được xử lý trong Java?](#-điều-gì-xảy-ra-khi-một-exception-không-được-xử-lý-trong-java)  

[🎯 Phân biệt giữa extends và implements trong Java?](#-phân-biệt-giữa-extends-và-implements-trong-java)  

[🎯 Quá trình biên dịch và thực thi một chương trình Java?](#-quá-trình-biên-dịch-và-thực-thi-một-chương-trình-java)  

[🎯 Các thành phần cơ bản trong một lớp Java?](#-các-thành-phần-cơ-bản-trong-một-lớp-java)  

[🎯 Java Garbage Collection là gì?](#-java-garbage-collection-là-gì)  

[🎯 Cách tối ưu bộ nhớ trong Java?](#-cách-tối-ưu-bộ-nhớ-trong-java)  

[🎯 Tại sao String trong Java là immutable (bất biến)?](#-tại-sao-string-trong-java-là-immutable-bất-biến)  

[🎯 Exception là gì?](#-exception-là-gì)  

[🎯 Giải thích về throw và throws trong Java.](#-giải-thích-về-throw-và-throws-trong-java)  

[🎯 Giải thích về do-while và while trong Java.](#-giải-thích-về-do-while-và-while-trong-java)  

[🎯 Sự khác biệt giữa super và this trong Java?](#-sự-khác-biệt-giữa-super-và-this-trong-java)  

[🎯 Bạn có thể sử dụng abstract với phương thức static không?](#-bạn-có-thể-sử-dụng-abstract-với-phương-thức-static-không)  

[🎯 Một số lưu ý về `abstract class`](#-một-số-lưu-ý-về-abstract-class)  

[🎯 Một số lưu ý về interface](#-một-số-lưu-ý-về-interface)  

[🎯 i++](#-i)  

[🎯 ++i](#-i-1)  

[🎯 Sự khác biệt giữa == và equals() trong Java?](#-sự-khác-biệt-giữa--và-equals-trong-java)  

[🎯 Sự khác biệt giữa i++ và ++i](#-sự-khác-biệt-giữa-i-và-i)  

[🎯 String Pool](#-string-pool)  

[🎯 Integer Cache](#-integer-cache)  

[🎯 Sự khác biệt giữa abstract class và interface?](#-sự-khác-biệt-giữa-abstract-class-và-interface)  

[🎯 Khi nào dùng abstract class khi nào dùng interface?](#-khi-nào-dùng-abstract-class-khi-nào-dùng-interface)  

[🎯 Sự khác biệt giữa Overloading và Overriding?](#-sự-khác-biệt-giữa-overloading-và-overriding)  

[🎯 Những đặc tính nổi bậc của java 8?](#-những-đặc-tính-nổi-bậc-của-java-8)  

[🎯 Các Collection Interface](#-các-collection-interface)  

[🎯 Map Interface](#-map-interface)  

[🎯 Sự khác biệt JDK, JRE, JVM?](#-sự-khác-biệt-jdk-jre-jvm)  

[🎯 Final](#-final)  

[🎯 Access modifier (phạm vi truy cập)](#-access-modifier-phạm-vi-truy-cập)  

[🎯 Sự khác biệt giữa mảng và ArrayList?](#-sự-khác-biệt-giữa-mảng-và-arraylist)  

[🎯 Tại sao không sử dụng con trỏ trong java?](#-tại-sao-không-sử-dụng-con-trỏ-trong-java)  

[🎯 Tại sao Java lại độc lập nền tảng?](#-tại-sao-java-lại-độc-lập-nền-tảng)  

[🎯 Đối tượng trong java là gì?](#-đối-tượng-trong-java-là-gì)  

[🎯 Java có mấy kiểu dữ liệu?](#-java-có-mấy-kiểu-dữ-liệu)  

[🎯 String trong java là bất biến đúng không? Có mấy cách tạo](#-string-trong-java-là-bất-biến-đúng-không-có-mấy-cách-tạo)  

[🎯 Phân biệt String vs StringBuilder vs StringBuffer](#-phân-biệt-string-vs-stringbuilder-vs-stringbuffer)  

[🎯 Stack và Heap trong java?](#-stack-và-heap-trong-java)  

[🎯 Class có thể kế thừa interface không và ngược lại?](#-class-có-thể-kế-thừa-interface-không-và-ngược-lại)  

[🎯 Nguyên lý SOLID?](#-nguyên-lý-solid)  



### 🎯 Java là gì và có những đặc điểm gì?

---

Java là một ngôn ngữ lập trình hướng đối tượng. Được thiết kế để chạy trên nhiều nền tảng khác nhâu mà không gặp phải vấn đề tương thích, nhờ vào cơ chế Write Once, Run Anywhere. Các đặc điểm gồm:
- Độc lập nền tảng
- Hướng đối tượng
- Đa luồng
- Thu gom rác tự động
- Thư viện phong phú

### 🎯 Khái niệm về final, finally, finalize trong Java?

---

- `final`: Là từ khóa dùng để khai báo một đối tượng không thể thay đổi. Nó có thể được sử dụng với:
    - Biến: Để khai báo một hằng số
    - Lớp: Để khai báo một lớp không thể kế thừa.
    - Phương thức: Để khai báo một phương thức không thể bị ghi đè
- `finally`: Là một khối mã trong câu lệnh `try-catch` luôn được thực thi, bất kể liệu có exception xảy ra hay không. 
Nó thường được dùng để giải phóng tài nguyên (như đóng file, kết nối mạng). **Khi trong finally có return thì giá trị return trong finally là giá trị cuối cùng.**
- `finalize`: Là một phương thức trong lớp `Object`, được gọi trước khi đối tượng bị garbage collection. Nó có thể được ghi đè để làm sạch tài nguyên, nhưng việc sử dụng `finalize()` không được khuyến khích trong Java hiện đại.

### 🎯 Điều gì xảy ra khi một exception không được xử lý trong Java?

---

Khi một exception không được xử lý trong Java, hệ thống sẽ ném ra (throw) exception đó lên các lớp cha của phương thức đang thực thi. Nếu exception không được xử lý trong bất kỳ lớp cha nào, chương trình sẽ dừng lại và in ra stack trace để thông báo về vị trí xảy ra lỗi trong mã nguồn.

### 🎯 Phân biệt giữa extends và implements trong Java?

---

extends: Dùng khi một lớp muốn kế thừa thuộc tính và phương thức từ một lớp khác.
implements: Dùng khi một lớp muốn cài đặt các phương thức của một giao diện và có thể cài đặt nhiều giao diện.

### 🎯 Quá trình biên dịch và thực thi một chương trình Java?

---

1. Viết mã nguồn
2. Biên dịch file `.java` thành `.class` qua `Javac`
3. Chạy chương trình với JVM
4. Quản lý bộ nhớ và Garbage Collection

### 🎯 Các thành phần cơ bản trong một lớp Java?

---

- Khai báo lớp
- Biến
- Constructor
- Method
- Khối static
- Phương thức static
- Lớp nội bộ

### 🎯 Java Garbage Collection là gì?

---

Là một cơ chế quản lý bộ nhớ tự động, giúp giải phóng bộ nhớ khi không còn sử dụng mà không cần sự can thiệt của lập trình viên

### 🎯 Cách tối ưu bộ nhớ trong Java?

---

1. Sử dụng kiểu dữ liệu phù hợp
2. Giảm thiểu việc tạo các đối tượng tạm thời

### 🎯 Tại sao String trong Java là immutable (bất biến)?

---

- An toàn trong đa luồng
- Tái sử dụng bộ nhớ

### 🎯 Exception là gì?

---

Exception là một sự kiện không mong muốn trong quá trình thực thi của chương trình, làm gián đoạn dòng chảy bình thường của nó. Exceptions có thể xảy ra do nhiều lý do, chẳng hạn như lỗi phần cứng, lỗi nhập liệu không hợp lệ, chia cho 0, lỗi truy cập tệp không tồn tại, v.v.
- `Runtime Exceptions (Unchecked Exceptions)`: là những lỗi không thể dự đoán trước và được kiểm tra khi chương trình thực thi. VD: lỗi logic bị null, chia cho 0
- `Checked Exceptions`: Là những lỗi có thể dự đoán trước và được kiểm tra lúc biên dịch. VD: SQLException khi không kết nối được với db

### 🎯 Giải thích về throw và throws trong Java.

---

- `throw` dùng để ném ngoại lệ từ trong một phương thức.
- `throws` dùng để khai báo phương thức có thể ném ngoại lệ ra ngoài.

### 🎯 Giải thích về do-while và while trong Java.

---

- `while`: kiểm tra điều kiện trước khi thực thi
- `do-while`: thực thi ít nhất 1 lần, sau đó kiểm tra điều kiện. VD: Nhập mật khẩu, nếu sai thì yêu cầu nhập lại tới khi đúng

### 🎯 Sự khác biệt giữa super và this trong Java?

---

- `this`: là một tham chiếu đến đối tượng hiện tại của lớp mà nó được sử dụng trong lớp đó
- `super`: là một tham chiếu đến đối tượng của lớp cha (superclass). Nó cho phép bạn truy cập vào các thành phần (biến, phương thức) của lớp cha từ lớp con.

### 🎯 Bạn có thể sử dụng abstract với phương thức static không?

---

Không. Vì
- `static`: là phương thức thuộc về lớp chứ không phải đối tượng. Điều này nghĩa là static method có thể gọi mà không cần tạo đối tượng
- `abstract`: là phương thức yêu cầu các lớp con phải cung cấp phần thân cho phương thức.

### 🎯 Một số lưu ý về `abstract class`

---

- Không thể tạo đối tượng
- Gồm cả method có thân và không thân
- abstract method bắt buộc phải có từ khóa `abstract`
- Về field thì giống như class thông thường

### 🎯 Một số lưu ý về interface

---

- Field trong interface luôn là `public static final`. Và không cần từ khóa interface sẽ ngầm hiểu
- Method mặc định luôn là `public abstract` và không cần từ khóa `public abstract`, trừ khi java 8+ là `default` hoặc `static` mới có thân

### 🎯 i++

---

```java
int i = 0;
int j = i++;    // i = 1, j = 0
```

### 🎯 ++i

---

```java
int i = 0;
int j = ++i;    // i = 1, j = 1
```

### 🎯 Sự khác biệt giữa == và equals() trong Java?

---

- `==` So sánh tham chiếu, tức là kiểm tra xem đối tượng có trỏ đến cùng 1 vị trí bộ nhớ không. Đối với dữ liệu nguyên thủy thì `==` so sánh giá trị của chúng.
- `equals()` Là phương thức của lớp `Object` dùng để so sánh giá trị của đối tượng. Nếu lớp cụ thể không ghi đè(override) phương thức này thì nó sẽ hành động giống `==`. Nhưng với các lớp như String, List thường để so sánh giá trị

### 🎯 Sự khác biệt giữa i++ và ++i

---

Điểm chung: đều tăng giá trị của i, nhưng giá trị trả về là khác nhau

Điểm riêng:
- i++ trả về giá trị trước khi tăng
- ++i trả về giá trị sau khi tăng

### 🎯 String Pool

---

```
String s1 = "Hello";
String s2 = "Hello";
String s3 = new String("Hello");
System.out.println(s1 == s2);      // true
System.out.println(s1 == s3);      // false
System.out.println(s1.equals(s3)); // true
```

### 🎯 Integer Cache

---

```
Integer num1 = 127;
Integer num2 = 127;
System.out.println(num1 == num2);  // true

Integer num3 = 128;
Integer num4 = 128;
System.out.println(num3 == num4);  // false
```
Giải thích: Integer caching cho giá trị từ -128 đến 127

### 🎯 Sự khác biệt giữa abstract class và interface?

---

Giống:
- Đều được sử dụng để tạo tính trừu tượng trong OOP.
- Đều không thể tạo đối tượng cụ thể với keyword new.
- Đều chứa cả phương thức và trường dữ liệu (interface phải là public static final)
  Khác:
- `Abstract class` có constructor
- Biến trong interface tất cả là hằng số
- abstract class phải `extends` còn interface thì `implements`

### 🎯 Khi nào dùng abstract class khi nào dùng interface?

---

Abstract class
- Khi có một nhóm các lớp liên quan cần chia sẻ chung một đoạn code hay tính năng nào đó. Bạn đưa các thành phần dùng chung vào lớp cha abstract và các lớp con liên quan sẽ kế thừa lớp cha abstract này.
- VD: dùng tạo 1 lớp BaseEntity để chứa các trường chung và BaseEntity sẽ không thể khởi tạo trực tiếp được
  Interface
- Muốn đạt được tính trừa tượng hoàn toàn. Trừu tượng hoàn toàn tất cả phương thức nêu ra trong interface đều không có phần triển khai chi tiết và cần được triển khai chi tiết bên trong lớp con implement interface đó.
- Muốn đạt đa kế thừa
- Muốn cho các lớp không liên quan gì đến nhau cũng có thể sử dụng chức năng của interface đó
- Khi muốn chỉ định các hành vi cần thực hiện mà không quan tâm hành vi đó được thực hiện bởi ai, thực hiện như thế nào

### 🎯 Sự khác biệt giữa Overloading và Overriding?

---


### 🎯 Những đặc tính nổi bậc của java 8?

---

- Viết code ngắn gọn hơn với lambda
- Xử lý collection dễ hàng hơn với Stream API
- Xử lý null an toàn hơn với Optional
- API Date/Time mới linh hoạt hơn (LocalDate, LocalTime, LocalDateTime,...)

### 🎯 Các Collection Interface

---

- List: danh sách có thứ tự, được phép trùng lặp.
- Set: tập hợp không cho phép trùng lặp.
- Queue: hàng đợi FIFO (First in first out)

### 🎯 Map Interface

---

- Lưu trữ dạng key và value
- Không cho phép trùng key

### 🎯 Sự khác biệt JDK, JRE, JVM?

---

JVM: là máy ảo java, môi trường thực thi bytecode java.

JRE: Bao gồm JVM và các thư viện chuẩn của Java. Cần thiết cho người dùng cuối.

JDK: Bao gồm JRE và các công cụ phát triển. Cần thiết cho lập trình java.

### 🎯 Final

---

- Variable: không thể thay đổi giá trị.
- Method: không thể override.
- Class: không thể kế thừa.

### 🎯 Access modifier (phạm vi truy cập)

---

- public: bất kì đâu
- default: trong cùng class và package
- protected: cùng class và ngoài package khác thông qua lớp con
- private: cùng class

### 🎯 Sự khác biệt giữa mảng và ArrayList?

---

- Mảng là cấu trúc dữ liệu có kích thước cố định.
- ArrayList là lớp collection có thể thay đổi kích thước.

### 🎯 Tại sao không sử dụng con trỏ trong java?

---

Vì khá phức tạp và không an toàn. Và đã có JVM chịu trách nhiệm cấp bộ nhớ nhầm.

### 🎯 Tại sao Java lại độc lập nền tảng?

---

Do java sửa dụng JVM, máy ảo java cung cấp cách thực thi mã Java độc lập với nền tảng.

### 🎯 Đối tượng trong java là gì?

---

Đối tượng là một thực thể trong thế giới thực, nó có trạng thái, hành vi, danh tính.

### 🎯 Java có mấy kiểu dữ liệu?

---

2 kiểu: nguyên thủy và tham chiếu (byte, short, int, long, float, double, char, boolean) và kiểu dữ liệu tham chiếu

### 🎯 String trong java là bất biến đúng không? Có mấy cách tạo 

---
String
Đúng. Có 2 cách tạo String là dùng từ khóa new và dấu double quotes (")
```
String str = "Hello";      
str.concat(" World");
System.out.println(str);    // Hello
      
str = str.concat(" World");
System.out.println(str);    // Hello World
```

### 🎯 Phân biệt String vs StringBuilder vs StringBuffer

---

String
- Bất biến
- Thread-safe
- Lưu trong Spring Pool
  String Builder
- Có thể thay đổi
- Không Thread-safe
- Nhanh hơn StringBuffer
  String Buffer
- Có thể thay đổi
- Thread-safe
- Chậm hơn StringBuilder


### 🎯 Stack và Heap trong java?

---

Stack Memory
- Hoạt động theo LIFO
- Quản lý tự động
- Lưu trữ biến local, gọi method
  Heap Memory
- Lưu đối tượng và Arrays
- Quản lý bởi Garbage Collector
- Kích thước lớn hơn Stack

### 🎯 Class có thể kế thừa interface không và ngược lại?

---

Class có thể implements nhiều interface. Interface chỉ có thể kế thừa interface khác không thể kế thừa class

### 🎯 Nguyên lý SOLID?

---

- `Single Responsibility Principle`: mỗi class chỉ nên có 1 nhiệm vụ duy nhất
- `Open/Closed Principle`: dễ mở rộng mà không cần sửa đổi code cũ
- `L`: class con có thể thay thế class cha mà không thay đổi hành vi chương trình
- `I`: nhiều interface nhỏ và cụ thể tốt hơn 1 interface lớn và chung chung
- `D`: các module cấp cao không nên phụ thuộc vào các module cấp thấp
