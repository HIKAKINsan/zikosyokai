```mermaid

graph LR;

    goto_bank["銀行で金をおろす

                  作業時間10分"]

    goto_bank-->goto_super["スーパーで卵を買う
                  作業時間10分"]

    goto_super-->goto_arau["卵を洗う

                  作業時間10分"]

    boil_hotwater["お湯を沸かす

              作業時間20分"]

   boil_eggs-->wash_egg["殻を割る

              作業時間10分"]

goto_arau-->boil_eggs
    boil_hotwater-->boil_eggs["卵をゆでる

              作業時間10分"]

    wash_egg-->crack_the_shell["塩を振る

              作業時間10分"]

    do_situps["背筋して腹を減らす

                作業時間30分"]

