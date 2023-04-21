#include <iostream>
#include <vector>
void read(vector<int>& vec) {//принимаем ссылку на вектор
	int a;
	cout << "Enter size of vector: ";
	cin >> a;//вводим длину вектора
	for (int i = 0; i < a; i++) {//при помощи цикла
		int b;
		cin >> b;//вводим значение
		vec.push_back(b);//добавляем новый элемент вектора
	}
}