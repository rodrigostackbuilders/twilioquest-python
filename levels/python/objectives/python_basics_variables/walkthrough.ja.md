# Toledoの試練に関するメモ

このバリアの周辺を少し探索すると、Toledo Van Possumの日誌の書き込みがもう1つ見つかります。

<blockquote>
2016年2月21日
<hr/>
<p>
Pythonの都市では、名前は重要な意味を持ちます。そのため、その人について説明したり、その人に割り当てられた目的を説明するために、名前が慎重に選ばれました。彼らは、市民のPythonコードにも同じことが当てはまると期待していました。
</p>
<p>
この試練を完了するため、指示に従い、2つの変数を宣言します。プログラミングでは、コードが動作するデータのプレースホルダーとして「変数」が使用されます。変数には通常、記述名が付けられているため、コードを読んでいる人は、どのような種類のデータが含まれているかを理解できます。
</p>
<p>
--TVP
</p>
</blockquote>
## ヒントとコツ

Toledoの日誌の残りの部分を読むと、役に立ちそうなヒントがいくつか見つかります。

<details>
<summary>コードファイルを作成して実行する方法を忘れました...</summary>
心配する必要はありません。完了した試練のバリアに戻り、*スペースバー*を押すと、前の試練に戻り、確認できます。必要に応じて何度でも、これらの試練で学習した手法を確認できます。このエリアの始めのいくつかの試練では、Pythonコードの記述方法と実行方法を理解しておく必要があります。

</details>
<details>
<summary>変数とは何ですか?その作成方法を教えてください。</summary>
[変数](https://www.w3schools.com/python/python_variables.asp)とは、プログラムが動作するデータのコンテナです。変数には、スペースを含まない連続した名前を付ける必要があります。Pythonでは、変数名に複数の単語を含める必要がある場合、スペースではなく`_`を使用します。例えば、変数を「my awesome thing」という名前にしたい場合、Pythonでは`my_awesome_thing`になります。

変数名はユーザーが作成します。変数名は、必要に応じて（ほぼ）任意の名前を付けることができます

コードの変数に値を__割り当てる__には、`=`（等号）を使用します。次のコードでは、数値`777`を`lucky_number`の名前の変数に割り当て、文字列`"Star Wars"`を`favorite_movie`の名前の変数に割り当てています。

```python
lucky_number = 777
favorite_movie = "Star Wars"

print(f"My luck number is {lucky_number}")
print(f"My favorite movie is {favorite_movie}")
```

</details>
<details>
<summary>この試練を完了するには何をする必要がありますか?</summary>
コードフォルダに、ファイル`variables.py`を作成します。

```bash
<%= env.TQ_PYTHON_CODE_PATH.value %>
```

このファイルで、文字列`"Cedric"`に設定された変数`favorite_robot`を作成します。`meaning_of_life`という名前の別の変数を作成します。これは数値`42`に設定されます。変数の宣言方法が分からない場合は、上記のヒントを参照してください。

コードを準備し、[*HACK*]ボタンをクリックし、試練を完了します。

</details>