```dart


void main(){
  //you can use \n in the last
  String loremIpsum = 'It is a long established fact\n' 
  'that a reader will be distracted by the\n'
  'readable content of a page when looking at its layout\n'
  'The point of using Lorem Ipsum is that\n'
  'it has a more-or-less normal distribution of letters,\n'
  'as opposed to using \'Content here, content here,\n'
  'making it look like readable English.\n';

  
  //you can also put all words in """  """;
  
  String loremIpsum1 = """
  It is a long established fact that a reader will be distracted by the
  readable content of a page when looking at its layout. The point of using
  Lorem Ipsum is that it has a more-or-less normal distribution of letters,
  as opposed to using 'Content here, content here', making it look like readable
  English.

  """;
  
  print(loremIpsum);
  print(loremIpsum1);
  
}