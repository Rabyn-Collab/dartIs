
```dart

void main (){
//upperscase & lowercase
String title = 'Dart Sdk';
print(title.toUpperCase());
print(title.toLowerCase());

//contains & replaceAll
String lovePizza = 'I love pizza';
bool containsPizza = lovePizza.contains('pizza');
print(containsPizza);

String lovePasta = lovePizza.replaceAll('pizza', 'pasta');

print(lovePasta);
/*
There are lot of methods to manupulate String you can try.
*/
    
}