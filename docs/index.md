# Documentation Template

## 数式の記述

数式インライン：$ax^2 + bx + c = 0$  
数式ブロック
$$
P\cdot Q = \|P\|\|Q\|\cos\alpha \tag{1}
$$

## 警告文

!!! Note
    ノートです。

!!! Tip
    ヒントです。

!!! Warning
    警告です

!!! Danger
    危険です。

!!! Success
    成功です。

!!! Failure
    失敗です。

!!! Bug
    バグです。

!!! summary
    概要です。

## 詳細ブロック

??? Note
    ノートです。

??? Tip
    ヒントです。

??? Warning
    警告です。

??? Danger
    危険です。

??? Success
    成功です。

??? Failure
    失敗です。

??? Bug
    バグです。

??? summary
    概要です。

## SmartSymbols

- (tm)
- (c)
- (r)
- c/o
- +/-
- -->
- <--
- <-->
- =/=
- 1.4, etc.
- 1st 2nd etc.

## Keys

- ++ctrl+alt+delete++
- ++ctrl+c++
- ++fn++
- ++win++
- ++tab++
- ++prtsc++

## コードハイライト

```cpp
#include <iostream>
void main() {
  std::cout << "Hello world!" << std::endl;
}
```

## コードフェンス

??? Note
    ここは注釈ブロックです。

    ```yml
    markdown_extensions:
      - pymdownx.superfences
    ```

    ``` mermaid
    sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
    ```

## タスクリスト

- [x] タスク1
- [ ] タスク2
  - [x] 子タスク
  - [ ] 子タスク

## タブブロック

=== "タブ1"

    タブ1です。

=== "タブ2"

    タブ2です。

## ボタン

[ボタン1](https://github.com/YumaMatsumura){ .md-button }
[ボタン2](https://github.com/YumaMatsumura){ .md-button .md-button--primary }

## font awesome ロゴ

<i class="fa fa-arrow-circle-right" aria-hidden="true"></i> arrow-circle-right  
<i class="fa fa-bars" aria-hidden="true"></i> bars  
<i class="fa fa-file" aria-hidden="true"></i> file  
<i class="fa fa-folder" aria-hidden="true"></i> folder  
<i class="fa fa-folder-open" aria-hidden="true"></i> folder-open  
<i class="fa fa-code" aria-hidden="true"></i> code  
<i class="fa fa-terminal" aria-hidden="true"></i> terminal  
<i class="fa fa-check" aria-hidden="true"></i> check  
<i class="fa fa-download" aria-hidden="true"></i> download  
<i class="fa fa-upload" aria-hidden="true"></i> upload  

## 注釈

ここに注釈[^1]をつけます。

[^1]: 注釈
