```mermaid

graph LR;

    goto_bank["500円を奪う

                  作業時間10分"]

    goto_bank-->goto_super["スーパーで150円のカップラーメンと100円のチャーシューを買う
                  作業時間10分"]

    goto_super-->goto_yakyoku["薬局で250円のコショウを買う

                  作業時間10分"]

    boil_hotwater["お湯を沸かす

              作業時間20分"]

   boil_eggs-->wash_egg["チャーシューを袋から取り出す

              作業時間10分"]


    boil_hotwater-->boil_eggs["カップラーメンをゆでる

              作業時間10分"]

    wash_egg-->crack_the_shell["チャーシューを入れる

              作業時間10分"]

    crack_the_shell-->sprinkle_wit_salt["コショウを振る

              作業時間10分"]

    do_situps["背筋して腹を減らす

                作業時間30分"]

