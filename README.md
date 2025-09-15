# Dart
void main() {   /*var v3 = List.empty(growable: true);    v3.add(10);   v3.add('문자 추가');   v3.add(true);   print(v3);    print(v3.runtimeType);*/


void main() {
  var names = ['Alice', 'Bob', 'Charlie'];
  names.removeLast();
  names.removeAt(0);
  names.removeRange(0, 1);
  print(names); // []

  var index = 2;
  var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  print(numbers[index]); // 3
  print(numbers[index - 1]); // 2
  print(numbers[index + 1]); // 4
  print(numbers[numbers.length - 1]); // 10
  print(numbers[0]); // 1
  print(numbers); // [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
}
