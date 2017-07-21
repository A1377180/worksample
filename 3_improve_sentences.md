selfはインスタンスオブジェクト自身を指しています。クラスの中でインスタンスオブジェクトを呼び出す際やそのインスタンスオブジェクトを呼び出す際は、selfを使用します。
selfを実際に使ってみましょう。  
```python
>>> class Test:
...     def __init__(self):
...         self.a =40
...     def xxx(self, x):
...         return self.a + x
... 
>>> test = Test()　　　#インスタンスの生成
>>> test.xxx(10)      #メソッドの呼び出し
50
```
xxxが呼ばれると、selfにTestというクラスのそのインスタンスが入ります。
