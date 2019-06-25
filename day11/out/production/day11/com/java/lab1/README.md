# 实验题目
编写工资系统，实现不同类型员工(多态)的按月发放工资。如果当月出现某个Employee对象的生日，则将该雇员的工资增加100元。

# 实验目的
对象、继承、封装、多态、抽象类的组合应用。

# 实验说明
（1）定义一个Employee类，该类包含：
	private成员变量name,number,birthday，其中birthday 为MyDate类的对象；
	abstract方法earnings()；toString()方法输出对象的name,number和birthday。
	
（2）MyDate类包含:
	private成员变量month,day,year；
	toDateString()方法返回日期对应的字符串：xxxx年xx月xx日
	
（3）定义SalariedEmployee类继承Employee类，实现按月计算工资的员工处理。该类包括：
	private成员变量monthlySalary；
实现父类的抽象方法earnings(),该方法返回monthlySalary值；toString()方法输出员工类型信息及员工的name，number,birthday。
	
（4）参照SalariedEmployee类定义HourlyEmployee类，实现按小时计算工资的员工处理。该类包括：
	private成员变量wage和hour；
	实现父类的抽象方法earnings(),该方法返回wage*hour值；toString()方法输出员工类型信息及员工的name，number,birthday。
	
（4）定义PayrollSystem类，创建Employee变量数组并初始化，该数组存放各类雇员对象的引用。利用循环结构遍历数组元素，输出各个对象的类型,name,number,birthday,以及该对象生日。当键盘输入本月月份值时，如果本月是某个Employee对象的生日，还要输出增加工资信息。

# 提示
```java
        Employee[] ems = new Employee[3];
        ems[0] = new SalariedEmployee("步惊云", 201, new MyDate(2000, 6, 24), 9000);
        ems[1] = new HourlyEmployee("雄霸", 202, new MyDate(1990, 1, 1), 3001, 192);
        ems[2] = new SalariedEmployee("步惊云", 201, new MyDate(1992, 7, 19), 16000);
```