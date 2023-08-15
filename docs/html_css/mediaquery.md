# メディアクエリ

## 768px以下の場合に変更
ウィンドウサイズが768px以下になったときに
=== "表示(max768)"
    <div class="disp">
        <p class="moji1">p要素1</p>
        <p class="moji2">p要素2</p>
        <p class="moji3">p要素3</p>
    </div>
    <style>
        .disp{
            display: flex;
            flex-direction: row;
        }
        .moji1{
            background-color: #559;
            flex: 1;
        }
        .moji2{
            background-color: #599;
            flex: 1;
        }
        .moji3{
            background-color: #959;
            flex: 1;
        }
        @media screen and (max-width:768px){
            .disp{
                flex-direction: column;
            }
        }
    </style>
=== "HTML(max768)"
    ```
    <div class="disp">
        <p class="moji1">p要素1</p>
        <p class="moji2">p要素2</p>
        <p class="moji3">p要素3</p>
    </div>
    ```
=== "CSS(max768)"
    ```
    .disp{
        display: flex;
        flex-direction: row;
    }
    .moji1{
        background-color: #559;
        flex: 1;
    }
    .moji2{
        background-color: #599;
        flex: 1;
    }
    .moji3{
        background-color: #959;
        flex: 1;
    }
    @media screen and (max-width:768px){
        .disp{
            flex-direction: column;
        }
    }
    ```
