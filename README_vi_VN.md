# Design Patterns

[English](./README.md) | Vietnamese

Các loại Design patterns

Có thể chia thành 4 nhóm patterns tùy thuộc vào tính chất của vấn đề mà chúng muốn giải quyết

- Gang of Four Patterns
- Enterprise Patterns
- SOA and Messaging Patterns
- Model-View Patterns

Hệ thống các mẫu Design pattern GOD hiện có `23 mẫu` được định nghĩa trong cuốn “Design patterns Elements of Reusable Object Oriented Software” và được chia thành `3 nhóm`

- [Design Patterns](#design-patterns)
	- [Creational Pattern](#creational-pattern)
		- [1. Factory Method](#1-factory-method)
		- [2. Abstract Factory](#2-abstract-factory)
		- [3. Builder](#3-builder)
		- [4. Prototype](#4-prototype)
		- [5. Singleton](#5-singleton)
	- [Structural Pattern](#structural-pattern)
		- [6. Adapter](#6-adapter)
		- [7. Bridge](#7-bridge)
		- [8. Composite](#8-composite)
		- [9. Decorator](#9-decorator)
		- [10. Facade](#10-facade)
		- [11. Flyweight](#11-flyweight)
		- [12.Proxy](#12proxy)
	- [Behavioral Pattern](#behavioral-pattern)
		- [13. Chain of Responsibility](#13-chain-of-responsibility)
		- [14.Command](#14command)
		- [15. Interpreter](#15-interpreter)
		- [16. Iterator](#16-iterator)
		- [17. Mediator](#17-mediator)
		- [18. Memento](#18-memento)
		- [19. Observer](#19-observer)
		- [20. State](#20-state)
		- [21. Strategy](#21-strategy)
		- [22. Template Method](#22-template-method)
		- [23. Visitor](#23-visitor)
	- [Tham khảo](#tham-khảo)


## Creational Pattern

Cung cấp các giải pháp khởi tao đối tượng một cách linh hoạt và phù hợp với bối cảnh sử dụng.

### 1. Factory Method

Định nghĩa một interface để tạo các đối tượng trong superclass nhưng cho phép lớp con quyết định instance nào sẽ được tạo.

### 2. Abstract Factory

Cung cấp một interface để tạo ra các họ đối tượng liên quan hoặc phụ thuộc lẫn nhau.

### 3. Builder

Tách biệt quá trình khởi tạo đối tượng phức tạp khởi các đại diện của nó

### 4. Prototype

Tạo ra các đối tượng dựa trên một mẫu đối tượng ban đầu

### 5. Singleton

Đảm bảo chỉ có duy nhất một instance của một class trong toàn bộ chương trình.

## Structural Pattern

Structural Patterns liên quan đến cấu trúc và mối quan hệ giữa các lớp và đối tượng nhằm tạo ra cấu trúc phần mềm dễ thay đổi và bảo trì hơn.

### 6. Adapter

Cho phép giao tiếp giữa các interface không tương thích

### 7. Bridge

Tách rời một lớp phức tạp thành hai phần riêng biệt: trừu tượng và triển khai.

### 8. Composite

Tạo ra cấu trúc cây để biểu diễn mối quan hệ whole-part giữa các đối tượng.

### 9. Decorator

Dynamically thêm chức năng mới cho đối tượng mà không ảnh hưởng đến các đối tượng khác.

### 10. Facade

Cung cấp một giao diện đơn giản cho một nhóm các lớp phức tạp.

### 11. Flyweight

Sử dụng chia sẻ để hỗ trợ tao hàng loạt các đối tượng hiệu quả hơn.

### 12.Proxy

Đại diện cho một đối tượng khác để kiểm soát truy cập vào đối tượng đó.

## Behavioral Pattern

Behavioral Patterns liên quan đến cách giao tiếp và trao đổi thông tin giữa các đối tượng và lớp. Các Pattern thuộc nhóm này gồm:

### 13. Chain of Responsibility

Cho phép chuyển các yêu cầu dọc theo chuỗi các đối tượng xử lý.

### 14.Command

Đóng gói yêu cầu thành các đối tượng có thể tham số hóa

### 15. Interpreter

Hỗ trợ việc định nghĩa biểu diễn văn phạm và bộ thông dịch cho một ngôn ngữ.

### 16. Iterator

Truy cập tuần tự các phần tử một tập hợp dữ liệu

### 17. Mediator

Định nghĩa một đối tượng trung gian để giao tiếp giữa các đối tượng.

### 18. Memento

Nắm bắt và lưu trữ trạng thái hiện tại của một đối tượng theo cách mà sau này nó có thể được khôi phục một cách smooth.

### 19. Observer

Định nghĩa phụ thuộc một chiều giữa các đối tượng

### 20. State

Cho phép một đối tượng thay đổi hành vi dựa trên trang thái nội bộ

### 21. Strategy

Định nghĩa tập các thuật toán có thể thay thế cho nhau để giải quyết một vấn đề.

### 22. Template Method

Định nghĩa bố cục xử lý chung cho một thuật toán, hoãn lại các bước cụ thể cho lớp con.

### 23. Visitor

Tách biệt các thuật toán khởi các đối tượng mà chúng hoạt động trên đó.


## Tham khảo

- [Design Pattern Tiếng Việt](https://nguyenphuc22.github.io/Design-Patterns/intro.html)
- [Tổng hợp 23 mẫu Design Patterns - Trợ thủ đắc lực của Developers](https://viblo.asia/s/tong-hop-23-mau-design-patterns-tro-thu-dac-luc-cua-developers-Q75wqJ67ZWb)
- [Giới thiệu Design Patterns](https://gpcoder.com/4164-gioi-thieu-design-patterns/)
- [Mẫu thiết kế (Design Pattern)](https://codecungnhau.com/mau-thiet-ke-design-pattern/)
- [Cùng học Design Patterns](https://viblo.asia/s/cung-hoc-design-patterns-z45bx8zqZxY)
- [Factory Method Design Pattern](https://www.youtube.com/watch?v=nimvrH0eruQ&list=PLoaAbmGPgTSOrVuxwbnDJ14U9J6CXJXUk&index=15)
- [Design pattern trong Java, mô hình UML và code ví dụ](https://viblo.asia/p/design-pattern-trong-java-mo-hinh-uml-va-code-vi-du-RQqKLgP457z)
- [Design Pattern là gì? Design Pattern trong Java](https://stackjava.com/design-pattern/design-pattern-la-gi-design-pattern-trong-java.html)
- [Design Pattern series](https://viblo.asia/s/design-pattern-series-68Z00nN9ZkG)
- [Design Patterns Là gì](https://viblo.asia/p/design-patterns-la-gi-bJzKmJpPZ9N)