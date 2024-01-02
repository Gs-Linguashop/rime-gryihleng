# 諧聲上古音輸入法（全拼、雙拼）

基於上古音諧聲的[Rime](https://rime.im)輸入方案

## 簡介

拼寫信息請參考[描述](src/description.md)文件；字典主要由中古韻圖、諧聲資料和詩經韻部反推生成，目前還沒有校對完全

雙拼鍵盤佈局請參考[雙拼聲母鍵盤圖](src/double_first_letter(consonant+medial).txt)和[雙拼聲母鍵盤圖](src/double_second_letter(rhyme).txt)文件
* 音節首拼：上古聲母諧聲類+介音
* 音節尾拼：上古韻母
* 韻母可以用“;”代替，實現簡碼

按“`”鍵使用[朙月拼音](https://github.com/rime/rime-luna-pinyin)反查上古音，當然也可以替換成其它反查輸入方式

授權條款：見 [LICENSE](LICENSE.txt)