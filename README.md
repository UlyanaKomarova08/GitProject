#include <iostream>
#include <vector>
void read(vector<int>& vec) {//��������� ������ �� ������
	int a;
	cout << "Enter size of vector: ";
	cin >> a;//������ ����� �������
	for (int i = 0; i < a; i++) {//��� ������ �����
		int b;
		cin >> b;//������ ��������
		vec.push_back(b);//��������� ����� ������� �������
	}
}