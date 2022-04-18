# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3
1. 番号付きリスト1
    1. 番号付きリスト1_1
    1. 番号付きリスト1_2
1. 番号付きリスト2
1. 番号付きリスト3
> お世話になります。xxxです。
> 
> ご連絡いただいた、バグの件ですが、仕様です。
> お世話になります。xxxです。
> 
> ご連絡いただいた、バグの件ですが、仕様です。
>> お世話になります。 yyyです。
>> 
>> あの新機能バグってるっすね

インストールコマンドは `gem install hoge` です

normal *italic* normal
normal _italic_ normal

normal **bold** normal
normal __bold__ normal

normal ***bold*** normal
normal ___bold___ normal

***

[Google先生](https://www.google.co.jp/)

normal ___bold___ normal
***

```php
class Hoge
　def hoge
　  print 'hoge'
　end
end
```

    class Hoge
    　def hoge
    　  print 'hoge'
    　end
    end

~~~ruby
　class Hoge
　  def hoge
　    print 'hoge'
　  end
　end
~~~

|header1|header2|header3|
|:--|--:|:--:|
|align left|align right|align center|
|a|b|c|




---

## menu
* [to header1](#header1)
* [to header2](#header2)
* [to test](#テスト　です)

<!-- some long code -->

[return to menu](#menu)
### header1
### header2
### テスト　です {#ttt}

***
<h2><a name="user-content-menu" href="#menu">menu</a></h2>
<a href="#header1">to header1</a>
<a href="#header2">to header2</a>

<!-- some long code -->

<a href="#menu">to menu</a>
<h3><a name="user-content-header1" href="#header1">header1</a></h3>
<h3><a name="user-content-header2" href="#header2">header2</a></h3>