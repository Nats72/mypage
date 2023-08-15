# 真ん中寄せ

## テキストの真ん中寄せ
p要素の中身(文字)がp要素の中で真ん中寄せされます。
=== "表示(text-align)"
    <p class="moji">p要素</p>
    <style>
        .moji{
            text-align: center;
            background-color: #559;
        }
    </style>
=== "HTML(text-align)"
    ```
    <p class="moji">p要素</p>
    ```
=== "CSS(text-align)"
    ```
    .moji{
        text-align: center;
        background-color: #559;
    }
    ```

## marginを使った真ん中寄せ
p要素がブロックではない場合(widthが100%ではない)に、横のマージンをautoで自動調整することで真ん中寄せします。
=== "表示(margin)"
    <div class="flex">
        <p class="moji">p要素</p>
    </div>
    <style>
        .flex{
            display: flex;
            background-color: #955;
        }
        .moji{
            margin: 0 auto;
            background-color: #559;
        }
    </style>
=== "HTML(margin)"
    ```
    <div class="flex">
        <p class="moji">p要素</p>
    </div>
    ```
=== "CSS(margin)"
    ```
    .flex{
        display: flex;
        background-color: #955;
    }
    .moji{
        margin: 0 auto;
        background-color: #559;
    }
    ```

## flex(align-items)を使った真ん中寄せ
p要素がブロックではない場合(widthが100%ではない)に、横のマージンをautoで自動調整することで真ん中寄せします。
=== "表示(align-items)"
    <div class="flex">
        <p class="moji">p要素</p>
    </div>
    <style>
        .flex{
            display: flex;
            align-items: center;
            background-color: #955;
        }
        .moji{
            background-color: #559;
        }
    </style>
=== "HTML(align-items)"
    ```
    <div class="flex">
        <p class="moji">p要素</p>
    </div>
    ```
=== "CSS(align-items)"
    ```
    .flex{
        display: flex;
        align-items: center;
        background-color: #955;
    }
    .moji{
        background-color: #559;
    }
    ```
