# Цикли
### Цикъл for

```c++

for( <Инициализация(i)>;  <Булево условие>;  <Актуализация(i)> )  
{  
	<Тяло на цикъла(i)> 
}

 ```
 Изпълнението работи така:
1. Изпълнява се инициализацията
2. Проверява се булевото условие;
	
	2.1  ако има стойност **лъжа**, цикълът приключва
	
	2.2 ако има стойност **истина**,  се изпълнава 3.
	
3. Изпълнява се тялото на цикъла.
4. Изпълнява се инкрементацията. Отиваме на точка 2.
### Цикъл while
```c++
while ( <Булево условие> )  
{  
	<Тяло на цикъла> 
}
 ```
Изпълнението работи така:
1. Проверява се булевото условие;
	
	1.1  ако има стойност **лъжа**, цикълът приключва
	
	1.2 ако има стойност **истина**,  се изпълнава 2.
	
2. Изпълнява се тялото на цикъла. Отиваме на 1.

### Цикъл do- while
```c++
do
{  
	<Тяло на цикъла>
	
}while ( <Булево условие> );
 ```
 Изпълнението работи така:
1. Изпълнява се тялото на цикъла.
2. Проверява се булевото условие

	2.1  ако има стойност **лъжа**, цикълът приключва

	2.2  ако има стойност **истина**,  отиваме на точка 1.

# Конвертиране на цикли.

![enter image description here](https://i.ibb.co/3pwkSHr/Capture.png)

### От for към while.
```c++
// for loop   
for(int i = 0; i < 10; i++)  
{  
	<Тяло на цикъла>
}  
  
// for loop converted to while loop   
int i = 0; //Инициализация
while(i < 10)  
{  
	<Тяло на цикъла>
	i++; // Актуализация
}
 ```
### От while към for.

```c++

// while loop  
while(*str != '\0')  
{ 
	<Тяло на цикъла>
	++str;
}

  
// while loop converted to for loop  
for(; *str != '\0'; ++str)  
{  
	<Тяло на цикъла>  
}
 ```
 ### От do-while към while.
```c++
// do-while loop
do 
{  
	<Тяло на цикъла>
	
} while ( <Условие> );


// do-while loop converted to while loop  
<Тяло на цикъла> 
while( <Условие> )  
{  
	<Тяло на цикъла>
}
 ```
Забележка! Предложените начини за преобразуване между цикли са с демонстрационна цел! Спрямо конкретната цитуация може да се постигне такова преобразуване и по много по-прост начин.