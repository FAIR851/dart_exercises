# Week 7 Activity - Dart Variables and Operators

## Name
Ibarra, Andrew Kim

## Scenario
This program simulates a student's grade computation.  
It declares variables of different types (`String`, `int`, `double`, `bool`), applies arithmetic and comparison operators, and prints the results.

## Code Example
```dart
void main() {
  String studentName = 'Ibarra, Andrew Kim';
  int quizScore = 25;
  double examScore = 74.5;
  bool passed = true;

  double totalScore = quizScore + examScore;   // arithmetic (+)
  bool isOver100 = totalScore > 100;           // comparison (>)

  print('Student: $studentName');
  print('Total Score: $totalScore');
  print('Is the total over 100? $isOver100');
  print('Passed? $passed');
}
