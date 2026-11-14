```c
#include <stdio.h>
#include <3ds.h>

/*
 *はじめまして！電脳核-web9です！
 *主にニンテンドー3dsの実機をメイン環境として、自作ソフトやツールを開発しています！
 */

typedef struct {
    const char *main_env;
    const char *languages;
    const char *ai_tools;
    const char *editors;
} DevStyle;

int main(void) {
    //開発環境・スタイル
    DevStyle my_style = {
        .main_env  = "ニンテンドー3ds (実機での動作・エミュレーターでのテストを軸に開発)",
        .languages = "C/C++",
        .ai_tools  = "Claude等の生成AIも活用してます",
        .editors   = "devkitPro, サクラエディタ"
    };

    //開発でこだわってるところ
    const char *passion[] = {
        "とにかく3dsの実機上でプログラムを動かすこと",
        "限られたメモリの中で最適化を工夫すること",
        "UIや見た目にこだわること"
    };

    //目標
    const char *goals[] = {
        "自作ソフトのソースコード公開&ドキュメント整備",
        "自作Webサイトの構築",
        "C#を使ってPCのソフトを完成させること"
    };

    printf("メイン環境: %s\n", my_style.main_env);
    printf("使用言語  : %s\n", my_style.languages);
    printf("一番のこだわり: %s\n", passion[0]);

    while (aptMainLoop()) {
        //3ds実機で色々便利なソフトを目指して開発中！
    }

    return 0;
}
```
