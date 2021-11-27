void main(){
String personName = 'John';
int age = 40;
double height = 1.80;
bool isOpen = true;
List numbers = [22, 55, 77, 88];
Map<String, dynamic> _person = {
    'name': 'john',
    'age': 25,
    'job': 'developer'
};

print(personName);
print(numbers);
print(_person);

  
 /*
In above
String/int,bool etc are variable type
personName, age/numbers are variable name
= means assignment
'john', 40 are value

while naming a variable first name must be lowercase(camel case naming).you shouldn't
put number in first place like this 5name (but number after first letter is ok like b5person);
  */ 



}