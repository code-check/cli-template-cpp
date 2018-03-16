# コマンドラインアプリケーション(CLI アプリ)作成用テンプレート(C++)

[main.cpp](src/main.cpp)を編集して、CLIアプリを実装してください。  
チャレンジ内でファイルの作成が許可されていれば、可読性等のためにファイルを分割する事も可能です。

## コマンドライン引数の取得方法
通常のC++アプリケーションと同じように、`int argc` と `char * argv[]` を使用してください。

```cpp
int main(int argc, char * argv[])
{
  // code to run
  return 0;
}
```

## コマンド実行結果の標準出力への出力
cout、printf等標準出力に出力する任意のメソッドが使用可能です。

``` c++
  cout << argv[0] << endl
```

## コンパイルについて
コンパイルには[clang](http://clang.llvm.org/)のg++コマンドを使用しています。

コンパイルオプション等を変更する場合は[makefile](makefile)を変更してください。
