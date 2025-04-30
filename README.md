# CS352Source code:
int main() {
  int x;
  x = 5;
  return x;
}

Token stream:
KEYWORD: int
ID: main
SYMBOL: (
SYMBOL: )
SYMBOL: {
KEYWORD: int
ID: x
SYMBOL: ;
ID: x
SYMBOL: =
NUMBER: 5
SYMBOL: ;
...

Abstract syntax tree:
Program
  Function: main returns int
    Declaration: int x
    Statement:
      Assign to: x
        Const: 5
    Statement:
      Return:
        ID: x
