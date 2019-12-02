# Kivi-App, ������� ���������� �� Angular 8.3.0 
**��������� ����� �� PHP � MySQL / unit-testing Jasmine + Karma / e2e testing Jasmine + Protractor**

���������� Kivi-App ������������ ����� "��������" �������� ����� � �������� 3 ������� �������� �����:
* /
* /rafting
* /semeyniy-rafting

�� ���� ��������� ���������� ������ ������� ����� � ���������.
���������� ������� �� ������ ��������� ������� �� Bootstrap 4.


## ����������

### ����� �������� �����
�� ������ ������� ���� 5 ��������� ���� �������� �����, ����������� ����������� ���������� ������ �����. 4 ����� � ��������� ����� �������� �� �������:
1. �������� ������ (�����)
2. ������ ������ (�����)
3. �������� (�����)
4. �������� ������ (�������)

����� ����� ����������� ����� ��������.
������ ����� ����� ��������� ��������� ������ � ������������ ����� ������ ����� ����� ���������, ���� ��� ����. ���� ��� ������ ������� ���������, �� ����� �������� ��������� �� �� ������ � ���� ��� �����. ����� ��������� ������ ������� �� ��������� �� �����. ��� ������ ��������� ������ ����� ���� 3 �������� ������:
* �������� ������ ������ �������
* ��������� ������ �� �������
* ������ ������� ��������� ���������� ������


### ��������� ����� 
��������� ������ �� ���� ������������ PHP ��������. 
��� ���������� ���������� �������� ������ �� ���� ������������ � �� �� MySQL. ����� ������ ������������ ���������� ������, ��� ������ �������� �� ��������� ��������� � ���������� �� ������� � ����������.
��� ������ ������ ������ � �� ������ ���������� � ���������� ��������� �� ������.
���� � ������� ��������� ����: [/backend/formbottom.php](https://github.com/DevAleks/Kivi/tree/master/backend/formbottom.php)

### ���������� �� ��������� �����
� ������� ������� ������������:
* ������� ����� � Youtube
* "��������" Fancybox
* ������ Vk



## ����������
���������� ��������� �� Angular 8.3.0, ��������� ����� �� PHP � MySQL, unit ������������ Jasmine + Karma, e2e ������������ Jasmine + Protractor.

### �������� Angular
* ���������� [/src/app/components/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/)
* ������� [/src/app/services/](https://github.com/DevAleks/Kivi/tree/master/src/app/services/)
* Pipe [/src/app/pipes/](https://github.com/DevAleks/Kivi/tree/master/src/app/pipes/)
* ������ [/src/app/app.module.ts](https://github.com/DevAleks/Kivi/tree/master/src/app/app.module.ts) (������ 41)
* ����� - ��������� � ���������� ������, �������� ������ � ��������� ������ �� �������:
* - [/src/app/components/callorder-form/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/callorder-form/)
* - [/src/app/components/first-form/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/first-form/)
* - [/src/app/components/footer-form/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/footer-form/)
* - [/src/app/components/question-form/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/question-form/)
* - [/src/app/components/top-form/](https://github.com/DevAleks/Kivi/tree/master/src/app/components/top-form/)
* ��������� ������ �� Json ����� [/src/app/components/first-block/first-block.component.ts](https://github.com/DevAleks/Kivi/tree/master/src/app/components/first-block/first-block.component.ts) (������ 25)
* ����� <script ...> � ��������. �������������� ���������[/src/app/components/scripthack](https://github.com/DevAleks/Kivi/tree/master/src/app/components/scripthack) � ������ ������ � ������� [/src/app/components/subscribe-block/subscribe-block.component.html](https://github.com/DevAleks/Kivi/tree/master/src/app/components/subscribe-block/subscribe-block.component.html)
  


## Unit ������������
������� ������� �������� 80% ���� �������. ��� ������ ���������� ����� � ����� ����������: /src/app/


## E2E ������������
������� �� 2 �����. ������� ������ ��������� �������� �������� � ��������� 3 �������� use case ��� ���� �������� �����.
��� ������ ���������� ���: [/e2e/src/](https://github.com/DevAleks/Kivi/tree/master/e2e/src/)

### ������ �����, �������� ��������
������� ������� ��������� ��������� ����� ���������:
* ������� �������� �� �������� �����������
* ��������, ������������ �� Json ����� ��� �������� ����������

� ����� ����������� ������������ ������ "��������" � �������� �� ������ �� ������ ��������.
����: [/e2e/src/app.e2e-spec.ts](https://github.com/DevAleks/Kivi/tree/master/e2e/src/app.e2e-spec.ts)

### ������ �����, ����� �������� �����
����������� �������� 3 ���������:
1. ��������/�������� ���������� ���� ����� �� ����
2. ��������� 2-� ������ ������������ ���������� �����
3. �������� �������� ������ �� ���������� � ������������ ������

����: [/e2e/src/app-kivi-test-form.e2e-spec.ts](https://github.com/DevAleks/Kivi/tree/master/e2e/src/app-kivi-test-form.e2e-spec.ts)
